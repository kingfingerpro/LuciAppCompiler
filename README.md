# OpenWrt SDK #

> 使用 Git Action 工作流自动编译指定的软件包

使用方法 :

1. 在开始前 , 可以编辑 addfeedsrc.sh 添加自定义 feeds 源
2. 编辑仓库中的 apps.txt , 以每行一个的格式保存 ( 至少需要一个以确保 workflow 能够正常运行 )
3. Action --> Compile IPK --> Run workflow
4. 默认是 21.02.03 SDK , 可以修改 workflow 文件中的 SDK_DLINK 的值 , 以达到更换 SDK 的目的
