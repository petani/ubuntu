### vim 真好用

[VIM Color Scheme Test - HTML][scheme]
[scheme]: http://vimcolorschemetest.googlecode.com/svn/html/index-html.html

起手式, 設定 .vimrc

<pre><code>
syntax on
set expandtab
set shiftwidth=4
set softtabstop=4
set tabstop=4
set number
set cindent
"set autoindent
set paste
set fileencodings=utf-8
set cursorline
colorscheme torte
" 搜尋到的字加 hilight
set hlsearch
" 將註解由深藍色變綠色
highlight Search term=reverse ctermbg=4 ctermfg=7
" 將註解的資料由深藍色變淺藍色
highlight Comment ctermfg=darkcyan
" 將註解由深藍色變綠色
" hi Comment ctermfg=Green
</code></pre>

參考文件

* [給程式設計師的Vim入門圖解說明][vim figure]

[vim figure]: http://blog.vgod.tw/2009/12/08/vim-cheat-sheet-for-programmers/

vim tab 功能

* vim a.md b.md c.md
* :tab all
* 切換 tab 
    * gt
* 跳到某個 tab
    * 數字gt
    * 例如跳到第1個tab, 1gt

vim 退出所有檔案
* :qa

vi tips

* ctrl+v (mark)
* press > 可以向右移動
* press < 可以向左移動

固定位置新增一個空格

* ctrl+v (mark)
* 200j  (輸入 200 然後按「下」鍵也可以
* I space
* ESC

進階指令

* 移動游標
    * zt 到頂部 
    * zz
    * zb
* 

vim  a b -O                                                                                                               
vim  a b -d
vimdiff a b

colorscheme torte
 
:help
ctrl+wo 放大螢幕
:only 放大螢幕
