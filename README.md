# Neonwolf Colorscheme for Git

This is a high-contrast, dark colorscheme for git that was inspired by the badwolf series of color schemes.

![sample](/../flair/screenshots/status.png)

## Installation

Include it as part of your `~/.gitconfig` file.

    $ mkdir -p ~/.gitfiles
    $ cp git-colors-neonwolf-256.gitconfig ~/.gitfiles
    $ git config --global include.path .gitfiles/git-colors-neonwolf-256.gitconfig

Or if you're particularly lazy:

    $ cat git-colors-neonwolf-256.gitconfig >>~/.gitconfig

This file only defines the colors, you need to turn them on yourself. If colors
do not show up, you may need to turn them on in your gitconfig:

    $ git config --global color.branch auto
    $ git config --global color.diff auto
    $ git config --global color.interactive auto
    $ git config --global color.ui auto
    $ git config --global color.pager true

## Contributing

Send me a pull request!

## TODO

Develop a low-color variant.

## License

Copyright (C) 2015 Dan Church.

License: MIT

This is free software: you are free to change and redistribute it.

There is NO WARRANTY, to the extent permitted by law.
