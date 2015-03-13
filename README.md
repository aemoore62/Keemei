# Keemei

[![Join the chat at https://gitter.im/jairideout/Keemei](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/jairideout/Keemei?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

*Validate QIIME metadata in Google Sheets*

Keemei (canonically pronounced *key may*) is an open-source, BSD-licensed tool for validating [QIIME](http://qiime.org/) metadata stored in [Google Sheets](http://www.google.com/sheets/about/). It is written in [Google Apps Script](https://developers.google.com/apps-script/) for easy integration with Google Sheets.

**Note:** Keemei is currently under active development and undergoing internal testing. Once complete, an initial public release will be installable as a [Google Sheets add-on](https://developers.google.com/apps-script/add-ons/).

## Getting started

To get started with Keemei, [browse the docs](https://github.com/jairideout/Keemei/wiki).

## Getting involved

Keemei is intended to be an open development effort, so if you'd like to get involved, get in touch on [Gitter](https://gitter.im/jairideout/Keemei) or the [issue tracker](https://github.com/jairideout/Keemei/issues).

## Licensing

Keemei is available under the new BSD license. See [LICENSE](LICENSE) for more details.

Keemei uses the [SheetConverter](https://sites.google.com/site/scriptsexamples/custom-methods/sheetconverter) library, which is available under the 2-clause BSD license. See [licenses/SheetConverter.txt](licenses/SheetConverter.txt) for more details. The SheetConverter library is distributed with Keemei because [Google discourages the use of libraries in add-ons](https://developers.google.com/apps-script/add-ons/publish). Instead, they recommend copying the library code into the add-on and using it directly.
