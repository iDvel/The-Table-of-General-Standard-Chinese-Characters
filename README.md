# 《通用规范汉字表》+ 注音 + Rime 字表

为 Rime 寻觅字表时，发现官方的袖珍简化字方案、四叶草方案及其他一些方案的字表欠佳。

-   生僻字太多，包含很多古字和繁体字。
-   错误或过时的注音比较多，如「旁bang」「亡wu」「呆ai」「帧zheng」等等很多，至少几百个。

一个一个手动修改太过麻烦，干脆整理一份完全正确的。

 <br>

## 使用的数据

https://zh.wiktionary.org/wiki/Appendix:%E6%B1%89%E8%AF%AD%E6%8B%BC%E9%9F%B3%E7%B4%A2%E5%BC%95/%E9%80%9A%E7%94%A8%E8%A7%84%E8%8C%83%E6%B1%89%E5%AD%97%E8%A1%A8  

这个数据、《现汉7》、《现代汉语规范词典》之间的注音并不都相同，使用前请注意。

<br>

## Rime 的 `yaml` 字表

「nüe 虐」「lüe 略」使用了「nve」「lve」的注音。

「句、去、需、雨」等使用了「ju qu xu yu」的注音。



### `8105无字频.dict.yaml`：

格式为 `汉字\t注音`，方便自己套用任何字频，只做了去重（曲 qū qǔ → qu），未作其他加工。

<br>

### 含字频的完整版：

使用了 [fkxxyz](https://github.com/fkxxyz)/**[rime-cloverpinyin](https://github.com/fkxxyz/rime-cloverpinyin)**  四叶草输入方案（v1.1.4）的字频。

对少许注音做了一些修改，如「哟you yo」「喔 wo o」，在注释里有注明。

增加了少许不在字表中的字：如「囧」「屌」「〇」等。

调整一些权重顺序。

完善了常用多音字自动注音的问题。

不在这个仓库更新了，需要的可以查看这里：[8105.dict.yaml](https://github.com/iDvel/rime-ice/blob/master/cn_dicts/8105.dict.yaml)

<br>

### 参考配置

https://github.com/iDvel/rime-ice

