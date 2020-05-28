# Wavelet Translatables

If you came here to help translating Wavelet - great, your contribution will be much appreciated!

Don't worry if you're unfamiliar with Git. You can follow the instructions at the bottom, altough following the instructions for advanced users will be most appreciated.

Instructions for advanced users or for people who want to learn something (use Google):
1) Create a fork of this repository.
2) Pull your fork so you can work locally, using your favorite text editor.
3) Create a copy of the values folder in the root of your fork and name it values-{language code}*
4) Before you go ahead and translate everything you can find in strings.xml, there are a few things to keep in mind:
  - %i and %s are substitutes. These will be replaced programmatically by a word or a number, so you must keep them in place. However, you can move them around to match your grammar.
  - \n is an enter. Keep these in place too.
  - Do not add unnecessary tabs or spaces.
  - Do not mess around with the tags around the strings.
  - Keep your translations brief and clear. Long translations might cause overflow in the UI.
5) Once you're satisfied, commit and push your changes to your branch.
6) Create a pull request mentioning the language you translated to.
7) You might want to watch this repository in case the default file gets updated and your file needs to be updated accordingly.

Instructions for anybody:
1) Go to https://github.com/Pittvandewitt/Wavelet-strings/blob/master/values/strings.xml
2) Read step 4 in the instructions above
3) Create an issue with your translated strings.xml file attached. Name the title something like 'Translation for values-en' and replace 'en' with your country code*. Mention the language you translated to in the message, just to be sure.

\* A list of all country codes can be found here: https://www.localeplanet.com/icu/