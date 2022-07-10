# CN-Tables

整理中国各地区 (大陆、香港、台湾) 汉字标准。

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

+ 大陆
    - [《通用规范汉字表》] (2013 年)
        - 收录汉字 8,105 个。
    - [《通用规范汉字表-字频》]
        - 依照 [邢红兵教授] 发布的 [25 亿字语料汉字字频表] 进行排序
          (最后 445 个汉字在字频表中没有，依照 [《通用规范汉字表》] 顺序排序)。
+ 香港
    - [《常用字字形表》] (2000 年，修订本)
        - 收录汉字 4,759 个。
    - [《常用字字形表-合并》]
        - 将相同序号的汉字合并到一行。
+ 台湾
    - [《国字标准字体表-常用(甲表)》] (1982 年)
        - 收录汉字 4,808 个。
    - [《国字标准字体表-次常用(乙表)》] (1993 年)
        - 收录汉字 6,343 个。

[《通用规范汉字表》]: 通用规范汉字表.txt
[《通用规范汉字表-字频》]: 通用规范汉字表-字频.txt
[邢红兵教授]: https://faculty.blcu.edu.cn/xinghb/zh_CN/index.htm
[25 亿字语料汉字字频表]: https://faculty.blcu.edu.cn/xinghb/zh_CN/article/167473/content/1437.htm

[《常用字字形表》]: 常用字字形表.txt
[《常用字字形表-合并》]: 常用字字形表-合并.txt

[《国字标准字体表-常用(甲表)》]: 国字标准字体表-常用(甲表).txt
[《国字标准字体表-次常用(乙表)》]: 国字标准字体表-次常用(乙表).txt
[甲表]: 国字标准字体表-常用(甲表).txt
[乙表]: 国字标准字体表-次常用(乙表).txt

## 参考资料

参考资料可在 [参考资料] 目录下找到。其中非文件类的在线资料将转换成 PDF 快照存放。

+ [Unihan.zip]
+ [25 亿字语料汉字字频表]
+ [常用字下載]
+ [次常用國字標準字體表 - 维基文库]
+ [ButTaiwan/cjktables.git]
+ ~~[rime-aca/character_set.git]~~
+ ~~[cjkvi/cjkvi-tables.git]~~

[参考资料]: 参考资料
[Unihan.zip]: https://www.unicode.org/Public/14.0.0/ucd/Unihan.zip
[常用字下載]: https://language.moe.gov.tw/result.aspx?classify_sn=23&subclassify_sn=437&content_sn=46
[次常用國字標準字體表 - 维基文库]: https://zh.m.wikisource.org/zh/%E6%AC%A1%E5%B8%B8%E7%94%A8%E5%9C%8B%E5%AD%97%E6%A8%99%E6%BA%96%E5%AD%97%E9%AB%94%E8%A1%A8
[ButTaiwan/cjktables.git]: https://github.com/ButTaiwan/cjktables
[rime-aca/character_set.git]: https://github.com/rime-aca/character_set
[cjkvi/cjkvi-tables.git]: https://github.com/cjkvi/cjkvi-tables

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
