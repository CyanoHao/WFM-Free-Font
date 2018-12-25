# WMF 开源字体库

这是经过验证可以用于[魔兽世界字体合并/补全工具](https://github.com/CyanoHao/Warcraft-Font-Merger)的一些开源字体。

## ⚠️ 注意：开源字体的许可协议限制

使用开源字体时请遵守许可协议。以下是一些最常见的需要注意的情形：

* SIL OFL 禁止单独销售字体；
* SIL OFL 要求衍生作品也要以 SIL OFL 发布；
* GPL 要求衍生作品也要以 GPL 发布；
* SIL OFL 和 GPL 不兼容，合并之后的字体不能公开发布；
* SIL OFL 和 Apache 兼容，但合并之后的字体只能以 SIL OFL 发布；
* GPL 和 Apache 兼容，但合并之后的字体只能以 GPL 发布。

## 西文字体

| 字体名 | 版本号 | 基本拉丁字母 | 扩展拉丁字母 | 西里尔字母 | 希腊字母 | 简介 |
| ------ | ------ | ------------ | ------------ | ---------- | -------- | ---- |
| [Noto Sans](NotoSans/) | 2.000 | ✓ | ✓ | ✓ | ✓ | Google 发布的支持多语言的字体，是 Noto 家族的一部分。|
| [Noto Rounded](https://github.com/CyanoHao/Nowar-Rounded/tree/master/notor) | 0.1.1 | ✓ | ✓ | ✓ | ✓ | 基于 Noto Sans 生成的圆体。|
| [Overpass](Overpass/) | 3.000 | ✓ | ✓ | | | Expressway 的开源版本，高速公路指路标志字体。ElvUI 附带的字体。|
| [PT Sans](PTSans/) | 2.003W | ✓ | ✓ | ✓ | | 俄罗斯纪念彼得大帝推行俄语正写法改革 300 周年推出的字体。ElvUI 附带的字体。|
<!-- |  |  |  |  |  |  |  | -->

* 基本拉丁字母：英语使用的 26 个拉丁字母。
* 扩展拉丁字母：西欧诸国语言使用的拉丁字母，包括 á、ü、ò、ç 等带重音的拉丁字母，及 æ、œ、ß 等合字。
* 西里尔字母：俄文、蒙古文使用的字母。
* 希腊字母：希腊文使用的字母，也常用于数学公式。

## 中日韩字体

| 字体名 | 版本号 | GB2312 | Big5 | GBK | GB18030 | 日语假名 | 韩语谚文 | 简介 |
| ------ | ------ | ------ | ---- | --- | ------- | -------- | -------- | ---- |
| [思源黑体 SC](SourceHanSansSC/) | 2.000 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | Adobe 和 Google 联合推出的黑体家族，为简体中文优化。|
| [思源黑体 TC](SourceHanSansTC/) | 2.000 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | Adobe 和 Google 联合推出的黑体家族，为繁体中文优化。|
| [思源黑体 CN](SourceHanSansCN/) | 2.000 | ✓ | ✓ | ✓ | ✓ | ✓ |  | 面向中国大陆发布的思源黑体，不含韩语谚文。|
| [Resource Han Rounded](https://github.com/CyanoHao/Resource-Han-Rounded) | 0.990 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | 基于思源黑体生成的圆体。|
| [有爱圆体](https://github.com/CyanoHao/Nowar-Rounded) | 0.1.1 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | 魔兽世界字体包。基于 Noto Sans 和思源黑体生成的圆体，西文字符效果比 Resource Han Rounded 更好。|
<!-- |  |  |  |  |  |  |  |  |  | -->

* GB2312：常用简化字。
* Big5：常用繁体字。
* GBK：常用和次常用的简繁汉字，一般不会遇到缺字问题。
* GB18030：中日韩各国的常用汉字和次常用汉字，一般不会遇到缺字问题。
* $ (GB2312 ∪ Big5) ⊊ GBK ⊊ GB18030 $。