# Add a new type of translator

In case you wanted to add your own type of translator, you can do so by extending the base class `BaseTranslator` as show in the example below:

```
	public class MyTranslator : BaseTranslator
	{
		[SerializedField] private GenericTranslation<MyObject> translation;
		[SerializedField] private UnityEvent<MyObject> unityEvent;

		public override void Translate()
		{
			// Apply the translation here...
			this.unityEvent.Invoke(this.translation.Translate());
		}
	}
```

The `Translate()` method will be called every time the language in [LanguageSettings](LanguageSettings.md) is changed.

#### [Back to index](../README.md)
