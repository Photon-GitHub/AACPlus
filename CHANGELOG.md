## v1.4.1
* Improved performance on 1.13
* plugin.yml update for 1.13

## v1.4.0
+ {server} placeholder
* Improved file handling
* Improved performance
* Fixed some false blocking
* Fixed a bug which caused case-sensitive command handling

## v1.3.2
* Update for the new AACAdditionPro command aliases.

## v1.3.1
+ New config handling
* Support for multiple digit version numbers

## v1.3.0
+ AACHider now supports blocking AACAdditionPro's commands as well
+ AACHider now uses AACAdditionPro's placeholder framework... if you ever want to know the ping of the player who executed a command associated with AAC / AACAdditionPro.
  Sensible features: expandable architecture, {world} placeholder and better overall performance.
+ AACHider does now support an empty replacement message, which allows for multi-line handling via commands.
* Handling of backslashes was missing in some cases
* Improved the message detection algorithm
* Lots of refactoring and code cleanup
* The config system now has a caching system for improved performance
* Updated and added the documentation so future development is easier

## v1.2.1
- Added aacverbose to the hidden commands (forgot it in 1.2.0)
- Fixed an IllegalArgumentException when parsing vanilla minecraft messages

## v1.2.0
- Restructured default config layout/wording
- Added option to block all AAC commands

## v1.1.0
- A few bug patches
- Added option to block Fastbow chat warnings

## v1.0.0
- Initial Release
