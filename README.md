# JavaScript 学習復習ページ

JavaScriptの基礎を学習するために作成した復習用ページです。

---

## 概要

HTML・CSS・JavaScriptを使った2つの機能を実装しています。

- **挨拶ページ**：名前を入力すると、時間帯に応じた挨拶を表示する
- **ニュース一覧**：JSONファイルからデータを読み込んで一覧表示する

---

## 使っている技術・概念

### JavaScript

- `const` / `let`：定数・変数の宣言
- `document.querySelector()`：HTML要素の取得
- `addEventListener()`：イベントの検知（click / input）
- `new Date()` / `getHours()`：日時の取得
- `if / else if / else`：条件分岐
- `textContent` / `innerHTML`：プロパティ操作
- アロー関数：`() => {}`
- 配列・オブジェクトの配列
- `for...of` ループ
- `fetch()` / `async` / `await`：非同期通信
- `try` / `catch`：エラー処理

### HTML / CSS

- セマンティックなHTML構造
- 外部CSSファイルの読み込み
- カードレイアウト

---

## ファイル構成

```
js-practice/
├── index.html   # メインページ
├── style.css    # スタイル
├── news.json    # ニュースデータ
└── README.md    # このファイル
```

---

## 動かし方

1. このリポジトリをクローンする

```bash
git clone https://github.com/mamimitome/js-practice.git
```

2. VSCodeで開く

3. Live Server拡張機能を使って `index.html` を開く
   - `index.html` を右クリック → `Open with Live Server`
   - またはVSCode右下の `Go Live` をクリック

> ※ `fetch()` を使っているため、ファイルを直接ダブルクリックで開くと動きません。必ずLive Serverを使ってください。

---

## 作成日

2026年4月
