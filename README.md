個人開発で、日常の記録アプリと、Windows 上の起動・習慣ツールを作っています。

## 作っているもの

- **my-apps** — 食材、体調、消耗品、家計、日課を一つの React アプリにまとめています。API は Cloud Run 上の FastAPI、データは Firestore です。PDF への質問は LangChain で扱います。
- **my-tool** — Electron で、ショートカット、壁紙、画像、アプリの使用時間、YouTube の視聴枠を一つの窓にしています。画像と壁紙は Python です。
- **my-directory-clean** — ディレクトリ整理の CLI と GUI です。破壊的な操作はまず dry-run で、実行しても既定はゴミ箱送りです。
- **mcp-workspace-projects** — 複数プロジェクトを、Cursor などの MCP から索引・検索・読取できるようにするサーバーです。
- **drive-ledger** — Google Drive 上の既存ファイルを台帳にするアプリです。画面は React、実行基盤は Cloud Functions、データは Firestore、認証は Identity Platform を想定しています。

## 技術

React、TypeScript、Electron、Python、FastAPI、Cloud Run、Firestore、LangChain
