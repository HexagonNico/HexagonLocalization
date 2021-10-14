# Add a new type of translation

In case none of the provided translations suit your needs, you can create your own translation by extending the `GenericTranslation` class as shown in the example below.

```
	[CreateAssetMenu(menuName ="My Assets/My translation"]
	public class CustomTranslation : GenericTranslation<MyObject>
	{

	}
```

This will let you create a custom translation to translate a `MyObject`.

It is also possible to change the translation method.

```
	[CreateAssetMenu(menuName ="My Assets/My translation"]
	public class CustomTranslation : GenericTranslation<MyObject>
	{
		public override MyObject Translate(int language)
		{
			// Your translation here...
		}
	}
```

You will then be able to use your custom translation in a [custom translator](CustomTranslator.md).

#### [Back to index](../README.md)
