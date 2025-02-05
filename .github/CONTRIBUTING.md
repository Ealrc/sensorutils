# Contributing to sensorutils

**Caution**

このガイドラインは執筆途中であり，今後ガイドラインに大幅な変更が行われる可能性があります．

---

Thank you for your contributing!! 😄

このドキュメントはsensorutilsの開発に参加するためのガイドラインです．
バグ報告や機能の追加といったsensorutilsへのContributeを行う際は以下のルールを理解し，
適切な方法で提案を行ってください．
また，このドキュメント自体に提案がある場合はIssueでその内容を報告してください．


## 目次

[sensorutilsの開発方針](#sensorutilsの開発方針)

[バグの報告](#バグの報告)

[バグの修正](#バグの修正)

[機能の追加](#機能の追加)

[スタイルガイド](#スタイルガイド)

---

## sensorutilsの開発方針

### 目的と方針

sensorutilsは主にセンサベースの行動認識ベンチマークデーセットの読み込みや前処理を簡単かつ高速に実行するためのライブラリです．現在は行動認識データセットの読み込み周りの機能が中心ですが，今後はセンサデータに対するより広範な操作を実装していく予定です．

### Feature works

sensorutilsの将来的な目標は以下の通りです．

- センサデータに対するより広範な操作への対応
- より多くのデータセットローダのサポート
- 音声データへの対応(signalutilsへ向けて)

---

### バグの報告

バグを発見したら，十分な確認を行った後，
以下の手順で適切な報告を行ってください．

- バグの再現方法やバグ発生時の挙動などバグに関する詳細な内容を明らかにしてください．
- 次にIssueやPull Requestを検索して，発見したバグがまだ未報告であることを確認してください．
- もし発見されたバグが未報告なものであれば，Issueでそのバグを詳細に報告してください．報告の際は`Bug report`テンプレートを使用して説明を行うようにしてください．ただし，バグ報告の際は厳密にテンプレートに従う必要はなく，コントリビュータが説明しやすい形で報告を行って頂いて構いません．
- また，報告する際は可能な限り，関連するIssue番号を引用し，リンクを張っていただけると助かります．

### バグの修正

バグを修正したら，以下の手順で適切な提案を行ってください．
ただし，修正は下記の[スタイルガイド](#スタイルガイド)に従って作成してください．

**Issueで報告されたバグを修正した場合**

- Pull Requestを介して修正を提案する．
- Pull Requestを作成する際はバグの内容をと修正方法を明確に示す．
- 説明には関連するIssue番号を含める．

**Issueで報告されていないバグを修正した場合**

- バグの規模が非常に小さなものでプロジェクトへの影響が小さいものはPull Requestにバグの内容と修正方法を示したうえで，提案を行う．
- バグの規模が比較的大きくプロジェクトに小さくない影響を与える場合は，Pull Requestで提案すると同時にIssueでバグの報告を行う．その際はPull Request番号をIssueに含めるようにする．

### 機能の追加

新しい機能の追加や既存の機能強化を提案する場合は，
Issueで提案内容を説明してください．
またその際は以下の項目を踏まえた説明を心がけてください．

- 提案する機能がなぜ必要なのか？
- 提案する機能を実装する場合はどの程度の規模になると想定されるか？

提案内容を議論した結果，その機能を実装することになった場合，
新たな機能はPull Requestでその機能の実装を提案します．
ただし，実装を行う際は下記の[スタイルガイド](#スタイルガイド)に従うようにしてください．

---

### スタイルガイド

コーディングスタイルについてはドキュメントを鋭意作成中です．

もしこの段階でバグ修正や機能追加の提案を行いたい場合は，
既存のコードのスタイルを参考にコードを記述するようにしてください．

