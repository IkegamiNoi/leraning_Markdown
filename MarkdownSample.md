## VisualStudioCodeでMarkdownプレビュー表示をする方法
Ctrl + Shift + p

# 見出し1
## 見出し2
### 見出し3
#### 見出し4

## 改行方法
行の終わりに半角スペースを2つ入れる

## 引用
> 引用
>> 二重引用

## コード記述
```
コード
```

## インラインコード
`インラインコード`

## 文字の色付け(例として赤にしている)
<span style="color: red; ">赤文字</span>

## 箇条書き
- 箇条書き
* 箇条書き
+ 箇条書き

## 番号リスト
1. 番号リストA
1. 番号リストB
    1. 番号リストC
1. 番号リストD

## 水平線
***
*****
---
-----
___

## テーブル
| 項目名1 | 項目名2 |
| --- | --- |
| 項目1 | 項目2 |

## 注釈
テキスト[^1]
[^1]: 注釈の内容

## PlantUML記法
```uml
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response

Alice -> Bob: Another authentication Request
Alice <-- Bob: another authentication Response
```

## 数式(LaTeX記法)
```math
x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}
```

### インライン記述
$e^{i\pi} = -1$

## 強調
*イタリック*
**太字**
***イタリックの太字***

## 打消し線
~~ 打消し ~~

## 折り畳み
<details><summary>サンプルコード</summary>
平文では必要なし

### Markdown記法を使用する場合空行が必要

```rb
puts 'Hello, World'
```
</details>

## リンク
[Google先生](https://www.google.co.jp/)

## 定義参照リンク
[こっちからgoogle][google]
その他の文章
[こっちからもgoogle][google]

[google]: https://www.google.co.jp/


