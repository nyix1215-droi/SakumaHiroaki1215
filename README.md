# AWS Cloud Engineer Portfolio

## 概要
AWS無料枠を活用し、EC2上にNginx Webサーバーを構築しました。
S3、IAM、CloudWatchを組み合わせ、クラウドインフラの基本設計・構築・監視を実装したポートフォリオです。

# AWS Cloud Portfolio

## 🌐 デモサイト
http://3.26.5.118

※現在稼働中のWebサーバーです

---

## 📌 概要
AWS無料枠を利用してクラウド環境を構築しました。

## 🏗️ 構成
- EC2（Amazon Linux）
- Nginx
- S3
- IAM
- CloudWatch

## 💡 ポイント
- セキュリティグループでアクセス制御
- IAMロールで安全にS3アクセス
- CloudWatchで監視

## 構成
- Amazon EC2
- Amazon Linux 2023
- Nginx
- Amazon S3
- IAM Role
- CloudWatch
- Security Group

## 実装内容
- EC2インスタンス作成
- Linuxサーバー初期設定
- Nginxインストール
- 静的Webサイト公開
- セキュリティグループ設定
- S3バケット作成
- CloudWatchメトリクス確認
- GitHubで構築手順を公開

## 工夫した点
- RDSを使わず、無料枠内で実装
- IAMロールを使い、アクセスキーをEC2に直接置かない設計
- CloudWatchで監視まで含めた構成

## 学んだこと
- Linux基本操作
- Webサーバー構築
- AWSネットワーク基礎
- IAM権限管理
- 監視の基本

## 設計意図

- EC2を使用した理由：
  → Linuxサーバー構築スキルを身につけるため

- Nginxを採用した理由：
  → 軽量で実務利用が多いため

- S3を使用した理由：
  → 静的ファイルを分離しスケーラビリティを意識

- IAMロールを使用した理由：
  → セキュリティ向上のため

**## トラブルと解決

問題：
ブラウザでEC2にアクセスできなかった

原因：
セキュリティグループでポート80が閉じていた

解決：
HTTP（80）を0.0.0.0/0で許可
