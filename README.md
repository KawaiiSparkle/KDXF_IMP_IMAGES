# 介绍

此仓库用来存放科大讯飞学习机展讯机型（无论课堂版还是零售版）利用下载模式或者CVE提取出除system,vendor以外的重要分区

为的是方便用户自行对平板进行维修（救砖）

欢迎各位玩机佬的Pull Request

侵权请开issue联系我(删除|下架)本(项目|部分文件)

# 文件命名方式

ToB:课堂/校园版

ToC:零售版

`{ToB|ToC}_机型名称_{平台代号|无}.zip`

# 文件制作方式

全选你要上传的分区镜像,右键`发送到-压缩(Zipped)文件夹`得到zip文件,并按照"文件命名方式"所述格式进行重命名


# 使用方式

* 拿去救砖（注：可能需要先签名一遍才能刷进去，当然你改分区名称强刷也行，但一定刷完得改回来）
* 拿去root机器
    * fork [Tomking062大佬的这个项目](https://github.com/TomKing062/action_big_resign_with_magisk)到自己Github账号下,进入你fork后的项目,Actions->resign_v3->Run Workflow,URL填`https://github.com/KawaiiSparkle/KDXF_IMP_IMAGES/raw/refs/heads/main/`<文件名.zip> 并Run Workflow即可,然后能在Releases中找到修补产物`resign.zip`打开取boot分区刷入即可
* 拿原版REC生成TWRP设备树，然后编译一个自己的TWRP

# 计划收集的机型

* 所有有条件能收集到的展讯KDXF机型
