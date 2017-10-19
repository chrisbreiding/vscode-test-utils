# VSCode Test Utils

Test utilities extension for [VSCode](https://code.visualstudio.com/. Currently supports easily adding and removing `.only` and `.skip` modifiers with keyboard shortcuts or the command palette.

## Available Commands

| Shortcut | Action | Mnemonic |
| -------- | ------ | -------- |
| `ctrl-alt-a ctrl-alt-o` | Add a `.only` to the current line if there's a `describe`, `context`, or `it` | `a`dd `o`nly |
| `ctrl-alt-r ctrl-alt-o` | Remove the `.only` from the current line | `r`emove `o`nly |
| `ctrl-alt-x ctrl-alt-o` | Remove all `.only`s from the current file | e`x`terminate `o`nlys |
| `ctrl-alt-m ctrl-alt-o` | Remove all `.only`s from the current file and add a `.only` to the current line if there's a `describe`, `context`, or `it` | `m`ove `o`nly |
| `ctrl-alt-a ctrl-alt-s` | Add a `.skip` to the current line if there's a `describe`, `context`, or `it` | `a`dd `s`kip |
| `ctrl-alt-r ctrl-alt-s` | Remove the `.skip` from the current line | `r`emove `s`kip |
| `ctrl-alt-x ctrl-alt-s` | Remove all `.skip`s from the current file | e`x`terminate `s`kips |

## About

The cursor can be anywhere on the line for the `add` and `move` commands. The shortcuts are meant to be used hold `alt` and `ctrl`, then pressing the letters in succession. So `ctrl-alt-a ctrl-alt-o` means holding `alt` + `ctrl`, pressing `a`, then pressing `o`.
