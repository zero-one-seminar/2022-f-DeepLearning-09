---
marp: true
header: ""
footer: "2023/01/18 ゼロイチゼミ <a href=\"https://twitter.com/nu_zero_one\" style=\"color:white\">@nu_zero_one</a>"
theme: 01semi
paginate: true
---

<!--
headingDivider: 2
_class: title
_paginate: false
-->

# 誤差逆伝播法について

<a style="color:white; text-decoration: none;" href="https://github.com/kentakom1213">ぱうえる（けんた）:link:</a>


## 誤差逆伝播法とは？

- 前回までは、学習のために勾配を求める過程で**数値微分**という手法を利用しました
- **誤差逆伝播法**では、この過程をさらに効率的に行うことができます

| | 数値微分 | 誤差逆伝播法 |
| - | - | - |
| 実装 | 簡単 | 難しい |
| 速度 | 遅い | 速い |
