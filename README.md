Translations for CodeIgniter System Messages
This project contains translations for the CodeIgniter system messages folder, system/language/english. A changelog has been added to the repository, so you can track updates between official releases.

Copy the folder(s) for the idioms you are interested in, from inside the language folder of this project to your application/language folder.

You may then use the CodeIgniter Language class to reference the translations directly, or you can set the default language in application/config/config to the idiom appropriate for your webapp.

There have been several questions about RTL languages, but that is not something addressed in CodeIgniter. The suggested approach is to keep any translations in left-to-right order, and to deal with right-to-left rendering through the "dir" attribute of an HTML element, or the "direction" attribute in CSS.
