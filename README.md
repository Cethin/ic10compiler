# IC10 Minifier README

## Features

Minifies IC10 code for the game Stationeers to save space. Replaces defines, aliases, and labels, pre-calculates hashes, removes blank lines, whitespace, and comments. This allows you to write more readable code without worrying about sacrificing space.

![MinifiedExample](https://github.com/user-attachments/assets/2588b61b-7409-4f9f-a708-5b8abef91b76)

## How to use

Install the IC10-Minifier extension for VSCode: https://marketplace.visualstudio.com/items?itemName=LukeSmith.ic10-minifier

Press "ctrl+P" and run "Minify IC10" on your file.

This will create a new file in the same directory with the prefixed "minified_" with the minified IC10 program.

## Known issues

* Relative branching with a line that's removed (empty line, comment, label, etc.) between it and it's destination will not be correctly changed.
