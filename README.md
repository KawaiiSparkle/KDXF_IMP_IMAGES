# 介绍

此仓库用来存放科大讯飞学习机展讯机型（无论课堂版还是零售版）利用下载模式提取出的几个未修改的重要分区：recovery,boot,uboot,sml,trustos,splloader

为的是方便用户自行维修（救砖）或者造CVE方法一键解bl的包

欢迎各位玩机佬的Pull Request

侵权请开issue联系我删除/下架本项目

# 使用方式

* 拿去造CVE方法一键解bl的包（照tomking的CVE教程改完后可能还需要签名，方法看它[这个项目](https://github.com/TomKing062/vendor_sprd_proprietories-source_packimage)）
* 拿去救砖（注：可能需要先签名一遍才能刷进去，当然你改分区名称强刷也行，但一定刷完得改回来）
* 拿去root机器（使用resign项目修补boot以及签名）

# 计划收集的机型

* 零售版：T10，T20，X2Pro，X3Pro，T30lite，C/S系列零售版（这个等有fdl支持再说）
* 课堂版：C6系列，C8系列
