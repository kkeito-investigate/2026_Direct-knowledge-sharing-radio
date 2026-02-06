# 運用ガイド（Runbook）

このドキュメントは、週2回のナレッジ共有を継続運用するための手順書です。

## 目的
- 火曜（基礎）/木曜（Tips・トレンド）の継続運用
- 資産を再利用できる形で蓄積
- ミスや詰まりを再発防止として記録

## 全体像（最短）
1. Issue テンプレで起票
2. GitHub Projects でフェーズ管理（バックログ→準備中→準備完了→実施済み）
3. 確定したら `sessions/` に資料作成
4. 実施後に URL と出典を整理

## 週次の流れ（例）
- 前週金曜〜月曜: ネタ収集（トレンド/ティップスの Issue）
- 火曜: 基礎回の実施
- 水曜: 木曜回の最終調整
- 木曜: Tips/トレンド回の実施
- 週末: ふりかえりと資産整理

## GitHub Projects の使い方
- Projects をワークスペースとして使う
- `フェーズ` を看板の列にする
- `枠` を 火曜/木曜/その他 でビュー分け
- Issue 1つ = セッション/トピック1つ

詳細は `docs/PROJECTS.md` を参照。

## 資産の置き方
- 1セッション1フォルダ: `sessions/tue/` or `sessions/thu/`
- 必須ファイル: `metadata.yaml / outline.md / slides.md / script.md / references.md`
- 下書きは `runs/`、最終版は `sessions/`

詳細は `docs/ASSET_MANAGEMENT.md` を参照。

## ミスの記録（再発防止）
- 失敗や詰まりは必ず記録
- Issue テンプレ「インシデント」 + `incidents/` のポストモーテム

詳細は `docs/INCIDENTS.md` を参照。

## 会話ログ（discussion ブランチ）
- `discussion` ブランチに会話ログを保存
- `main` には混ぜない

テンプレは `docs/discussion/README.md` を参照。

## 迷ったら
- まず Issue を起票して Projects に置く
- 不明点は `docs/` の運用ドキュメントを確認
