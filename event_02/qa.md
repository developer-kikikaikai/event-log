# ソフトウェア開発　炎上学概論（２）アジャイルとウォーターフォールによる炎上防止

## 質疑ログ

- 開発スタイル
    - アジャイルは開発手法の話。ただ継続して開発するから可能。
        - 受託の中でも、例えばWebサービスはずっと継続していくからアジャイルな開発は可能。客を巻き込む必要あり
    - 銀の弾丸ではない
- アジャイル開発の例
    - 例えばゲーム業界。ユーザーが面白いものを作らないと意味がないので、アジャイルを取り入れることができる
    - 例えば基幹系だと、BEは基幹システムと紐づいてるので難しいが、ユーザーインターフェースとなる部分に対してアジャイルな開発を実践したこともある
    - 導入にあたり、プラクティスを変えるな。例えばデイリースクラムはきちんと毎日やる等、意味のあることをきちんと実施し、なんちゃってにならないようにする
- テストについて
    - アジャイルだと修正したらテストを回すのが通例となっているが、逆にウォーターフォールを免罪符に適切なテストをしないプロジェクトもある
    （今は結合試験フェーズだから単体試験をやらないといった形）
    そうではなくて、フェーズをくぎったものが絶対ではなくて必要なことはスキップするとまずい
- アジャイルはドキュメントいらない？
    - その認識は間違っている。コミュニケーションの手法として必要なものは残すべき
    - 手法関係なく、ドキュメントを残さないプロジェクト、ありがち。
    - 一部にいる、そういった間違った考え・免罪符にする人の意識をどう変えていくか？
        - 意識改革をしていく為に働きかける必要がある。
        https://twitter.com/SengtoInc/status/1216168517373841409
    - アジャイルへの認識が間違っている人が、なんちゃってアジャイルにしがち
    - 関連する記述の原文:https://agilemanifesto.org/
　　　*Working software* over comprehensive documentation
　　　あくまでソフトウェアが大事だと言っているだけで、ドキュメントの重要性を下げたりはしていない
アジャイルの見積り・スケジュールについて
- アジャイルは相対値を使う？実測値を使うこともある。1タスク辺りの見積精度を繰り返しの中で上げていくもの
- タイムボックスという考え方が大事。この中でバックログ残数と期間の関係を可視化
    - タイムボックスで期間終了時に残件が0にならないバックログが、スケジュールに収まらない作業となる
    - タイムボックスの状態を見て、適宜その中身の調整をすることが、スケジュール管理としてやれることになる
- 生産性・見積精度の話
    - 繰り返し同じチームが作業をするから、効率や見積精度が上がっていくという発想
    - これは、ウォーターフォールなプロジェクト内でも同じチームで似たようなプロジェクトを回しているとスキルが上がるのでは？
        - チームのノウハウ・情報をどれくらい詰めているか？の重要度はウォーターフォールでもアジャイルでも変わらない
        - ウォーターフォールといっても、実際は小さいプロジェクトから始まって、徐々に機能追加していくことも多い
    - 一気にリプレイスみたいな一度きりの経験のものは炎上するよね
- 属人性問題
    - プロジェクト参画者をどう教育するの？という悩みはあるが、これは手法とは関係ない話