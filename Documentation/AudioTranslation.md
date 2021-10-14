# Audio translation

An Audio translation is a type of [translation](CreateTranslation.md) that can modify an AudioClip depending on the language settings.

An Audio translation will need a reference to the [LanguagesAsset](LanguagesAsset.md) to provide language options. You can click on *Create Languages Asset* to create one and then assign it in the inspector.

![Empty translation](../Pictures/EmptyAudio.png)

After adding a reference to the [LanguagesAsset](LanguagesAsset.md) you should be able to add translations to the list. Each translation consists in a language and a reference to an AudioClip.

The language can be chosen with a popup among one of the languages you added in your [LanguagesAsset](LanguagesAsset.md). The [AudioTranslator](AudioTranslator.md) will use this value to choose a translation.

The AudioClip reference will be returned when applying the translation with an [AudioTranslator](AudioTranslator.md) component.

![Example translation](../Pictures/ExampleAudioTranslation.png)

#### [Back to index](../README.md)
