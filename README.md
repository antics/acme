# Acme 💜 Emacs
Acme with Emacs keys for navigation and win/mac keys for undo/cut/copy/paste.

| Key     | Action |
| --------|:------:|
| C-b     | left |
| C-f     | right |
| C-p     | up |
| C-n     | down |
| C-a     | start of line |
| C-e     | end of line |
| C-w     | cut word |
| C-u     | cut line |
| C-y     | paste |
| C-v     | paste |
| C-x     | cut |
| C-c     | copy |
| C-z     | undo |
| C-l     | tab completion |

## Dependencies
You need to install [https://github.com/9fans/plan9port](plan9port) to compile and run the code.

## Installation
```
9 mk
cp o.acme /usr/local/plan9/bin/acme
```
## TODO
- C-k to kill line.
- C-q to Exit Acme or maybe Del window.
