# THOX GitHub Agent Team（翻訳ブリッジ）

完全な仕様は[英語の原文](../../thox-agent-team.md)を参照してください。

## Review coverage

Issue、Issue コメント、Pull Request、手動検証、日次ポリシー検証を対象とします。

## Safe merge gates

必須チェック成功、ブランチ保護の許可、非ドラフト、head SHA 一致、機密変更の人手レビューを確認してからマージします。

## Branch pruning

マージ済みで同一リポジトリ内、既定・保護対象ではなく、他のオープン PR から参照されない機能ブランチのみ削除します。
