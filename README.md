
<div align='center'>
    <font size='7'><b>ak37e_lvgl8</b></font>
</div>
<center><b>--AK37E 嵌入式平台移植 LVGL 8.2 图形开发框架</b></center>

# 项目介绍
这是一个 **安凯37E系列开发平台** 移植 **LVGL v8.2** 的工程项目，可作为模板工程，用于开发者快速上手在 **AK37E** 平台上开发图形界面。

# 编译环境准备
编译该项目建议在以下环境：

- Ubuntu 16 操作系统
- cmake、make 已安装
- 交叉编译环境已配置（购买 AK37E 开发板后，向官方索要开发文档，里有流程）

运行 run.sh 脚本会在 build 目录下生成目标程序。

# 项目配置
不同 **AK37E** 平台在外设配置上会有差异，该节主要介绍对 LVGL 的 显示驱动 和 触摸驱动 进行定制化配置。

### 显示驱动配置
首先对显示驱动进行配置