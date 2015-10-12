languagetool-tinymce
===========

### LanguageTool for TinyMCE

languagetool-tinymce is a plugin for TinyMCE. It is based on the AtD TinyMCE Plugin.  

[LanguageTool] (https://www.languagetool.org/) is an Open Source proof­reading program for English, French, German, Polish, and more than 20 other languages.

[After the Deadline](http://www.afterthedeadline.com) is an [open source](http://open.afterthedeadline.com) software service that checks [spelling, style, and grammar.](http://www.afterthedeadline.com/features.slp).

This project contains a modified version of the AtD TinyMCE Plugin.

Changes:
* AtD-code, this has been simplified for use with LanguageTool - it now assumes there's no markup anymore in the text field (not even bold etc)!
* editor-plugin, the AtD-pluzgin for TinyMCE, heavy modified for LanguageTool.


### Quick Start

1.  Follow steps of [LanguageTool - Integration On Websites] (Integration On Websites).

### Examples

*   [Demo](https://www.languagetool.org/)

### Localization

Localization is done using the i18 support of tinyMCE. Separate plugins are available for each language, and potentially, if using themes, also a language plugin within the theme.

### License

[LGPL](http://www.opensource.org/licenses/lgpl-2.1.php)

### Credits

* This code is a derivate(hack) of the spellcheck plugin from Moxiecode.  Thanks for the hard work guys.
* Original Author: Raphael Mudge (Automattic)
* Heavily modified by Daniel Naber for [LanguageTool] (http://www.languagetool.org)
