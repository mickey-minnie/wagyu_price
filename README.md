# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリはウェブ上でのファイルの保存場所のことで、ローカルリポジトリは自分のPC上での作業場所


## プッシュとマージの違いは何でしょうか？
- プッシュはローカルリポジトリからリモートリポジトリにファイルを同期することで、マージは同じリポジトリ上で作業用ブランチからメインブランチに同期すること


## コミットとプッシュの違い
- コミットはローカルリポジトリ上で変更履歴を残す作業で、プッシュはコミットで残した変更履歴をリモートリポジトリに同期すること


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 変更履歴を見た際に、そのコミットのメッセージから、どんな変更を行なったのかがわかるように書いてあげること


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルでマージするフローは、メインブランチにマージ後に自分でリモートリポジトリにプッシュするため反映は早いがミスが見落とされる危険性があり、プルリクエストでマージするフローは、プルリクエストをすることによりコードの確認作業をコード記述者と別の人が行うため、ミスが発見しやすく安心という違いがある


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- どれを選択するかは状況によって異なるが、下記３つのうちどれかの対処を実施する
  - 1.先にマージされた変更内容を取り込む
  - 2.後にマージしようとしている変更内容を取り込む
  - 3.どちらの変更内容も取り込む