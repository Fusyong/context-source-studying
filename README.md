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

亲爱的汉斯，
我已经已经检查并修改了char-scr.lua和scrp-cjk.lua。我改动的地方有些多，尽管我尽可能谨慎行事，也编写了一些用例来观察跟踪信息和最终的PDF、查看结点列表中注入的结点，但肯定还有我意想不到的的问题：新的错误；对韩语和日语部分的可能影响（我略微调整了前面共用的函数）；对系统内核行为的干扰（我增加了拉丁字符集合数字字符集），等等。所以我有些犹豫，不知道怎样才是最合适的提交方式，以便减少你的麻烦。

我处理中文标点时，遵照的是 *General Rules for Punctuation* (GB/T 1583—2011), the standard applicable to The People's Republic of China.

all to simsun.ttc the main font for Simplified Chinese in Win10 (not to mingliu.ttc that just for raditional Chinese)

simsun.ttc
simsunb.ttf
simfang.ttf
simhei.ttf
simkai.ttf
mingliub.ttc
