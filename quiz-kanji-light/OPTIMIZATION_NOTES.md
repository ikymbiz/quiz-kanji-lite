# 起動軽量化メモ

- `index.html` の途中で切れていた JavaScript を復元しました。
- 起動時に `quiz-data.json` / `character.json` を待たず、必要になったタイミングで読み込むようにしました。
- `splash.png` とキャラクターPNGを WebP に変換しました。
- トップ画像は初期表示後に遅延読み込みします。
- 図鑑の未開放キャラ画像は読み込まず、開放済み画像だけ `loading="lazy"` で読み込みます。
