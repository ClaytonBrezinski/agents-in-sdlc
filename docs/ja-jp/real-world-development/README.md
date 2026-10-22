---
title: "実践的な開発"
slug: ja-jp/real-world-development
authors:
  - geektrainer
lastUpdated: 2026-09-16
---

現実的なシナリオ、完成したアプリケーション、共有バックログを使って、ソフトウェア開発ライフサイクル全体で GitHub Copilot を活用します。反復的に変更を計画し、コードを作成し、動作をテストし、プルリクエストを確認し、エージェントで作業を管理します。

## シナリオ

ボードゲームのクラウドファンディングを提供する架空の会社 Tailspin Toys に、新しく開発者として参加したとします。チームのバックログは GitHub Issue として登録済みなので、取り組む作業を選べます。フィルターやページネーションなどの機能追加のほか、アクセシビリティやコーディング標準などの品質改善も含まれます。

## 環境を選択する

GitHub Copilot は、作業する場所を問わず利用できます。自分の開発方法に合った環境を選択してください。各ワークショップには個別のセットアップがあり、共通の Tailspin Toys シナリオを使用します。

### [GitHub Copilot CLI][cli]

ターミナルでエージェント型アシスタントを使用します。Plan モードと Autopilot モード、指示、スキル、カスタム エージェント、Playwright MCP、Agent Merge、便利なスラッシュ コマンドを使って作業します。

### [GitHub Copilot アプリ][app]

エージェント セッションを並行して実行し、セッション モードを切り替え、キャンバスで共同作業し、デスクトップ アプリで GitHub Issue とプルリクエストを管理します。

### [GitHub Copilot クラウド エージェント][cloud]

GitHub Issue を非同期エージェントに割り当て、その作業を指示して進捗を確認し、エージェントが作成したプルリクエストをレビューします。

### [Visual Studio Code][vscode]

Visual Studio Code と GitHub Codespaces で GitHub Copilot を使用します。エディターを離れずに、Copilot Chat のエージェント モード、MCP サーバー、カスタム エージェントを活用します。

[cli]: cli/
[app]: app/
[cloud]: cloud/
[vscode]: vscode/
