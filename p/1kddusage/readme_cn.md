

1keydd使用
-------

onekeydevdesk自助安装FAQ:

> 最低要求1h512m，推荐4h8g，小内存安装后会使用swap。    
> 如何扩大数据区：默认20G，可以执行/run/initramfs/usr/bin/growpart /dev/vda 2 && resize2fs /dev/vda2扩展此空间到整个剩余可余空间。  
> 如何清除数据：挂载vda2，清除onekeydevdeskd/changes中的内容，重启即可。  
> 如何以硬盘方式启动：重启编辑grub条目，去掉perch，解包01-core.ldeb到硬盘上的某rootcopy文件夹内。   
> 更多请自行探索。。。  