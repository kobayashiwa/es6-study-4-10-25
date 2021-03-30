# es6-study-4-10-25
JavaScript 学習コース IV > クラスの継承 > 継承とは

## 継承とは
「継承」とは、すでにあるクラスをもとに、新しくクラスを作成する方法のこと。
例えば「Aクラス」から「Bクラス」を継承すると、「Aクラス」の全ての機能を引き継いで、「Bクラス」を作成することができる。

#### 継承の書き方
継承を用いてクラスを作成するには「extends」を用いる。
例えば、「Aクラス」を継承して「Bクラス」を作成するには、「class B extends A」と書く。
また、継承では元となるクラスを親クラス（例のAクラス）、新しく作成するクラスを子クラス（例のBクラス）と呼ぶ。

## コーディングトレーニング
「リグナイト株式会社」のレイアウト構造をレスポンシブで写経する。

#### サイト構造
header > logo - nav - toggle
main > section（hero-image） - section（index--about） - section（index--phenol） - section（index--products） - section（index--application） - section（index--works） - section(index--develop)
aside
footer

#### ブレイクポイント
- desktop（992px ↑）
- tablet（991px ↓）
- smartDevice（767px ↓）

## チャレンジ
- ハンバーガーメニューに画像やSVGを使わずcssで描画する
- ヘッダーの高さ分スクロールしたらヘッダーのheightを変更する
