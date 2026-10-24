# aidd-claude-home

著者（mryo0826）の Claude Code の個人設定（`~/.claude`）のうち、公開して良い物だけを追跡しているリポジトリです。[AI駆動開発 実践ガイド](https://github.com/mryo0826/aidd-practice-guide) を回す時に、実際に使っている設定です。

## 中身

| ファイル | 何か |
|---|---|
| `CLAUDE.md` | 個人の作業原則。Claude Code が全てのプロジェクトで読み込む。日本語の表記の決まり（平仮名より漢字にする語の一覧等）が入っている |
| `settings.json` | Claude Code の個人設定（権限・モデル・effort 等）。値は著者の環境に合わせた物 |
| `.gitignore` | 許可リスト。全てを無視し、ここに挙げたファイルだけを追跡する。認証情報・会話の記録・履歴を追跡しない為 |

## 日本語の表記の決まりについて

AI が書く日本語は、推敲の仕組みを別に作らなくても、表記の決まりを数行渡すだけで読みやすくなる、というのが著者の実践です（測った物ではありません）。決まりは `CLAUDE.md` の中身そのものです。

## 使う時の注意

- 丸ごと自分の `~/.claude` に置かないで下さい。`settings.json` には、著者の手元のパス（作業日誌のリポジトリ）が入っています。要る行だけを持って行って下さい。
- 誰でも使える形の個人メモリのテンプレートは、ガイドの側の [`user-memory-template.md`](https://github.com/mryo0826/aidd-practice-guide/blob/main/user-memory-template.md) にあります。このリポジトリは、著者自身の実物です。

## ライセンス

[MIT No Attribution（MIT-0）](LICENSE)
