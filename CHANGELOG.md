#Changelog

##0.1.1 (January 1, 2015)

- Added tests.
- Bootstrap template now includes parameters after each function name with optional brackets.
- Markdown template now includes parameters after each function name with optional brackets.
- Dash template now includes parameters after each function name with optional brackets.
- Added parameters and properties to dash export.

##0.1.0 (December 24, 2014)

- Restructured data returned from `utils.parseData` method.
- Renamed method `utils.findPackage` to `utils.findPackagePath` to better reflect it's purpose.
- package.json contents is now passed through to the template as `pkg`.
- Bootstrap template redesigned.
- Bootstrap template updated to include homepage link and version number.
- Bootstrap template now includes deeplinks to individual files.
- Removed options from Bootstrap template for toggling code blocks and private methods.
- Consolidated Bootstrap template resources.
- Markdown template updated to include homepage link and version number.
- Fixed issue with improperly detecting language through highlight.js handlebars helper.

##0.0.18 (December 12, 2014)

- Improved Dash docset generation.
- Removed brackets from around optional tag names.

##0.0.17 (December 7, 2014)

- Removed paragraph tag from descriptions.
- Forced language on highlight method.

##0.0.16 (December 6, 2014)

- Added promise to buildDashDocSet method.

##0.0.15 (December 5, 2014)

- Added offline support to dash documentation.

##0.0.14 (December 5, 2014)

- Added new export to Dash.
- Updated to latest version of dox.

##0.0.13 (October 16, 2014)

- Large code blocks are now pre-highlighted.
- Updated to latest version of dox.

##0.0.12 (October 2, 2014)

- Added text overflow to methods to prevent overlapping body content.

##0.0.11 (September 11, 2014)

- Removed tag made redundant by doxdox 0.5.0 update.
- Fixed bug related to relative directories.
- Added findPackage method to utils.

##0.0.10 (September 8, 2014)

- Updated to latest version of Handlebars.

##0.0.9 (September 6, 2014)

- Fixed issue with relative source paths.
- Updated to latest version of dox.

##0.0.8 (September 5, 2014)

- Updated to latest version of dox.

##0.0.7 (August 18, 2014)

- Added support for examples tag.
- Added support for returns tag.
- Added both `bower_components` and `gulpfile` to default walk exceptions.

##0.0.6 (August 17, 2014)

- Added support for custom Handlebars templates.
- Improved built-in template selection (now case insensitive).

##0.0.5 (August 17, 2014)

- Added support for crawling directories.
- Added support for pulling title and description from package.json files.
- Added "Back to Top" link.
- Minor visual changes.

##0.0.4 (August 10, 2014)

- Improved Node.js support with the addition of a new method: parseFile.

##0.0.3 (August 10, 2014)

- Updated doxdox to be importable through Node.js

##0.0.2 (August 7, 2014)

- Added output flag.
- Added syntax highlighting to Bootstrap layout.

##0.0.1 (August 3, 2014)

- Initial public release.
