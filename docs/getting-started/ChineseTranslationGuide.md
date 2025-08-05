---
title: PDPS 汉化指南与语言切换教程
date: 2025-08-05
description: "提供详细的图文步骤，指导用户如何为 Tecnomatix Process Simulate (PDPS) 安装中文语言包，以及如何在不同语言界面之间进行自由切换。"
---

# PDPS 汉化指南与语言切换教程

本指南将带你完成 Tecnomatix Process Simulate (PDPS) 的中文化设置，并介绍如何在不同语言环境之间轻松切换。

## 一、首次安装 PDPS 汉化包

如果你是首次安装，或者安装时未选择中文语言包，请遵循以下步骤。

### Step 1：解压并安装中文语言包

在 PDPS 的主安装包中，我们可以找到独立的中文语言包。

=== "第一步：搜索语言包"

    1.  首先，完全解压你的 PDPS 安装包。
    2.  在解压后的文件夹中，使用搜索功能，关键词为 `Chinese`。
    3.  找到名为 `Tecnomatix localization 2502(版本号) Chinese.msi` 或类似的 `.msi` 安装程序。

    ![在安装包中搜索 Chinese](/assets/pdps-localization/step1-language-install.webp){loading=lazy}
    *<p align="center">定位中文语言支持安装文件</p>*

=== "第二步：运行安装程序"

    双击运行该 `.msi` 安装程序，启动安装向导。

    ![运行中文语言安装向导](/assets/pdps-localization/step2-chinese-ui.webp){loading=lazy}
    *<p align="center">开始安装中文界面支持</p>*

=== "第三步：完成安装"

    按照向导提示，依次点击“下一步”，接受协议并完成安装。

    ![安装过程截图](/assets/pdps-localization/step2-chinese-ui-install.webp){loading=lazy}
    *<p align="center">安装向导进行中</p>*

    ![安装成功提示](/assets/pdps-localization/step2-chinese-ui-installSucced.webp){loading=lazy}
    *<p align="center">语言包安装成功</p>*

### Step 2：验证汉化效果

完成安装后，双击桌面上的 Process Simulate 图标启动软件。如果界面显示为中文，则说明汉化成功。

![PDPS 中文界面展示](/assets/pdps-localization/step5-language-success-pdps.webp){loading=lazy}
*<p align="center">成功汉化后的 PDPS 主界面</p>*


## 二、在不同语言间切换

如果你的软件已安装多种语言，可以使用 **Tecnomatix Doctor** 工具进行快速切换。

### Step 1：启动 Tecnomatix Doctor

在 Windows 的“开始”菜单中，找到 `Tecnomatix` 文件夹，并点击打开 **Tecnomatix Doctor** 应用程序。

![在开始菜单中找到 Tecnomatix Doctor](/assets/pdps-localization/step3-open-doctor.webp){loading=lazy}
*<p align="center">启动语言切换工具</p>*

### Step 2：选择切换语言功能

=== "第一步：打开工具菜单"

    在 Tecnomatix Doctor 的顶部菜单栏中，点击 `Tool`（工具）下拉菜单。

    ![点击工具菜单](/assets/pdps-localization/step4-change-language.webp){loading=lazy}

=== "第二步：选择更改语言"

    在下拉菜单中，选择 `Change Language`（更改语言）选项。

    ![选择更改语言选项](/assets/pdps-localization/step4-change-language-selected.webp){loading=lazy}
    *<p align="center">选择目标语言</p>*
    
    ![安装成功提示](/assets/pdps-localization/step4-change-language-succed.webp){loading=lazy}
    *<p align="center">切换语言的弹窗</p>*

### Step 3：选择目标语言并确认

在弹出的窗口中，选择你希望切换到的目标语言（例如 `English`），然后点击 `OK` 按钮。系统会弹出成功提示。

![在弹窗中选择语言并确认](/assets/pdps-localization/step5-language-success.webp){loading=lazy}
*<p align="center">确认切换后的成功提示</p>*

!!! tip "小提示"
    语言切换成功后，需要**重新启动 Process Simulate** 软件，新的语言界面才会生效。如果仍未生效，尝试重启电脑。