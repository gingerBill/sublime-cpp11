# Sublime C++11

This package provides better support for C and C++11 languages in Sublime Text.

It is primarily focused on improving the default C/C++ syntax highlighting shipped with Sublime Text.

## What is improved?

This color scheme has the ability to allow for custom styling conventions. The default styling convention is this:

*`Types_Are_Like_This` or `TypesAreLikeThis`
* `CONSTANTS_ARE_LIKE_THIS`

It also includes a selection of custom types that are used numerous in projects (i.e. `uint`, `u32`, `s64`, `float32`, `usize`, etc.) and custom keywords (i.e. `bit_cast`, `internal`, `global`, `local_persist`).

## How to customize

You can edit the packages within Sublime using [PackageResourceViewer](https://packagecontrol.io/packages/PackageResourceViewer). `JSON-tmLanguage` files can be converted to their xml equivalent `tmLanguage` using [AAAPackageDev](https://packagecontrol.io/packages/AAAPackageDev) and converted using `z:AAAPackageDev: Convert (YAML, JSON, PList) to...`.

To modify the custom styling, open and edit `C++11.JSON-tmLanguage`. The custom styling is marked at the beginning of the `patterns`.

## Why does this exist?

I, the author ([gingerBill](https://github.com/gingerbill)), created it to aid my development in C and C++ and allow for quick and useful syntax highlighting. I use custom types and keywords that I wanted to have proper syntax highlighting.

The macro highlighting is not perfect but this is not a problem for me personally and these bugs can be _fixed_ by placing a semi-colon on a separate line below the macro.
