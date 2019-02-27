# Overview

このワークショップは、AWS セキュリティサービスを理解し、そのサービスを使用して貴社環境の脅威を識別および修復する方法を学習する手助けとなるように設計されています。Amazon GuardDuty、Amazon Macie、Amazon Inspector、AWS Security Hub などのサービスを使用します。これらのサービスを使用して、攻撃中および攻撃後の脅威を調査し、通知と修復パイプラインを設定し、追加的な保護策を講じて、貴社環境のセキュリティを改善する方法を学習します。

* **レベル**: 中級
* **時間**: 2 ～ 3 時間
* **<a href="https://www.nist.gov/cyberframework/online-learning/components-framework" target="_blank">CSF 機能</a>**: 検出、対応、復旧
* **<a href="https://d0.awsstatic.com/whitepapers/AWS_CAF_Security_Perspective.pdf" target="_blank">CAF 構成要素</a>**: Detective, Responsive
* **<a href="https://awssecworkshops.com/getting-started/" target="_blank">前提条件</a href>**: AWS アカウント、管理者権限を持つ IAM ユーザー

## シナリオ

あなたの会社はクラウドに慣れておらず、最近インフラストラクチャーを試験的にリフトアンドシフトで移行しました。あなたはシステム管理者であり、AWS 環境のセキュリティ監視を任されています。その作業の一環として、その環境におけるセキュリティイベントへの対応も担当しています。

## アーキテクチャ

このワークショップ用に、us-west-2 リージョンで単一のインスタンスが設定されています。これは試験的な「リフトアンドシフト」移行であり、アプリケーションは冗長化していません。そのため、単一の公開ウェブサーバーとなっています。このウェブサーバーは、Elastic Network Interface を通じてインターネットゲートウェイにアクセスできます。顧客は、Elastic Network Interface を指す DNS エントリを通じてウェブサーバーにアクセスします。静的コンテンツを S3 バケットに保管し、ウェブサーバーからのアクセスに VPC S3 エンドポイントゲートウェイを使用します。

![Architecture](./images/diagram-basic-arch.png "Workload Architecture")

## プレゼンテーションデッキ
[ワークショップのプレゼンテーションデッキ](./threat-detect-workshop-presentation.pdf)

## リージョン
このワークショップには、us-west-2 (Oregon) リージョンを使用してください。

## モジュール

1. [環境構築と設定](./01-environment-setup.md)
2. [攻撃シミュレーション](./02-attack-simulation.md) 
3. [検知と対応](./03-detection-and-remediation.md) 
4. [レビューとディスカッション](./04-review-and-discussion.md)

合計時間: ± 2 時間