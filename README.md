# README
＃　Ruby on Railsチュートリアルのサンプルアプリケーション
これはチュートリアルを使ってつくられたアプリケーションです

＃＃　使い方
このアプリケーションを動かす場合は、まずリポジトリを手元にクローンしてください。
次に必要になるコマンドRuby Gemsをインストールします。
````
$ bundle install --without production
````
その後、データベースをマイグレーションします。
```
$rails db:migrate
```
テストが無事に通ったら、Railsサーバーを立ち上げる準備が整っています
```
$rails servers
```
詳しくはruby on railsのチュートリアルを参考にしてください。





This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
