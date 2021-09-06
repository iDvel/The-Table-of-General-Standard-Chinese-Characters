# 《通用规范汉字表》+ 注音 + Rime 字表

为 Rime 寻觅字表时，发现官方的输入法方案、四叶草的输入方案及其他一些方案均使用了**很多**错误的注音。

如「旁bang」「亡wu」「呆ai」「帧zheng」等等很多，至少几百个，一个一个手动修改太过麻烦，干脆整理一份完全正确的。

可以自己用脚本批量对照着添加任意输入方案的字频。  

  

## 使用的数据

https://zh.wiktionary.org/wiki/Appendix:%E6%B1%89%E8%AF%AD%E6%8B%BC%E9%9F%B3%E7%B4%A2%E5%BC%95/%E9%80%9A%E7%94%A8%E8%A7%84%E8%8C%83%E6%B1%89%E5%AD%97%E8%A1%A8  

  

  

## Rime 的 `yaml` 字表

### 一些修改：

去重，如「曲 qū qǔ」去掉声调后都是「qu」，结合 Rime 的 `derive/^([jqxy])u/$1v/` 用「qu」或「qv」都可以打出来。

「nüe 虐」「lüe 略」使用了「nue」「lue」的注音。
「lǜ 绿」「nǚ 女」等使用了「lv」「nv」的注音。
「句、去、需」等使用了「ju qu xu」的注音。
「呒   ḿ」修改为「呒   mu」。
「呣	ḿ」「呣	m̀」修改为「m」。
「嗯 ng」修改为「en」。
「欸」四种「e」音，删除并只保留「ai」  。

  

### 文件：

`8105无字频.dict.yaml`：格式为 `汉字\t注音`，方便自己加工任何字频。

`8105四叶草字频.dict.yaml`：使用了 [fkxxyz](https://github.com/fkxxyz)/**[rime-cloverpinyin](https://github.com/fkxxyz/rime-cloverpinyin)**  这个项目的字频。



#### 额外扩展：

有些字、词不在《通用规范汉字表》里，但可能会用到的，如：

```
〇	ling
囧	jiong
屌	diao
艹	cao
肏	cao
冇	mao
曱甴	yue you
朙月拼音	ming yue pin yin
佇列	zhu lie
```



