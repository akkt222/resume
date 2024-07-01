# 職務経歴書

## 略歴
| 年月 | 略歴 |
| --- | --- |
| 2018年3月 | 　成蹊大学文学部英米文学科卒業 | 
| 2018年4月 | 　株式会社NTTデータビジネスブレインズ　入社 | 
| 2020年8月 | 　株式会社NTTデータビジネスブレインズ　退職 | 
| 2020年9月 | 　株式会社ギフティ　入社 | 
| 2022年8月 | 　株式会社ギフティ　退職 | 
| 2022年9月 | 　株式会社シックスティーパーセント　入社 | 
| 2023年6月 | 　株式会社シックスティーパーセント　退職 | 
| 2023年8月 | 　株式会社viviON 入社 | 

## スキルセット
### 言語・フレームワーク
|言語・フレームワーク|経験年数|レベル(主観)|
| --- | --- | --- |
| Ruby, Ruby on Rails | 4年 | 人に教えられる |
| Go | 1.5年 | 人に教えられる |
| JavaScript | 2年 | 少し使える |
| TypeScript | 半年 | 少し使える |
| React | 半年 | 少し使える |

### その他の技術
- AWS
  - Elastic Beanstalk
  - copilot
  - Code Build, Code Pipeline
  - App Mesh
  - その他WAF, S3, RDS, EC2, ECSなど一般的なもの
- GCP
  - Cloud Run
- gRPC
- GraphQL
- terraform
- Docker
- Sentry
- GitHub Actions
- Cricle CI



## 職務経歴

### 株式会社NTTデータビジネスブレインズ (2018年4月-2020年8月)

- NTTデータ社と日本板硝子社の合弁会社です
- 取引先企業の業務基幹システムであるSAPのFI, COモジュールの運用・導入を担当しました
- プログラミングはABAPやSQLを少し触る程度でプログラマー職ではありませんでしたが、通訳・翻訳の業務を経験したこと、また取引先企業の海外ブランチと協業することが多かったことから、元々得意だった英語の能力が向上し、英語で業務を遂行することが出来るようになりました


### 株式会社ギフティ　(2020年9月-2022年8月)
- 大手カフェチェーンのギフト券のような、デジタルギフトと言われる商材の発行・流通をしている企業です
- この時から職業プログラマーとして就業しております
- 主にモノリシックな Railsアプリケーションの開発・運用に従事しました。他、テクニカルサポートのような役割や新卒向けの課題作成やインターンのメンタリングなどに従事しました。担当していたプロジェクトは主に以下のふたつになります

#### 法人向けキャンペーンプラットフォーム
- SNSのアカウントやショートメールなどを用いていわゆるインスタントウィンを提供するシステムです

- チーム構成
  - エンジニア3名
  - PdM 1名
- 使用技術
  - Ruby
  - Ruby on Rails
  - JavaScript
  - jQuery
  - Stimulus
  - Semantic UI
  - MySQL
  - CircleCI
  - Docker
  - AWS ElasticBeanstalk
  - AWS copilot
  - terraform
  - ansible
  - Cloud Formation
  - LINE, Twitter, Vpass, アクリート、Survey Monkey等の外部API

<details>
<summary>苦労した点</summary>

このプロダクトはプッシュ通知を起点にスパイクアクセスが発生することが多く、普段は比較的静かなものの、急に分間10万件を超えるwriteが走り始める特徴がありました。そのような状況でもサービスを落とさないような様々な工夫が求められました。具体的には外部APIなどの技術選定の見直しや、オートスケーリングの対応、また必要に応じてデータベースのフェイルオーバーを行うことを求められました。

</details>


#### 店舗向けデジタルギフト配布システム
- 飲食店やイベント会場などに設置したタブレット端末を利用してユーザーがデジタルギフトを受け取るためのシステムです

- チーム構成
  - エンジニア3名
  - PdM 1名
- 使用技術
  - Ruby
  - Ruby on Rails
  - tailwind CSS
  - MySQL
  - Docker
  - AWS copilot
  - Code Pipeline

<details>
<summary>苦労した点</summary>

手動で行われていたデプロイ作業を自動化することで、リリース頻度を向上させました。ビジネス要件からリリース時にPdMの確認を挟みたいという要件があったため、承認フローを差し込みやすいCode Pipelineを選定することで、これを実現しました。


</details>

### 株式会社シックスティーパーセント　(2022年9月-2023年6月)
- アジアのファッションブランドだけを集めた越境ECサイト、『60%』を運営しているスタートアップ企業です。
- Rails, React/TypeScript, Golangを用いたアプリケーションの開発者としてのロールと、スクラムマスターとしてのロールに従事しました。担当していたプロジェクトは主に以下の二つになります


### EC出品者・配送業者向けの管理システム
- 出品される商品や配送状況を管理するためのシステムです
- チーム構成
  - エンジニア3名
- 使用技術
  - Ruby
  - Ruby on Rails
  - React
  - TypeScript
  - PostgreSQL
  - GraphQL
  - Cloud Run
  - heroku
  - kubernetes
  - Docker
  - Shopify


<details>
<summary>苦労した点</summary>

業務委託メンバーのみで開発されてきたシステムであったことから、設計が行われておらずレガシー化している、テストを書く文化が無いなどの問題がありました。Reactの経験がほとんど無かったためキャッチアップしつつ、リファクタリングやテスト文化の布教を行いました。

またスクラムマスターとしてスクラムを導入し、ベロシティの算出が出来るようにしました。

</details>

#### ソーシャルログイン・通知基盤システム
- OAuthにてSNSアカウントを連携してもらい、プッシュ通知などに活用するためのシステムです。

- チーム構成: エンジニア1名

- 使用技術
  - Golang
  - chi
  - gorm
  - Cloud Run
  - Redis
  - PostgreSQL

<details>
<summary>苦労した点</summary>

会社・私自身にGolangの知見が無い中、試行錯誤しながら一人で開発しました。納期もタイトでしたが、業務と並行して学習を行いました。
この開発によって会社の技術ポートフォリオにGolangを加えることが出来ました。

</details>

### 株式会社viviON (2023年8月-現在)
- 同人作品販売プラットフォーム『DLsite』を中心に、クリエイター支援サービス『ci-en』『GENSEKI』などの開発を行なっている企業です。
- 既存サービスの多くはモノリシックなPHPアプリケーションになっているのですが、それらを主にGolangを用いてマイクロサービス化していくチームに所属しています。

- チーム構成
  - エンジニア4名
  - ディレクター1名

- 使用技術
  - Golang
  - gRPC
  - App Mesh
  - Code Pipeline
  - Docker
  - terraform

### 株式会社SAMANSA（2024年1月〜現在）
- 社員ではなく業務委託での参加です。
- 短編映画だけを集めたNetflixのようなアプリ「SAMANSA」の運営を行なっている企業です。

- チーム構成
  - エンジニア若干名
  - PdM一人

- 使用技術
  - Ruby on Rails
  - GraphQL
  - terraform
  - Code Pipeline
  - OpenSearch