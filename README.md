# vim-github-link-opener

Ever seen something like this?

    gem "github/linguist"

Or this?

    Check out gabebw/dotfiles for more.

Or what about this (in Go files):

    import (
      "github.com/spf13/cobra"
      "github.com/stretchr/testify/assert"
    )

Wouldn't it be cool if you could quickly open
<https://github.com/github/linguist>,
<https://github.com/gabebw/dotfiles>,
<https://github.com/spf13/cobra>,
or <https://github.com/stretchr/testify>?

This plugin lets you do exactly that!

It's exactly like visiting other URLs in vim: type `gx` when your cursor is
anywhere in the string, and this plugin will open the GitHub project in your
browser.

It won't change how `gx` treats other URLs. They'll still work. And if you use
@christoomey's excellent
[vim-quicklink](https://github.com/christoomey/vim-quicklink), that will keep
working too.

## Installation

With [vim-plug](https://github.com/junegunn/vim-plug):

    Plug 'gabebw/vim-github-link-opener'

Then run `:PlugInstall`.
