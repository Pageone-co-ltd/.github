# .github

PageOne（Pageone-co-ltd）の全リポジトリに適用される Organization 共通テンプレートを管理するリポジトリです。

> **⚠️ このリポジトリは Public です。**
> 機密情報・案件固有情報・顧客名・設計書・認証情報などを一切コミットしないでください。
> 詳細は [`.github/copilot-instructions.md`](.github/copilot-instructions.md) を参照してください。

## 含まれるファイル

| ファイル / ディレクトリ            | 内容                               |
| ---------------------------------- | ---------------------------------- |
| `.github/ISSUE_TEMPLATE/`          | Issue テンプレート（6種類）        |
| `.github/PULL_REQUEST_TEMPLATE.md` | PR テンプレート                    |
| `.github/copilot-instructions.md`  | GitHub Copilot 向け組織共通指示    |

## Issue テンプレート一覧

| ファイル名  | 用途                   | ラベル   |
| ----------- | ---------------------- | -------- |
| `impl.md`   | 実装・開発             | `impl`   |
| `infra.md`  | インフラ設計           | `infra`  |
| `docs.md`   | ドキュメント作成・更新 | `docs`   |
| `bug.md`    | バグ報告・誤記修正     | `bug`    |
| `review.md` | レビュー依頼           | `review` |
| `spike.md`  | 調査・検証             | `spike`  |

## このリポジトリに投入してよい情報

以下のみを対象とします。案件固有情報・機密情報は対象外です。

- Issue テンプレート・PR テンプレート
- GitHub Copilot 向け組織共通指示ファイル
- Organization 全体に適用するワークフロー・設定ファイルで、機密情報を一切含まないもの

## 運用ルール

詳しくは [GitHub 運用ルールガイドライン](https://github.com/Pageone-co-ltd/internal-docs-musubix) を参照してください。

- Issue タイトルに種別文字列（`[IMPL]` 等）を付与する必要はありません。テンプレート選択時に自動でラベルが付与されます。
- PR 本文の「関連 Issue」欄には `Related to #番号` を使ってください（`Fixes` / `Closes` は使用禁止）。

### PR ラベル付与ルール

PR にはブランチ名プレフィックスに対応するラベルを手動で付与してください。詳細なルールは [`.github/copilot-instructions.md`](.github/copilot-instructions.md) を参照してください。
