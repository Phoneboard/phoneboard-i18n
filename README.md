Quick tutorial to translate.
==================================
For translating, you need to have git and the Qt Linguist tool
[How to install and use git](https://help.github.com/articles/set-up-git/)
[Download Qt Linguist](https://github.com/lelegard/qtlinguist-installers/releases)


### Creating a translation
To add a new language you need to use the [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) code as the file name, for example Portuguese (ISO 639-1 code "pt")

Copy the en.ts and rename it to pt.ts

    cp en.ts pt.ts

Open the file with Qt Linguist to edit them

    linguist pt.ts

When you've finished create a pull request.

Translation credits.
==================================
* Arabic    [Haythem Hamdi]
* Dansk     [Olgierd Nowakowski]
* Polish    [Jakub Werwiński]
* Hungarian [Dani Bá]
* Cambodian		[IC Fix Sothy]
* Italian		[Nicola Ripiccini]
* Finnish		[Ruuben Vuolasranta]
* French		[Occaz'out]
