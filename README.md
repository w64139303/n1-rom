# N1-ROM
本固件基于 lean源码、passwal源码和F大内核打包脚本制作，刷机和升级完全参考F大教程即可.

          第一次刷机（从U盘或TF卡启动之后）：
             cd  /root   &&   ./install-to-emmc.sh     或者：　/root/install-to-emmc.sh
          在线升级，先把 update-amlogic-openwrt.sh 以及镜像文件 xxxxxxxxxxxxxxxxxxxxxxxxx.img用winscp工具上传至/mnt/mmcblk2p4, 然后：
　　　cd  /mnt/mmcblk2p4
         chmod 755 update-amlogic-openwrt.sh
         ./update-amlogic-openwrt.sh  xxxxxxxxxxxxxxxxxxxxxxxxxx.img
         注意：update-amlogic-openwrt.sh一般随固件同时发布，在.7z包里面，每次升级最好都用最新版的update脚本

F大教程地址
https://www.right.com.cn/forum/thread-4076037-1-1.html
