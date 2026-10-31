# SPELLCOMMAND — MONO

モノクロのリアルタイム魔法コマンド試作。

試遊URL: https://spellcommand-mono.shawnaaaaa.chatgpt.site

現在は所有者限定のSites公開です。GitHub Pagesは未設定です。

## 操作
- 左手: WASD / 矢印キー。発動: Z / L2
- 右手: I=△ J=□ K=× L=○。発動: X / R2
- Q/E または L1/R1: カード確認（入力に選択は不要）
- P: 一時停止
- 画面ボタンでタッチ操作可能
- Standard Gamepad API対応（実機未検証）

## 試作範囲
３戦、６種類の魔法、ランダム数値補正、手札３枚、同一コマンド同時準備、左右保持、コンボ、怯み、ブレイク、６秒フィーバー。カードは準備時に手札から移動し補充、発動時に捨て札へ移動。デッキ編集・永続収集・入力精度評価・方向封印は未実装。

index.html と game.js を同じディレクトリで静的配信できます。外部依存なし。
