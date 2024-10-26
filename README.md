# Anthropic Cookbook

Anthropic Cookbookは、開発者がClaudeを使って開発するためのコードとガイドを提供します。自身のプロジェクトに簡単に統合できるコードスニペットを用意しています。

## 前提条件

このクックブックの例を最大限活用するには、Anthropic APIキーが必要です（[こちら](https://www.anthropic.com)から無料で登録できます）。

コード例は主にPythonで書かれていますが、基本的な考え方は、Anthropic APIとの連携をサポートする任意のプログラミング言語に応用できます。

Anthropic APIを初めて使用する場合は、基礎をしっかりと理解するために、[Anthropic API 基礎コース](https://github.com/anthropics/courses/tree/master/anthropic_api_fundamentals)から始めることをお勧めします。

## さらに詳しく

ClaudeやAIアシスタントの活用をさらに深めるために、以下の有用なリンクをご覧ください：

- [Anthropic 開発者ドキュメント](https://docs.anthropic.com/claude/docs/guide-to-anthropics-prompt-engineering-resources)
- [Anthropic サポートドキュメント](https://support.anthropic.com)
- [Anthropic Discordコミュニティ](https://www.anthropic.com/discord)

## コントリビューション

Anthropic Cookbookは、開発者コミュニティの貢献によって成り立っています。アイデアの提案、タイプミスの修正、新しいガイドの追加、既存のガイドの改善など、あらゆる形での貢献を歓迎します。皆様の貢献により、このリソースはより価値のあるものとなります。

作業の重複を避けるため、コントリビューションの前に既存のイシューとプルリクエストを確認してください。

新しい例やガイドのアイデアがある場合は、[issues ページ](https://github.com/anthropics/anthropic-cookbook/issues)で共有してください。

## レシピ一覧

### スキル
- [引用](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/citations)：Claudeに回答の中で出典を引用させる方法を学びます。
- [分類](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/classification)：Claudeを使用したテキストとデータの分類テクニックを探ります。
- [検索拡張生成（RAG）](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/retrieval_augmented_generation)：外部知識でClaudeの回答を強化する方法を学びます。
- [要約](https://github.com/anthropics/anthropic-cookbook/tree/main/skills/summarization)：Claudeによる効果的なテキスト要約のテクニックを学びます。

### ツールの使用と統合
- [ツール使用](https://github.com/anthropics/anthropic-cookbook/tree/main/tool_use)：Claudeの機能を拡張するための外部ツールや機能との統合方法を学びます。
  - [カスタマーサービスエージェント](https://github.com/anthropics/anthropic-cookbook/blob/main/tool_use/customer_service_agent.ipynb)
  - [電卓との統合](https://github.com/anthropics/anthropic-cookbook/blob/main/tool_use/calculator_tool.ipynb)
  - [SQLクエリ](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/how_to_make_sql_queries.ipynb)

### サードパーティ統合
- [検索拡張生成](https://github.com/anthropics/anthropic-cookbook/tree/main/third_party)：外部データソースでClaudeの知識を補完します。
  - [ベクトルデータベース（Pinecone）](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/Pinecone/rag_using_pinecone.ipynb)
  - [Wikipedia](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/Wikipedia/wikipedia-search-cookbook.ipynb/)
  - [Webページ](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/read_web_pages_with_haiku.ipynb)
  - [インターネット検索（Brave）](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/Brave/web_search_using_brave.ipynb)
- [Voyage AIによるエンベディング](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/VoyageAI/how_to_create_embeddings.md)

### マルチモーダル機能
- [Claudeでのビジョン機能](https://github.com/anthropics/anthropic-cookbook/tree/main/multimodal)：
  - [画像処理入門](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/getting_started_with_vision.ipynb)
  - [ビジョン機能のベストプラクティス](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/best_practices_for_vision.ipynb)
  - [チャートとグラフの解釈](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/reading_charts_graphs_powerpoints.ipynb)
  - [フォームからのコンテンツ抽出](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/how_to_transcribe_text.ipynb)
- [Claudeでの画像生成](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/illustrated_responses.ipynb)：画像生成のためにClaudeとStable Diffusionを使用します。

### 高度なテクニック
- [サブエージェント](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/using_sub_agents.ipynb)：OpusとともにHaikuをサブエージェントとして使用する方法を学びます。
- [PDFのClaudeへのアップロード](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/pdf_upload_summarization.ipynb)：PDFを解析してテキストとしてClaudeに渡します。
- [自動評価](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/building_evals.ipynb)：Claudeを使用してプロンプト評価プロセスを自動化します。
- [JSONモードの有効化](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/how_to_enable_json_mode.ipynb)：Claudeから一貫したJSON出力を確保します。
- [モデレーションフィルターの作成](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/building_moderation_filter.ipynb)：アプリケーション用のコンテンツモデレーションフィルターをClaudeで作成します。
- [プロンプトキャッシング](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/prompt_caching.ipynb)：Claudeでの効率的なプロンプトキャッシングのテクニックを学びます。

## 追加リソース

- [AWS上のAnthropic](https://github.com/aws-samples/anthropic-on-aws)：AWS インフラストラクチャ上でClaudeを使用するための例とソリューションを探索します。
- [AWSサンプル](https://github.com/aws-samples/)：AWSのコードサンプル集で、Claudeで使用するように適応できます。一部のサンプルはClaudeで最適に動作するように修正が必要な場合があります。

