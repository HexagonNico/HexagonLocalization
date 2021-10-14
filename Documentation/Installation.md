# Installing and quick start

## Install from .unitypackage file

To install a Unity package, open your project and go to *Assets => Import Package => Custom Package*.

This will open an 'Open File' window, choose the *HexagonLocalization.unitypackage* file.

To finish the installation, click on *Import* and Unity will import the content of the package into your project.

## Install from .zip file

Extract all the files from the .zip file, the extracted folder should be called *HexagonLocalization*.

Open your project in Unity and drag the folder from your file explorer to the project window. Unity will import the whole content of the folder into your project.

## Quick start

If you have installed everything correctly, you should be able to create assets for the package.

Go to *Assets => Create => HexagonLocalization* and you should see all the assets added by the package.

The [Languages asset]() is the asset that will contain all the languages your game is translated into. You will only need one in your project.

The other four are [translations assets](), they will be used to write and apply translations for your game.

If you click on the *Add component* button on any object in your scene you should now be able to see a section called *Hexagon Localization* that contains all the [translator components]() and the [LanguageSettings]() component.
