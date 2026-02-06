# 資産管理ルール

## フォルダ方針
- セッションは `sessions/tue/` または `sessions/thu/` に作成
- フォルダ名は `YYYY-MM-DD_topic`

## セッション最低限ファイル
- `metadata.yaml`
- `outline.md`
- `slides.md`
- `script.md`
- `references.md`

## 出典ルール
- 出典は必ず `references.md` に集約
- トレンド/ニュースは発生日と参照日を記載

## 大きいファイル
- GitHub には置かない
- 外部URLとハッシュ（またはチェックサム）を記録

## バージョン管理
- 下書きは `runs/` に置く
- 最終版は `sessions/` に昇格
- 実施後の更新は `metadata.yaml` に追記
