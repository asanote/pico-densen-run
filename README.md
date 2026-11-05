# ピコの電線ラン

でんきの子ピコが、電線の町から地下ケーブル道を抜けて発電所をめざす横スクロールアクションです。全3ステージ。

**遊ぶ:** https://asanote.github.io/pico-densen-run/

## 操作

| 操作 | キーボード | タッチ | コントローラー |
| --- | --- | --- | --- |
| 移動 | ← → / A D | 左右ボタン | スティック・十字キー |
| ジャンプ（長押しで高く） | Z / Space / ↑ | A | Xbox: A / Switch: A・B |
| ダッシュ・放電（ギガ） | X / Shift | B | Xbox: X・B / Switch: X・Y |
| 一時停止 | P / Esc | 画面タップで再開 | メニューボタン / + − |

## 進化

- **ピコ**: 1回当たるとミス
- **メガ**: 電池で進化。レンガを壊せる
- **ギガ**: 雷コアで進化。B で放電

## 構成

`index.html` 1枚で完結しています（ビルド不要）。claude.ai の Artifact 版から移したものです。

- 元の Artifact: https://claude.ai/artifact/1mC5Ev9nuTuEREogVQ6BMx
- ハイスコアと解放済みステージはブラウザの localStorage に保存します。

ローカルで遊ぶときは `index.html` をブラウザで開くだけで動きます。
