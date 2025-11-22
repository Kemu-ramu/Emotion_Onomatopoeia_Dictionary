# Emotion Onomatopoeia Dictionary

感情ごとに関連するオノマトペをカード形式で紹介する辞書アプリケーション

## 機能

- 感情カテゴリのカードをグリッド表示
- 各感情に紐づくオノマトペの定義と画像を表示
- カテゴリカードから詳細セクションへジャンプできるアンカーリンク
- カラーテーマや辞書データを `emotion.js` で簡単に編集可能

## 使い方

1. `index.html` をブラウザで開いてください。
2. 感情カードをクリックすると、ページ内の該当セクションへスクロールします。
3. 新しいオノマトペや感情カテゴリを追加したい場合は、`emotion.js` の `dictionary` / `pictureDictionary` と `emotions` 配列を編集してください。

## ファイル構成

- `index.html` - Bootstrap を読み込み、アプリ本体を描画する HTML
- `emotion.css` - カードのレイアウトやリンク領域のスタイルを定義
- `emotion.js` - 感情データと描画ロジックを保持する JavaScript

## カスタマイズ手順

1. オノマトペを追加する場合は `dictionary` と `pictureDictionary` にキー・値を追記。
2. 新しい感情カテゴリを作成する場合は `EmotionObject` のインスタンスを `emotions` 配列に追加。
3. カラーパレットやレイアウトを調整したい場合は `emotion.css` を編集。

## 参考にしたURL
[https://getbootstrap.com/](https://getbootstrap.com/)

[https://developer.mozilla.org/ja/](https://developer.mozilla.org/ja/)

[https://pixabay.com/](https://pixabay.com/)

## スニペットURL
[https://recursionist.io/users/Kemui?public-lc](https://recursionist.io/users/Kemui?public-lc)

## Github URL
[https://github.com/Kemu-ramu/Emotion_Onomatopoeia_Dictionary](https://github.com/Kemu-ramu/Emotion_Onomatopoeia_Dictionary)

## 公開サイトURL
[https://kemu-ramu.github.io/Emotion_Onomatopoeia_Dictionary/](https://kemu-ramu.github.io/Emotion_Onomatopoeia_Dictionary/)
