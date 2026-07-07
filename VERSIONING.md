# VERSIONING（演習用 contracts の版管理規約）

- semver 3 要素固定（prerelease/build メタは対象外 — contract_pin の MVP 契約に一致）
- 互換変更（optional field 追加・endpoint 追加）= minor bump
- 破壊的変更（field 削除・型変更・required 化）= major bump 必須
- 版系列は v{X.Y.Z}.yaml の並置ファイルで表現する（演習で任意の版間を
  oasdiff 比較できるようにするための形式 — 実運用の git 履歴の代替）
