建立自己的LINUX LIVE ISO [GOOGLE: create custom linux live iso]

資料來源: https://helpdeskgeek.com/linux-tips/make-a-custom-live-linux-distro-with-linux-live-kit/
https://github.com/Tomas-M/linux-live

00.預備動作
sudo apt-get update && sudo apt-get install squashfs-tools

01.下載https://github.com/Tomas-M/linux-live 到 /tmp

02.解壓縮linux-live

03.切換目錄
cd /tmp/linux-live

04.執行建立ISO工作
sudo ./build
cd ..
ls -l
sudo ./gen_linux_iso.sh


PS.拿自己的 『建立統包 LINUX TOOLS VM』 實驗成功

