ubuntu
======

Ubuntu 大小事

### Ubuntu 的rar 壓縮檔內容亂碼問題

* 解除安裝 rar , 使用 p7zip-full, p7zip-rar
    * apt-get remove rar unrar
* Ubuntu裡如何用指令查詢已安裝套件
    * dpkg --get-selections | grep xxx
