# 《通用规范汉字表》+ 注音 + Rime 字表

为 Rime 寻觅字表时，发现官方的输入法方案、四叶草的输入方案及其他一些方案均使用了**很多**错误的注音。

如「旁bang」「亡wu」「呆ai」「帧zheng」等等很多，至少几百个，一个一个手动修改太过麻烦，干脆整理一份完全正确的。

可以自己用脚本批量对照着添加任意输入方案的字频。  

 <br>

## 使用的数据

https://zh.wiktionary.org/wiki/Appendix:%E6%B1%89%E8%AF%AD%E6%8B%BC%E9%9F%B3%E7%B4%A2%E5%BC%95/%E9%80%9A%E7%94%A8%E8%A7%84%E8%8C%83%E6%B1%89%E5%AD%97%E8%A1%A8  

这里面有几个字和《现代汉语规范词典》的注音不一样，比如「呒 m」和「欸 e」。

<br>

## Rime 的 `yaml` 字表

`8105无字频.dict.yaml`：格式为 `汉字\t注音`，方便自己套用任何字频。

`8105四叶草字频.dict.yaml`：使用了 [fkxxyz](https://github.com/fkxxyz)/**[rime-cloverpinyin](https://github.com/fkxxyz/rime-cloverpinyin)**  四叶草输入方案的字频。


