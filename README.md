### こんにちは Suzuki です

カスタマーサポート × ナレッジマネジメント × 生成AI で、CS の現場を仕組みで改善しています。
2022年から CS・営業・テレアポに携わり、現在はフードデリバリー会社の顧客サポートチームのSVとして現場の運用と品質に責任を持っています。
料理や旅行が好きで、海外で食べた料理を再現するのにハマってます。

#### 代表プロジェクト

**[cs-rag-engine](https://github.com/kydlp/cs-rag-engine)** — D2CブランドのCSを *人間承認フロー付き* で自動化するRAGエンジン（受託案件の匿名公開版）
- ナレッジをSSOTに一元化 / 生成AIで根拠付きの返信下書き / 回答品質をKPI化して継続改善
- 実運用で **品質の合格率 73.5%→80.0%**、**エスカレーション精度 98.0%**、**エスカレ見逃し（FN）0件**
- CS・ナレッジ視点の解説: [docs/cs-knowledge-management.md](https://github.com/kydlp/cs-rag-engine/blob/main/docs/cs-knowledge-management.md)

**[vending-ops-analytics](https://github.com/kydlp/vending-ops-analytics)** — 手作業で回っていた売上・精算のスプレッドシートを、検証可能な形に作り直した記録（受託案件の匿名公開版）
- 壊れていた旧ファイルの数式279個を全ダンプして問題を特定 → マスタ/入力/集計/出力の4層に再設計
- 移行時は **旧ファイルの支払額を1件ずつ再計算して突合**し、合わない分に理由をつけてから置き換え
- 「綺麗にした」で終わらせず、**差の理由を一覧で示してから移行する**という進め方そのものが成果物

**[vending-telemetry-bridge](https://github.com/kydlp/vending-telemetry-bridge)** — 公開APIのない業務システムから、日次データを無人で取り続けるための設計・運用記録（ドキュメントのみ）
- 「1人しか取り出せない事実」「休むと止まる確認作業」を、**失敗時に必ず鳴る**自動化に置き換えた
- やらなかったこと・断ったこと（請求に影響する設定は触らない）まで記録

#### よく使う技術・ツール
TypeScript / Python / Cloudflare Workers / Anthropic Claude / NotebookLM / Gmail API / BASE
