### 如何安裝 Latex

在 Ubuntu 下安裝 Latex 方法

* `apt-get install texlive texlive-fonts-extra latex-cjk-all latexila jabref`

然後安裝字形, 大約需要下載 106 MB 的套件檔, 尤其是 ttf-arphic-bkai00mp 是 xelatex 特別需要的字型, 解決 Invalid fontname `文鼎ＰＬ中楷' 問題

* `apt-get install texlive-fonts-extra ttf-arphic-bkai00mp`

安裝好後，使用 latexila 編輯 tex 檔案, 然後按 「XeLatex  -> PDF」來產生 PDF
