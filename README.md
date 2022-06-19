# CN-Tables

整理中国大陆简中、中国台湾繁中的国标汉字表。

## 协作整理

由于疏忽、参考资料有误等，码表可能会存在一些错误，如果你发现了错误请通过
[Issues] 或者 [PR] 反馈给我。

+ 如果不会 Git 操作可在 [Issues] 中发起反馈。
+ 如果熟悉 Git 操作可在更正错误后发起 [PR]。

[Issues]: https://github.com/kitty-panics/cn-tables/issues
[PR]: https://github.com/kitty-panics/cn-tables/pulls

## 数据格式

每个文件一行一字，以 Tab (制表符) 进行分割，例：

```Text
U+4E00	一
U+4E59	乙
U+4E8C	二
U+5341	十
```

## 文件列表

+ [《通用规范汉字表》]
    + 收录汉字 8105 个。
+ [《常用国字标准字体表（甲表）》]
    + 收录汉字 4808 个。
+ [《次常用国字标准字体表（乙表）》]
    + 收录汉字 6341 个。

**注：**

1. [甲表] 和 [乙表] 中都有收录 `兀` 字
2. [乙表] 中 `嗀`、`斔` 字重复收录了一次

[《通用规范汉字表》]: 通用规范汉字表.txt
[《常用国字标准字体表（甲表）》]: 常用国字标准字体表（甲表）.txt
[《次常用国字标准字体表（乙表）》]: 次常用国字标准字体表（乙表）.txt
[甲表]: 常用国字标准字体表（甲表）.txt
[乙表]: 次常用国字标准字体表（乙表）.txt

## 参考资料

参考资料可在 [参考资料] 目录下找到。其中非文件类的在线资料将转换成 PDF 快照存放。

+ [cjkvi/cjkvi-tables]

[参考资料]: 参考资料
[cjkvi/cjkvi-tables]: https://github.com/cjkvi/cjkvi-tables

## 相关项目

### [cn-tables]

整理中国大陆简中、中国台湾繁中的国标汉字表。

[cn-tables]: https://github.com/kitty-panics/cn-tables

### [unicode-cjk]

整理所有 [Unicode CJK] 字符。

[unicode-cjk]: https://github.com/kitty-panics/unicode-cjk
[Unicode CJK]: https://www.unicode.org/Public/UCD/latest/ucd/Blocks.txt

### [unicode-cjk-98wubi]

整理 Unicode CJK 字符的 [五笔98] 编码。

[unicode-cjk-98wubi]: https://github.com/kitty-panics/unicode-cjk-98wubi
[五笔98]: http://98wb.ysepan.com

### [unicode-cjk-cangjie5]

整理 Unicode CJK 字符的 [仓颉5] 编码。

[unicode-cjk-cangjie5]: https://github.com/kitty-panics/unicode-cjk-cangjie5
[仓颉5]: https://github.com/Jackchows/Cangjie5

### [unicode-cjk-cns11643-cangjie]

[Unicode]、[CNS11643]、Cangjie 对照表。

[unicode-cjk-cns11643-cangjie]: https://github.com/kitty-panics/unicode-cjk-cns11643-cangjie
[Unicode]: https://www.unicode.org/Public/UCD/latest
[CNS11643]: https://data.gov.tw/dataset/5961

### [unicode-cjk-ids]

备份、修补 [chise/ids]。

[unicode-cjk-ids]: https://github.com/kitty-panics/unicode-cjk-ids
[chise/ids]: https://gitlab.chise.org/CHISE/ids.git

### [unicode-cjk-zhlf]

整理 Unicode CJK 字符的 [字海两分] 编码。

[unicode-cjk-zhlf]: https://github.com/kitty-panics/unicode-cjk-zhlf
[字海两分]: http://cheonhyeong.com/Simplified/download.html

### [unicode-cjk-zhlf-sc]

整理 Unicode CJK 字符的 [字海两分速成] 编码。

[unicode-cjk-zhlf-sc]: https://github.com/kitty-panics/unicode-cjk-zhlf-sc
[字海两分速成]: http://cheonhyeong.com/Simplified/download.html
