# 2026 生成AIナレッジ共有

役員向けの週次AIナレッジ共有の資産管理リポジトリ。

## スケジュール
- 火曜: AI開発の基礎（イロハ）
- 木曜: Tips と一般トレンド

初回セッション: 2026-02-10（火）

## ワークスペース（GitHub Projects）
GitHub Projects（v2）を準備・共有・振り返りの中心として運用します。
詳細は `docs/PROJECTS.md` を参照。

## リポジトリ構成
- `sessions/`: セッションごとの資料（構成、スライド草案、台本、参考）
- `templates/`: 再利用テンプレート
- `assets/`: 共有画像やコード断片
- `runs/`: エージェントの中間生成物
- `docs/`: 運用ルール
- `incidents/`: ミスの再発防止ログ

## 使い方（最短導線）
1. Issue テンプレート「セッション提案」で起票
2. GitHub Projects で管理
3. 確定したら `sessions/tue/` または `sessions/thu/` にフォルダ作成
4. `templates/session/` を使って作成開始

## スラッシュコマンド
`docs/COMMANDS.md` を参照

## ルール
- セッションフォルダ名: `YYYY-MM-DD_topic`
- 出典は必ず `references.md` に集約
- 大きいファイルは外部保存し、URL とハッシュのみ記載
- ミスは `docs/INCIDENTS.md` と `incidents/` に記録
