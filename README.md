# 手でひらく

カメラで手の形を読み取り、形ごとに決めたサイトを開くページです。
同じ形を1秒続けると、そのサイトへ移動します。

公開ページ: https://yannsi.github.io/te-de-hiraku/

| 手の形 | 開くサイト |
|---|---|
| ✌️ ピース | YouTube |
| 👍 親指を上 | 天気（tenki.jp） |
| 🤟 アイラブユー | Googleマップ |

割り当ては `index.html` の「ここを書き換えると…」の部分で変えられます。
映像は端末の中だけで処理し、どこにも送りません（MediaPipe Gesture Recognizer を使用）。
