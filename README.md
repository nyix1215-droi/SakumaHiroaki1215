# AWS Cloud Engineer Portfolio

## 概要
AWS無料枠を活用し、EC2上にNginx Webサーバーを構築しました。
S3、IAM、CloudWatchを組み合わせ、クラウドインフラの基本設計・構築・監視を実装したポートフォリオです。

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
- 面接で説明しやすいシンプルな構成

## 学んだこと
- Linux基本操作
- Webサーバー構築
- AWSネットワーク基礎
- IAM権限管理
- 監視の基本
