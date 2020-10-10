# Learning Vim

From my personal experience of learning Vim, it is actually difficult to 
really learn Vim by reading the documentation or watching other people’s 
operations. You must In the application, only by entering the real scene can 
you gradually become familiar with and master the relevant commands.

Therefore, in order to meet the needs of learning and operation at the same 
time, the files in the project are all in Markdown format, which can be used 
as documentation for reading, you can also use Vim to open the file for actual 
operation (the latter is recommended).

## How To Use

1. Open your Terminal
2. Clone this project to local
  > `git clone git@github.com:dofy/learn-vim.git`
3. Change directory to `learn-vim`
  > `cd learn-vim`
4. Open `file-one.md` by Vim
  > `vim file-one.md`

## Typographic Instructions

```Markdown
## High level heading

### Next level heading

The text without any format is the description content and is only for reading.

> The text embedded in the quote block is the operation instruction, you can 
> follow the content mentioned in it to operate
>
> And, Operators or Commands will be contained in symbols like `:w`

The `<` and `>` in the form of `f<X>` in the command do not need to be typed 
out. `<X>` represents a variable, that is, you can type `fa`, `fb` or `fC`

_Note: Commands are case sensitive (the items that need attention will appear in symbols like the current line)_
```

## Navigation

### Basic Operation

1. [Move The Cursor](file-one.md)
1. [Open File, Find Content](file-two.md)
1. [Modify and Save Documents](file-three.md)
1. [Some Tips](file-four.md)
1. [Split Screen and Tabs](file-five.md)
1. [Block Operation](file-six.md)
1. [Macros in Vim](file-seven.md)

### Appendix

1. [Vim Plugins](plugin.md)
1. [Recommended Plugins](plugins/index.md)
    1. [NERDTree](plugins/nerdtree.md)
    1. [EasyAlign](plugins/easyalign.md)
    1. [Airline & Themes](plugins/airline.md)
    1. [surround.vim](plugins/surround.md)

## Tips

- There will be navigation to the next chapter or related chapters in the 
tutorial, locate the file name and execute `gf` (goto file) to open the 
related file
- You can open the relevant chapters to view at any time, and then use `:bp` 
to return to the previous file (this command will be discussed in 
[Chapter 2](file-two.md))
- When you exit the tutorial with `:q` or `:qa`, you may receive a warning 
that the file is not saved, try adding `!` after the command

## TODO

- [ ] vimdiff
- [ ] more settings
- [ ] other mode
- [ ] text object
- [x] [plugins](plugin.md)

## Recommended Vim Configuration Scheme

  - [dofy / **7th-vim**][7th-vim]
  - [kepbod / **ivim**][kepbod]
  - [chxuan / **vimplus**][chxuan]
  - [SpaceVim / **SpaceVim**][spacevim]

## Other Vim Tutorials

- Run `vimtutor` on the console. This is the official Vim tutorial.
- [Concise Vim Leveling Guide][coolshell] Very good introductory tutorial.
- [Vim Galore][vimgalore] Frequent updates, must read for advanced Vim.
- [Vim everyday][liuzhijun] A total of 30 articles, relatively complete.
- [Vim Tutorial][vimjc] A Vim Chinese tutorial website maintained by a girl, 
continuously updated.
- [A book for learning the Vim editor][learnvim] Another Learn Vim (English).

## Cheatsheets

> [https://vim.rtorr.com][cheatsheets1]

> [![002][cheatsheets2]][cheatsheets2]

> [![003][cheatsheets3]][cheatsheets3]

> [![004][cheatsheets4]][cheatsheets4]

**再次感谢您的关注！如果爱，请分享。爱生活，爱 VIM！**

[7th-vim]: https://github.com/dofy/7th-vim
[kepbod]: https://github.com/kepbod/ivim
[chxuan]: https://github.com/chxuan/vimplus
[spacevim]: https://github.com/SpaceVim/SpaceVim
[coolshell]: http://coolshell.cn/articles/5426.html
[vimgalore]: https://github.com/mhinz/vim-galore
[liuzhijun]: https://liuzhijun.iteye.com/category/270228
[vimjc]: https://vimjc.com
[learnvim]: https://github.com/iggredible/Learn-Vim
[cheatsheets1]: https://vim.rtorr.com/lang/zh_tw
[cheatsheets2]: http://people.csail.mit.edu/vgod/vim/vim-cheat-sheet-en.png
[cheatsheets3]: https://cdn.shopify.com/s/files/1/0165/4168/files/preview.png
[cheatsheets4]: http://michael.peopleofhonoronly.com/vim/vim_cheat_sheet_for_programmers_screen.png
