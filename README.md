# -VPS-LAMP-
さくらVPS上にLAMP環境を構築し、WordPressのセットアップまで行ったハンズオン学習記録です。

---
## 使用技術

- Linux （Rocky Linux）
-　Apache
-　MariaDB
-　PHP
-　WordPress

---

## 学習の流れ
本プロジェクトでは、以下の順序でLAMP環境構築およびWordPress導入を行いました。
01. さくらVPS準備・接続(SSH) 
02. Apacheサーバー構築(インストール&起動)
03. Apache Basic認証の設定と動作確認
04. PHPのインストールとApacheとの連携確認
05. MariaDBのインストールと接続確認
06. WordPressのダウンロードとインストール
07. WordPressログイン画面の表示・管理画面へのアクセス

---

## スクリーンショット

### Apache Basic認証の動作確認

ApacheでBasic認証を設定し、アクセス時にユーザー名とパスワードの入力が求められることを確認しました。
![Apache Basic Auth Test](images/apache-basic-auth-test.png)
