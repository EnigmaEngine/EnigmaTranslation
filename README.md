# EnigmaTranslation

This is the hub for internationalization and localization of Enigma Engine. These files are used to translate the UI into different languages.

Through the provided locale folders, assets can be translated, including but not limited to text, images, and audio. When the game is built, the translations are pulled from this repository and compiled into the game.

## Adding a new language

Follow these steps to add a new language:
1. Create a new language folder with the correct locale code for your language.
	- The locale code is based on the language as well as the region you wish to translate for. For example, Braziliian Portuguese is pt-BR.
	- As an example of regions, American English is `en-US`, where as British English is `en-GB`.
2. Add the corresponding entries to the `index.xml` file.
	- You will need to add a new `<locale>` tag, which will provide a list of contributors.
	- You will also need to provide translations for basic UI elements needed for the user interface, such as the "Okay" button.
	- You will also need to go to the other languages and provide a translation for the name of your language. For example, the `Portuguese` language needs to contain the Portuguese words for `French`, `Italian`, `German`, `English`, etc.
3. Add the translations to the locale's folder.
	- Be sure to translate text and, if able, images and audio assets.

## Contributions

Contributions to this project are HIGHLY encouraged.
