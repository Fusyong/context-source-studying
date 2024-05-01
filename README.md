仅供学习ConTeXt源码用，其中包含有ConTeXt源码（**请务必遵守源码版权协议**）以及我的修改

<!-- 
# 符号链接

MKLINK [[/D] | [/H] | [/J]] Link Target
        /D      创建目录符号链接。默认为文件符号链接。
        /H      创建硬链接而非符号链接。
        /J      创建目录联接。
        Link    指定新的符号链接名称。
        Target  指定新链接引用的路径(相对或绝对)。

## 安装字体相关命令

mtxrun --generate
mtxrun --script font --reload

查找你想要字体（包括文件名和符号名称），比如：

mtxrun --script fonts --list --all --pattern=*noto*cjk*light*

或列出四种特性：

>mtxrun --script fonts --list --spec deng-light

## tex\texmf-context\third\zhfonts\


```shell
mklink char-scr.lua D:\ah21\TEX\context-source-studying\source-reviewed\char-scr.lua
mklink scrp-cjk.lua D:\ah21\TEX\context-source-studying\source-reviewed\scrp-cjk.lua
mklink type-imp-mscore.mkiv D:\ah21\TEX\context-source-studying\source-reviewed\type-imp-mscore.mkiv

```

-->