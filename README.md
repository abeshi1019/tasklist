# README

#　概要
タスクの名前と詳細を入力し、一覧として表示するtodoアプリ。

本アプリはマイナビより出版されている「現場で使えるRuby on Rails5速習実践ガイド（５．２対応）」のハンズオンである。

本書の内容に理解を深めながら以下を学習している。


#　学習点
##　ログイン機能
gem 'devise'を使用せず実装。
以下の
- gem 'bcrypt'によるパスワードのｄｉｇｅｓｔ変換。
- 管理者権限の作成（admin）
  （管理者を作成するにはコンソールでadminの値を１にして生成してください）

##　テスト
'RSpec','Capybara','FactoryBot'を用いたテストの作成

##　メーラーの実装
タスクを保存した際にtaskleaf@example.comよりメールが送信される。（現状デフォルトでuser@example.comに送信される。）

##　Active Storageによる画像の添付
タスク保存時に画像を添付することが可能。

##　タスクのCSVのインポート/エクスポート
トップページにボタンを設置。CSVによるタスクのインポート/エクスポートが可能

