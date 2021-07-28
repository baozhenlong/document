# 数值

## 半角数字

阿拉伯数字一律使用半角形式，不得使用全角形式。

```markdown
错误：这件商品的价格是１０００元。

正确：这件商品的价格是 1000 元。
```

## 千分号

（1）数值为千位以上，应添加千分号（半角逗号）。

```markdown
XXX 公司的实收资本为 ￥1,258,000 人民币。
```

（2）对于 4 位的数值，千分号是选用的，比如`1000`和`1,000`都可以接受。对于 4 位以上的数值，应添加千分号。

## 货币

（1）货币应为阿拉伯数字，并在数字前写出货币符号，或在数字后写出货币中文名称。

```markdown
$1,000
1,000 美元
```

（2）英文的货币名称，建议参考国际标准 [ISO 4217](https://en.wikipedia.org/wiki/ISO_4217)。

## 数值范围

表示数值范围时，用波浪线（`～`）或一字线（`—`）连接。带有单位或百分号时，两个数字建议都要加上单位或百分号。参见 [标点符号](marks.md)

```markdown
132kg～234kg

67%～89%
```

## 变化程度的表示法

（1）数字的增加要使用“增加了”、“增加到”。“了”表示增量，“到”表示定量。

```markdown
增加到过去的两倍
（过去为一，现在为二）

增加了两倍
（过去为一，现在为三）
```

（2）数字的减少要使用“降低了”、“降低到”。“了”表示增量，“到”表示定量。不能用“降低 N 倍”或“减少 N 倍”的表示法，要用“降低百分之几”或“减少百分之几”。因为减少（或降低）一倍表示数值原来为一百，现在等于零。

```markdown
降低到百分之八十
（定额是一百，现在是八十）

降低了百分之八十
（原来是一百，现在是二十）
```