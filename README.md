# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか?
リモートリポジトリとは,ネット上にソースコードを管理するシステムの事であり,それに対してローカルリポジトリとはPC上にソースコードを管理するシステムの事である。


## プッシュとマージの違いは何でしょうか?
pushはローカルリポジトリの内容をリモートリポジトリに反映させるものであり,mergeとはbranchの変更点を他のbranchに反映させるためのものである。


## コミットとプッシュの違い
commitはローカルリポジトリの変更内容を保存しておくものであり,過去に変更した地点から作業を開始することができる点がpushとの違いである。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
変更点をわかりやすく簡潔に書くこと。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
ローカルからのフローでは,ローカルのmaster(main)の変更内容が保存されているのに対して,プルリクエストの方では,ローカルのmaster(main)に変更点が更新されない点が違いである。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
先にマージされた内容を取り込む,後にマージされた内容を取り込む,両方とも取り込むの3つがあり,状況に応じてコードを書いた人と相談しながら対処するべきである。