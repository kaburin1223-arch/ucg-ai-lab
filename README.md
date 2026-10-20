# ucg-ai-lab
UCG AI Deck Optimization Simulator
UCG AI LAB — MVP v0.1

スマートフォンのブラウザで動く、UCGスターターデッキ初手抽選の試作です。

使い方

• index.html をブラウザで開く。GitHub Pagesで公開するとSafariからURLで利用できます。
• SD01またはSD02を選択し、50枚シャッフル→6枚引く。
• 乱数シードを固定すれば同じ初手を再現可能。

未実装

引き直し、フェイズ進行、BP/効果処理、合法手、AI対戦、デッキ最適化。現段階の数値はAI評価結果ではありません。

GitHubへのアップロード

1. GitHubでPrivateリポジトリ ucg-ai-lab を作成（README初期化も可）。
2. index.html と本READMEをリポジトリへアップロードする。
3. 非公開での動作確認はCodespacesのポートプレビュー等を利用する。GitHub Pagesは公開範囲に注意してください。