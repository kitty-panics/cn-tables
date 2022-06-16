# cn-tables

整理简中、繁中的国标汉字表。

## 协作整理

由于疏忽、参考资料有误等，码表可能会存在一些错误，
如果你发现了错误请通过 [PR] 或者 [issues] 反馈给我。

+ 如果熟悉 Git 操作可在更正错误后发起 [PR]。
+ 如果不会 Git 操作可在 [issues] 中发起反馈。

[PR]: https://github.com/kitty-panics/cn-tables/pulls
[issues]: https://github.com/kitty-panics/cn-tables/issues

## 数据格式

每个文件一行一字，以 Tab (制表符) 进行分割，例：

```Text
U+4E00	一
U+4E59	乙
U+4E8C	二
```

## 文件列表

+ [通用规范汉字表.txt]
    + 收字 8105 个。
+ [常用国字标准字体表（甲表）.txt]
    + 收字 4808 个。
+ [次常用国字标准字体表（乙表）.txt]
    + 收字 6341 个。

[通用规范汉字表.txt]: 通用规范汉字表.txt
[常用国字标准字体表（甲表）.txt]: 常用国字标准字体表（甲表）.txt
[次常用国字标准字体表（乙表）.txt]: 次常用国字标准字体表（乙表）.txt

**注：**

在甲表乙表中都有收录 `兀`、`嗀`、`斔` 三字。

## 参考资料

+ [cjkvi/cjkvi-tables]

[cjkvi/cjkvi-tables]: https://github.com/cjkvi/cjkvi-tables

## 相关项目

### [cn-tables]

整理中国大陆简中、中国台湾繁中的国标汉字表。

[cj-tables]: https://github.com/kitty-panics/cn-tables

### [unicode-cjk]

整理所有 Unicode CJK 字符。

[unicode-cjk]: https://github.com/kitty-panics/unicode-cjk

### [CNS11643-Unicode-Cangjie]

CNS11643、Unicode、Cangjie 对照表。

[CNS11643-Unicode-Cangjie]: https://github.com/kitty-panics/CNS11643-Unicode-Cangjie
