# ボンバーこうかとん

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
* 障害物も敵も爆弾で破壊するゲーム with こうかとん
* 参考URL：[レトロゲームの殿堂](https://w.atwiki.jp/yamamura2/pages/374.html)

## ゲームの遊び方
* 矢印キーでボンバーKOKAを操作し、スペースキー押下による足元への爆弾設置。
* 三分以内に他キャラクターを殲滅、もしくは最大スコアの状態で勝利。

## ゲームの実装
### 共通基本機能
* 主人公キャラ
* 矢印操作機能
* 盤面領域内判定関数

### 分担追加機能
* Helo(操作キャラ)クラス(北村)
* 壁の生成、破壊機能クラス(北村)
* マップ詳細生成機能クラス(北村)
* 敵クラス(小林)
* 爆弾の制御機能クラス(小林)
* 他キャラの行動機能クラス(小林)
* タイマー機能クラス (町田)
* 効果音、BGM制御機能クラス(町田)
* スコア機能クラス(おん)
* タイトル画面描画機能クラス(岡崎)
* ゲームオーバー画面描画クラス(岡崎)

### ToDo
- [1] マージ後のコメントなどの精査、修正
- [2] 記述方法の統一
- [3] 素材作成
- [4] 細かな機能の発案、実装

### メモ
* main関数は最低限の呼び出しのみで記述している
* 汎用的な関数を用意して、動作対象に適用している
