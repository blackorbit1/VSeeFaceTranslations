# VSeeFace translations

It is possible to translate [VSeeFace](https://www.vseeface.icu/) into different languages and I am happy to add contributed translations! To add a new language, first make a new entry in `VSeeFace_Data\StreamingAssets\Strings\Languages.json` with a new language code and the name of the language in that language. The language code should usually be given in two lowercase letters, but can be longer in special cases. For a partial reference of language codes, you can refer to [this list](https://github.com/nohamelin/simple-locale-switcher/wiki/Language-Names-for-Locale-Codes). Afterwards, make a copy of `VSeeFace_Data\StreamingAssets\Strings\en.json` and rename it to match the language code of the new language. Now you can edit this new file and translate the `"text"` parts of each entry into your language. The `"comment"` might help you find where the text is used, so you can more easily understand the context, but it otherwise doesn't matter.

New languages should automatically appear in the language selection menu in VSeeFace, so you can check how your translation looks inside the program. Note that a JSON syntax error might lead to your whole file not loading correctly. In this case, you may be able to find the position of the error, by looking into the `Player.log`, which can be found by using the button all the way at the bottom of the general settings.

Generally, your translation has to be enclosed by doublequotes `"like this"`. If double quotes occur in your text, put a \ in front, for example `"like \"this\""`. Line breaks can be written as `\n`.

Translations are coordinated on GitHub in the [VSeeFaceTranslations](https://github.com/emilianavt/VSeeFaceTranslations) repository.
