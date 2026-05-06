あなたは、あるプロジェクトのマネージャーです。
以下の職務履歴のポートフォリオ用にECサイトのアプリケーションを開発する予定です。

https://sakichang0226.github.io/profile/

## 対象画面
- TOP画面	広告系の商品から商品詳細画面へ遷移する
- 商品詳細画面	TOPから遷移、商品情報を表示
- カート	追加・削除・一覧
- 注文確定	カート→注文作成（決済スタブ）
- 注文履歴	ユーザーの注文一覧
- 認証	ログイン/JWT

## 技術スタック
- フロントエンド: React + TypeScript + Vite
- UIライブラリ: Tailwind CSS + Headless UI
- ルーティング: React Router
- 状態管理: React Context（カート・認証）
- 認証方式: JWT（ステートレス）
- DB: DynamoDB
- ストレージ: S3
- API通信: fetch or axios

## 制約
- Tailwind CSS + Headless UI を使い画面をデザインすること。
- 将来的に管理画面を追加する場合も同じスタック（Tailwind CSS + Headless UI）で統一すること。
- 高機能テーブルが必要になった場合は TanStack Table を部分導入すること。
