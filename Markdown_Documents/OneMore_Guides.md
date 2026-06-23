---
layout: default
title: OneMore 快捷键和功能
---
<!-- markdownlint-disable MD025 MD033 MD060 -->
# OneMore 快捷键和功能

- 作为完全免费且开源的 OneNote 神级插件，**OneMore** 的定位不仅仅是 Markdown 转换，它更像是一个旨在补齐 OneNote 原生短板的“全功能效率工具箱”。

- [返回首页](../README.md)
- [1. Markdown 与文本处理](#1-markdown-与文本处理)
- [2. 核心效率全局导航](#2-核心效率全局导航)
- [3. 代码块与页面元素增强](#3-代码块与页面元素增强)
- [4. 自定义样式 (My Styles)](#4-自定义样式-my-styles)
- [5. 表格高级扩展 (Tables)](#5-表格高级扩展-tables)
- [6. 标签系统与高级搜索 (Tagging)](#6-标签系统与高级搜索-tagging)
- [7. 脚注与附加工具](#7-脚注与附加工具)
- [8. 高效小贴士](#8-高效小贴士)

## 1. Markdown 与文本处理

> 这组功能彻底解决了 OneNote 原生不支持 Markdown 以及纯文本处理能力弱的问题。

- **转换 Markdown (Convert Markdown)** `Alt + Shift + M`：将当前页面上的 Markdown 源码直接渲染为 OneNote 富文本。
- **预览 Markdown (Preview Markdown)** `Ctrl + Alt + Shift + M`：弹窗预览当前 Markdown 文本的最终渲染效果。
- **清理所有格式 (Clear Formatting)** `Ctrl + Shift + N`：彻底清除选中文字的混乱格式，恢复为 Normal 样式。
- **转换为大写 (To Uppercase)** `Ctrl + Alt + Shift + U`
- **转换为小写 (To Lowercase)** `Ctrl + Shift + U`
- **粘贴为纯文本 (Paste as Plain Text)** `Ctrl + Shift + V`：直接过滤掉剪贴板中自带的网页或代码格式。
- **粘贴富文本 (Paste Rich Text)** `Ctrl + Alt + V`
- **复制/重现上一个命令 (Replay Last Command)** `Alt + Shift + R`：一键重复你刚才执行的文本操作。

## 2. 核心效率全局导航

- **万能命令面板 (Command Palette)** `Ctrl + Shift + P`：类似 VS Code 的命令面板。按下后弹窗，输入任何功能名称（如 "Sort" 或 "Markdown"）即可直接执行，无需去菜单栏寻找。
- **快速查找面板 (Quick Palette)** `Ctrl + ,`（Ctrl + 逗号）：快速检索。
- **收藏夹弹窗 (Favorites)** `Alt + F`：一键呼出你收藏的页面或分区，快速跳转。
- **显示导航窗口 (Navigator Window)** `Alt + Shift + N`：在右侧生成一个大纲树状图，类似 Word 的导航窗格，点击标题直接跳转。
- **加入阅读清单 (Add to Reading List)** `Ctrl + Shift + B`：将当前页面打上标签，加入稍后阅读。

## 3. 代码块与页面元素增强

> OneNote 原生没有真正意义上的代码块，OneMore 提供了完美的解决方案：

- **插入代码块 (Insert Code Block)** `F6`：插入一个带有独立背景色、边框、并支持**超过 100 种编程语言语法高亮**的高级代码框。
- **代码着色 (Colorize)** `Alt + C`：为选中的纯文本代码重新进行语法高亮染色。
- **插入水平分割线 (Horizontal Line)** `Alt + Shift + F11`
- **插入双水平分割线 (Double Line)** `Alt + Shift + F12`
- **插入文本框 (Insert Text Box)** `Alt + F6`
- **插入表情符号 (Insert Emoji)** `Alt + F12`
- **插入可排序日期 (Sortable Date)** `Ctrl + Shift + D`：插入诸如 `2026-05-20` 格式的标准化日期，方便后续排序。
- **插入日期与时间** `Ctrl + Alt + Shift + D`

## 4. 自定义样式 (My Styles)

> 弥补了 OneNote 无法像 Word 那样自定义全局样式的遗憾。你可以自己设计 H1 到 H9 的字体、颜色、行间距，然后用快捷键一键套用：

- **套用自定义样式 1 ~ 9**：`Ctrl + Alt + Shift + 1` 直至 `Ctrl + Alt + Shift + 9`

## 5. 表格高级扩展 (Tables)

> 让 OneNote 的表格具备类似 Excel 的部分计算与快速操作能力：

- **添加/编写公式 (Add Formula)** `F5`：在表格单元格中写入类似 `=SUM(A1:A5)` 的 Excel 表达式。
- **重新计算公式 (Recalculate)** `Shift + F5`：手动刷新表格中的公式计算结果。
- **向下填充 (Fill Down)** `Ctrl + D`：类似 Excel，向下复制单元格内容或递增数据。

## 6. 标签系统与高级搜索 (Tagging)

- **插入 Hashtag 标签** `Alt + T`：在文本中快速插入类似 `#工作`、`#灵感` 这样的推特风格标签。
- **搜索指定 Hashtag** `Ctrl + Alt + T`
- **扫描本页所有标签** `Ctrl + Alt + F10`
- **全局搜索与替换 (Search and Replace)** `Ctrl + H`：补齐了 OneNote 极难使用的原生替换功能。
- **高级搜索 (Search)** `Alt + Shift + G`

## 7. 脚注与附加工具

- **添加学术脚注 (Add Footnote)** `Ctrl + Alt + F`：在文末自动生成标准的学术/学术论文引用脚注。
- **移除脚注 (Remove Footnote)** `Ctrl + Shift + F`
- **隐藏/显示笔记容器边框** `Alt + B`：一键切断或显示 OneNote 特有的“文本框”外框虚线，让排版更干净。
- **查看底层 XML 源码** `Ctrl + Alt + Shift + X`：高级开发人员调试页面元素使用。

## 8. 高效小贴士

- 以上所有快捷键都可以在 OneMore 的 **Settings (设置)** 面板中自行更改，如果遇到与系统其他软件冲突的键位，随时可以重新绑定。
- 如果记不住这么多快捷键，只需牢记 **`Ctrl + Shift + P`**。这个命令面板支持拼写模糊搜索，能帮你调用上述所有功能。
