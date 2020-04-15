---
tag:
  - 学習メモ
  - PWA
---

# Progressive Web Application
----

# Service Worker
## Servidce workerとは
```
Webページとは別にバックグラウンド(別スレッド)で動作するJavascript環境のこと
```
* JavaScriptは疑似的に非同期処理を実現しているが全て単一スレッドで動いている
  * [参考](https://qiita.com/YoshikiNakamura/items/732ded26c85a7f771a27)
* 別スレッドで動作する環境を使うことでプッシュ通知やバックグラウンドでのデータ同期が可能に

