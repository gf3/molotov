# Molotov colour scheme
Molotov is a vim colour scheme that gets out of your way and lets you focus on what's at hand. It has additional colouring info for many languages and plugins.

Molotov works best with 256 colors or a True Color terminal and is supported in vim, neovim, GVim, MacVim, et al.

## Installation
### Using [vim-plug](https://github.com/junegunn/vim-plug)
``` vim
Plug 'gf3/molotov'
```

### Manually
Copy [molotov.vim](colors/molotov.vim) to the `colors` directory in your vim configuration directory.

### Setup
You’ll want to use a similar config to effectively use Molotov:

``` vim
" Set 256 colours, dark background, and molotov
set t_Co=256
set background=dark
colorscheme molotov

" If using airline.vim:
let g:airline_theme='molotov'
```

### Terminal colours
Grab Molotov for your terminal as well!

- [Molotov for iTerm2]
- [Molotov for Terminal]
- [Molotov for Alacritty]

## Screenshots

### Javascript
![Terminal Vim Screenshot for JavaScript](https://butt.zone/molotov/molotov-javascript.png)

### Typescript
![Terminal Vim Screenshot for TypeScript](https://butt.zone/molotov/molotov-typescript.png)

### CSS
![Terminal Vim Screenshot for CSS](https://butt.zone/molotov/molotov-css.png)

### Ruby
![Terminal Vim Screenshot for Ruby](https://butt.zone/molotov/molotov-ruby.png)

### C
![Terminal Vim Screenshot for C](https://butt.zone/molotov/molotov-c.png)

## Modes
|     | Unmodified | Modified |
| --- | --- | --- |
| Normal | ![](https://butt.zone/molotov/molotov-normal.png) | ![](https://butt.zone/molotov/molotov-normal-modified.png) |
| Insert | ![](https://butt.zone/molotov/molotov-insert.png) | ![](https://butt.zone/molotov/molotov-insert-modified.png) |
| Visual | ![](https://butt.zone/molotov/molotov-visual.png) | ![](https://butt.zone/molotov/molotov-visual-modified.png) |
| Replace | ![](https://butt.zone/molotov/molotov-replace.png) | ![](https://butt.zone/molotov/molotov-replace-modified.png) |

[Molotov for iTerm2]: https://raw.githubusercontent.com/gf3/dotfiles/master/Molotov.itermcolors
[Molotov for Terminal]: https://raw.githubusercontent.com/gf3/dotfiles/master/Molotov.terminal
[Molotov for Alacritty]: https://raw.githubusercontent.com/gf3/dotfiles/master/.alacritty.yml
