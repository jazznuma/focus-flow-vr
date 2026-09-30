# Focus Flow

Quest 3 の Meta Quest Browser で遊べる、星空をテーマにした WebXR ゲームのプロトタイプです。

## ゲームモード

- **星を見つける** — 近く／遠くに交互に現れる星を選ぶ
- **流星を待つ** — 遠くの星を眺めながら、ゆっくり星を探す
- **リズムキャッチ** — 流れてくる星をテンポよく選ぶ

操作はコントローラーのレーザーでターゲットを選びます。デスクトップでは「画面で試す」からマウスでプレビューできます。WebXR 部分は A-Frame を CDN から読み込みます。

## GitHub Pages で公開

1. リポジトリのルートに `index.html` と `README.md` を置きます。
2. GitHub の **Settings → Pages** を開きます。
3. **Build and deployment → Deploy from a branch** を選び、既定ブランチと `/ (root)` を指定して保存します。
4. 表示された Pages の URL を Quest 3 の Meta Quest Browser で開きます。WebXR には HTTPS が必要で、GitHub Pages の公開 URL は HTTPS です。

## 注意

このプロトタイプは視覚を使ったゲーム体験であり、視力回復や眼疾患の治療効果を示すものではありません。VR内の仮想距離を変えても、一般的なVRヘッドセットでは実際の目のピント距離は変わりません。違和感、眼精疲労、複視、頭痛、吐き気などを感じたら、すぐに終了して休憩してください。
