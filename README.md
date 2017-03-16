# rofi-lpass

Custom script for Rofi that allows you to copy passwords from your Lastpass vault.

## Features

* List all your entries
* Copy password of an entry
* Copy username / email of an entry
* Copy URL (if entry has an URL)
* Open URL (if entry has an URL)

## Installation

1. Make sure you have [lastpass-cli](https://github.com/lastpass/lastpass-cli) installed, with `lpass` on your `PATH`.
2. Symlink the script to somewhere on your `$PATH`: `ln -s $(pwd)/rofi-lpass ~/bin/rofi-lpass`.
3. Run rofi with this as a custom script: `rofi -modi lpass:rofi-lpass -show lpass`

## License

Copyright © 2017 Magnus Bergmark. Code released under the MIT license.
