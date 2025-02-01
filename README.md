# TinyMCE Emojis

Provides an editor button to insert emojis (also known as emoticons) into
content.

The button opens a dialog where you can browse through several categories or
search by (English) keywords.

![Screenshot of the open dialog](https://raw.githubusercontent.com/backdrop-contrib/tinymce_emojis/1.x-1.x/screenshots/emojis-dialog.png)

Additionally, if you write a colon followed by some characters in content, the
emoji library will provide suggestions to pick from in a popup collection.

![Autocomplete when typing](https://raw.githubusercontent.com/backdrop-contrib/tinymce_emojis/1.x-1.x/screenshots/emoji-autocomplete.png)

## Installation

- Install this module using the official [Backdrop CMS instructions](https://docs.backdropcms.org/documentation/extend-with-modules)
- Edit your custom TinyMCE profile to add the button to the toolbar

## Dependencies

- TinyMCE

Important note: your database has to be able to deal with emojis (utf8mb4),
which is usally the case, but might not in some edge cases.

## Issues

Bugs and feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/tinymce_emojis/issues)

## Current Maintainers

- [Indigoxela](https://github.com/indigoxela)

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
