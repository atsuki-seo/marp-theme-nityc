---
marp: true
theme: yuge
paginate: true
header: 'ヘッダー'
footer: 'フッター'
math: mathjax
---

<!--
class: title
-->
# Marp Theme Yugeサンプル
## レイアウトテンプレート集

---

<!--
class: slide
-->
# 基本的なスライドレイアウト（class: slide）

## 見出し構造のテスト
### 小見出しの表示
- 箇条書きリスト項目
- 重要なポイント

> 引用文のスタイル確認用テキストです

```javascript
// コードブロックの表示確認
function sampleCode() {
    console.log("Hello, World!");
}
```

通常のテキストの表示確認用サンプル文章です。

---

# 良い点の強調（summary-positive）

<div class="summary-positive">

## ✅ ポジティブスタイル
- 成功事例の表示
- 良い点の強調
- 肯定的なメッセージ

</div>

---

# 注意点の表示（summary-negative）

<div class="summary-negative">

## ❌ ネガティブスタイル
- 課題や問題点の表示
- 注意すべき点
- 改善が必要な項目

</div>

---

<!--
class: flex-layout
-->

# 基本2カラムレイアウト（class: flex-layout）

<div class="columns">
<div class="summary-positive">

## 左カラム
- 短いコンテンツ
- 項目1
- 項目2
- 項目3

</div>
<div class="summary-negative">

## 右カラム（長いコンテンツ）
- 長いリストのテスト
- 項目A
- 項目B
- 項目C
- 項目D
- 項目E
- 項目F
- 項目G
- 項目H
- 項目I
- 項目J
- 項目K
- 項目L

</div>
</div>

---

<!--
class: flex-layout natural-height
-->

# Natural-Height レイアウト（class: natural-height）

<div class="columns">
<div>

## 📋 左カラム（非常に長いリスト）
- リスト項目の表示確認1
- リスト項目の表示確認2
- リスト項目の表示確認3
- リスト項目の表示確認4
- リスト項目の表示確認5
- リスト項目の表示確認6
- リスト項目の表示確認7
- リスト項目の表示確認8
- リスト項目の表示確認9
- リスト項目の表示確認10
- リスト項目の表示確認11
- リスト項目の表示確認12
- リスト項目の表示確認13
- リスト項目の表示確認14
- リスト項目の表示確認15

</div>
<div class="summary-positive">

## 🎯 右カラム（短いコンテンツ）
**特徴**
- 左側が長くても位置安定
- 各カラムが自然な高さを保持

**overflow: visible で**
**コンテンツが切れない**

</div>
</div>

---

<!--
class: flex-layout equal-height
-->

# Equal-Height レイアウト（class: equal-height）

<div class="columns">
<div class="summary-positive">

## 左カラム（短いコンテンツ）
- 短いテキスト
- 項目1
- 項目2

</div>
<div class="summary-negative">

## 右カラム（長いコンテンツ）
- 長いテキストの表示確認
- 項目A
- 項目B
- 項目C
- 項目D
- 項目E
- 項目F
- 項目G

**両カラムの高さが揃います**

</div>
</div>

---

<!--
class: flex-layout
-->

# 画像レイアウトテスト（基本）

<div class="columns">
<div>

## 左カラム画像
![サンプル画像1](../img/end.jpg)
![サンプル画像2](../img/start.jpg)

</div>
<div>

## 右カラム画像
![サンプル画像3](../img/end.jpg)
![サンプル画像4](../img/start.jpg)

</div>
</div>

---

<!--
class: flex-layout natural-height
-->

# 画像レイアウトテスト（Natural-Height）

<div class="columns">
<div>

## 📸 画像ギャラリー
![画像1](../img/end.jpg)
![画像2](../img/start.jpg)
![画像3](../img/end.jpg)
![画像4](../img/start.jpg)
![画像5](../img/end.jpg)
![画像6](../img/start.jpg)
![画像7](../img/end.jpg)
![画像8](../img/start.jpg)

</div>
<div class="summary-positive">

## 💡 レイアウト特徴
**Natural-Height**
- 左側に多数の画像
- 右側は短い説明文
- 位置が上部に固定

**画像が多くても**
**説明文の位置は安定**

</div>
</div>

---

<!--
class: flex-layout equal-height
-->

# 画像レイアウトテスト（Equal-Height）

<div class="columns">
<div class="summary-positive">

## 🎯 Before画像
![Before](../img/end.jpg)

**特徴**
- 高さが統一
- 背景色も揃う

</div>
<div class="summary-negative">

## 🚀 After画像
![After](../img/end.jpg)

**特徴**
- 左右の高さが揃う
- 見た目が整然
- 比較表示に最適

</div>
</div>

---

<!--
class: end
-->

# Thank you for watching