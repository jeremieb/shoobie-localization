![Shoobie](https://repository-images.githubusercontent.com/267961442/68e5db5b-d7e5-4bd5-9e1d-fce69bca0515)

# Shoobie community language support

### Localization

Help [Shoobie app](https://shoobie.app/) to be as inclusive as possible by supporting more languages.

As part of the community, if you would like to see your native language supported, feel free to submit a pull request to the repository.

To allow discussion thread for each language, please don't add multiple languages in the same pull request. This will give opportunities for peer review.

### Disk Structure
Languages are structured with main folders per language, like this:

`en.lproj/Localizable.strings`

Where `en` is replaced by the [ISO 639-1 two-letter language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes), and the `Localizable.strings` file is structured as per the English (`en`) version.

Please do not include any other files in a pull request.

### Localization

Strings are denoted as `"KEY"` = `"value"`, where the keys remain the same across all languages, and the values are localized. There must be a `;` at the end of each line.

`"water_label" = "WATER TEMP";`

### Credits

Please append the name you would like to be credited by to the pull request or the comment block at the top of the Localizable.strings file.

```
/* 
  Localizable.strings
  
  ====================
  English
  ====================
  Created by YOUR NAME
  ====================
  
*/
```

### Source

This project has been inspired by Steven Troughton-Smith and the community language support for the app [Broadcast](https://github.com/steventroughtonsmith/broadcasts-localization)
