# 目的
使用 Cocos2dx-3.15.1 建立 Html5 開發專案

# 前置環境
已安裝python

# 步驟
下載 cocos2dx-3.15.1 資料包 （https://github.com/cocos2d/cocos2d-x/tree/cocos2d-x-3.15.1）

資料包解壓縮後, 進入cocos2d-x-3.15.1:
cd cocos2d-x-3.15.1

在該目錄下, 執行:
python setup.py

執行過程中可以跳過NDK, ANT等設定

完成後, 再執行:(讓系統環境認得cocos指令)
source ~/.bash_profile

# 建立專案
在任意資料夾目錄執行:(注意最後的點 表示在當前目錄創建專案)
cocos new helloJS -l js -d .

進入 helloJS, 其目錄下的 index.html 以firefox開啟可本地測試

clone 本專案 helloJS/index.html 亦可用firefox進行本地測試
