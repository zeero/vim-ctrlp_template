# vim-ctrlp_template
CtrlP Extension for template.

## Install
Install with package manager.

[dein.vim](https://github.com/Shougo/dein.vim):
```dein.toml
[[plugin]]
repo = 'zeero/vim-ctrlp_template'
lazy = 1
on_cmd = ['CtrlPTemplate']
depends = ['ctrlp.vim']
```

## Usage
```
:CtrlPTemplate
```

If may add keymap into your vimrc like below:
```
nnoremap <leader>t :<C-u>CtrlPTemplate<CR>
```

