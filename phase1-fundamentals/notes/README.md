# Phase 1: 基礎（Claude 101 / AI Fluency）

## 学習範囲
- Claude の基本的な使い方・機能理解
- AI Fluency Framework（4D: Delegation, Description, Discernment, Diligence）
- Claude のモデル比較（Opus / Sonnet / Haiku）

## 対応する試験ドメイン
全ドメインの前提知識

## リソース
- [Claude 101（Anthropic Academy）](https://anthropic.skilljar.com/claude-101)
- [AI Fluency Framework](https://anthropic.skilljar.com/)

## 進捗
- [x] セクション1: Meet Claude（Day 1）
- [x] セクション2: Organizing your work — Desktop App / Projects / Artifacts（Day 2）
- [x] セクション3: Expanding Claude's reach — Skills（Day 2）
- [ ] セクション3 続き: Connectors / Enterprise Search / Research mode
- [ ] セクション4: Use-cases
- [ ] Claude 101 修了証の取得

## メモ

### Day 1（2026-04-04）— Meet Claude

#### Claudeの3つの原則
- 有益（Helpful）・正直（Honest）・無害（Harmless）

#### プロンプト作成の3ステップ
1. 状況説明 — 自分の役割・目標・背景情報を伝える
2. タスクの定義 — 書いてほしいのか、分析か、構築か、具体的な行動を指示する
3. ルールの指定 — スタイル・トーン・サンプルを提示する

#### 4Dフレームワーク
- **Delegation（委任）** — 適切なタスクをAIに任せる
- **Description（記述）** — 明確な指示を書く
- **Discernment（識別）** — 出力の品質を判断する
- **Diligence（勤勉）** — 継続的に改善する

#### よくある課題と解決策
| 課題 | 解決策 |
|------|--------|
| 回答が一般的すぎる | 対象者・役割・制約を具体的に追加 |
| 回答が長すぎる/短すぎる | 「2段落で」「100語以内で」と明示 |
| フォーマットが違う | 例を示す or 構造を具体的に説明 |
| 情報が間違っている | 重要な事実は独自検証、情報源を要求 |
| 口調が合わない | 「会話調で」「フォーマルに」と指定 |

### Day 2（2026-04-05）— Desktop App / Projects / Artifacts / Skills

#### Claudeデスクトップアプリの3つのモード
| 項目 | Chat | Cowork | Code |
|------|------|--------|------|
| 用途 | 素早い対話・アイデア探求 | 複雑・継続的な作業（調査・分析・文書作成） | ソフトウェアの構築（記述・テスト・デプロイ） |
| 主な機能 | クイック入力、音声入力 | ローカルフォルダ、プラグイン、サブエージェント | 質問/コード/計画モード、ビジュアル差分、Git統合 |

- CoworkとCodeは内部的に同じエンジン（Claude Code）で動作

#### プロジェクト
- 知識の保存、関連チャットの整理、チーム共同作業に使う機能
- 大量のファイルはRAGモードで最大10倍まで拡張可能
- 3段階の権限レベル: 閲覧可能 / 編集権限 / 所有者

#### アーティファクト
- 会話の横に専用ウィンドウとして作成されるもの
- 種類: ドキュメント / コード / HTMLページ / SVG画像 / Mermaid図 / Reactコンポーネント

#### スキル
- Claudeが特定のタスクのパフォーマンスを上げるための専門知識パッケージ
- Anthropic Skills（公式）とカスタムスキル（自作）の2種類

#### プロジェクトとスキルの違い（重要）
| 項目 | プロジェクト | スキル |
|------|-------------|--------|
| 目的 | 知識を蓄える（参考文献） | 実行するプロセスを定義する |
| 最適 | 長期的な視点、参考資料、チーム共同作業 | 反復可能なワークフロー、複数ステップのタスク |
| 持続性 | プロジェクト内の全チャットで利用可能 | スキルが発動された際に適用される |
