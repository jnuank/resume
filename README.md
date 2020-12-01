# 職務経歴書

# Table of contents
- [基本情報](#基本情報)
- [職務経歴（概要）](#職務経歴概要)
- [資格](#資格)
- [スキル](#スキル)
- [強み](#強み)
- [やったことはないが興味があるもの](#やったことはないが興味があるもの)
- [職務経歴](#職務経歴)
  - [ハンズラボ株式会社(2018/07〜)](#201807---現在--ハンズラボ株式会社)
  - [株式会社Vヴィズリア(2016/10〜2018/06)](#201610---201806--株式会社vヴィズリア)
  - [日本サード・パーティ株式会社(2009/04〜2016/09)](#200904---201609--日本サードパーティ株式会社)
- [課外活動](#課外活動)


## 基本情報

| 項目 | |
|---|-----|
|Name|Jun Nakajima|
|Twitter|[@jnuank_](https://twitter.com/jnuank_)|
|Qiita|[@jnuank](https://qiita.com/jnuank)|
|Wantedly|[Wantedly](https://www.wantedly.com/users/64214659)|
|SpeakerDeck|[Jun Nakajima](https://speakerdeck.com/jnuank)|
|LAPRAS|[LAPRAS](https://lapras.com/public/BGBJDIV)|
|connpass|[NakajimaJun](https://connpass.com/user/NakajimaJun/)|
|Blog|[jnuank blog](https://jnuank.hatenablog.com/)|
|note|[note](https://note.com/jnuank)|
|Zenn|[Zenn](https://zenn.dev/jnuank)|


## 職務経歴（概要）

### エンジニア 2016年10月〜

- 社内用のWebアプリケーションの開発
  - Python、Django REST framework、Vue.js
- 介護施設向け入居者請求システム開発
  - bash、Python、AWS Lambda
- 客先向けの小売基幹システムの開発
  - bash
- 広告代理店向けのプロジェクト管理支援ツールの開発
  - C#、ASP.NET MVC5

### エンジニア以前 2009年4月〜2016年9月
- 医療機器(レントゲン、アンギオグラフィー、CT、MRI、US）のメンテナンス、修理、据付
- 無線LAN機器のコールセンターのオペレーター

## 資格

| 取得時期 | 名称 |
|---|-----|
|2020/10 |認定スクラムマスター(LSM)|

## スキル

### 言語
#### フロントエンド
- HTML、CSS、JavaScript
- Vue.js

#### バックエンド
- Python
- C#
- Java
- Shell(bash)

### データストア
- SQLServer、PostgreSQL

### フレームワーク
- ASP.NET MVC5、Bootstrap
- Django、Django REST framework
- Spring Boot
- jQuery
- Vuetify

### インフラ
#### AWS
- EC2、Elastic Beanstalk
- Lambda、APIGateway、SQS、SNS
- RDS、DynamoDB
- VPC、IAM、S3、CloudFormation、CloudWatch

#### オンプレ

- Apache

#### OS
- Windows、Windows Server
- macOS
- Linux(CentOS、Amazon Linux)

### その他

- GitHub、 GitHub Actions、 SVN
- Sentry、Selenium IDE、TestCafe、Cypress
- Docker
- Serverless Framework
- PlantUML
- Google Jamboard、miro

### 開発プロセスなど

- スクラム
- モブプログラミング
- ユーザーストーリーマッピング
- RDRA2.0
- [Event Storming](https://www.eventstorming.com/)
- ふりかえり
  - KPT、YWT、FDL、タイムライン、4Ls



## 強み

- チームで取り入れた方が良いと感じたモノを、なぜ必要なのかを踏まえながら、チームへ浸透させていくこと
- ぼっちで始めること、人を巻き込むこと 
- モブ/ペアプログラミングを取り入れながら、互いに教えあう文化を作っていくこと


## やったことはないが興味があるもの

- チーム全体でのドメインモデル駆動設計・開発
- Scala/Akka、リアクティブアーキテクチャ
- 関数型言語でのプロダクト開発
- 自立したチームを作ること
- エンジニア組織制度の制定、運用


## 職務経歴

### 2018/07 - 現在 : ハンズラボ株式会社

顧客向けのシステム開発の受託、親会社従業員が使用する社内システムのアプリケーション開発に従事しています。

少人数のチームで要件定義・設計・開発・テスト・運用と開発プロセスを一通り経験をしました。そこで要件を組み立て関係者と合意を取ることの重要性と、複雑な業務ロジックをどのようにコードで表現するかについて、興味を持つようになっていきました。

#### 2020/10 - 現在： 社内システムのレガシーマイグレーション
役割: DB設計（メンバー）

チーム：4人

- テキストで保管された商品のマスタ（約1億レコード）のAuroraに移行することを目標に、データベースの設計。
- プランとして、
  - まずは他のアプリケーションが参照する為の参照用テーブルを作成
    - この時に、検索の性能が悪くないか、日次でのInsert処理に耐えられるか
  - 参照用とは別に、正規化がちゃんとされた（商品の中でも、賞味期限なし、ありのやつ、医療品、コスメなどカテゴリ別に属性が違うものを仕分ける）テーブルの設計
  


#### 2020/04 - 09： 社内システムのレガシーマイグレーション
役割: Webアプリケーションエンジニア（メンバー）

チーム：4人

- bashで作られた社内システムをPython、Django REST framework、Vue.jsに置き換えを実施
- 主にバックエンド側（Python Django REST framework)を担当。進捗によってはペアプログラミングでフロントエンド側も実装。
- このときのプロジェクトの課題やどのように乗り越えていったのかは、下記スライドで登壇
  - [対話から始めていく私たち開発チームのジャーニー](https://speakerdeck.com/jnuank/dui-hua-karashi-meteikusi-tatikai-fa-timufalsesiyani)

##### チームの横断作業
- E2Eテスト(Cypress)を提案し、導入する
- [Django Rest Swagger](https://django-rest-swagger.readthedocs.io/en/latest/)を使用していたが非推奨となっていたので、 [drf-yasg](https://github.com/axnsan12/drf-yasg)に変更実施
- 他チームへTDD、drf-yasgの導入支援
- TDDやdrf-yasgでの書き方等は、他のチームに広める為の支援を実施。
- デプロイは手動でやっていたのを、GitHub Actions（手動トリガー）に変更し、デプロイ手順を簡略化することを実施。


#### 2020/01 - 2020/03： 介護施設向け入居者請求システム開発
役割: Webアプリケーションエンジニア（メンバー）

チーム:3人

- 別拠点で導入されていたbashとHTMLで作られたシステムから、必要機能を抜粋したものを抜き出して開発し、システムの導入を1ヵ月で実施。
- その後のフェーズで、外部システムとの連携があるということで、PythonとAWS Lambdaで連携用バッチを作成。
  - 外部システムから渡されるCSVファイルのフォーマットの情報があやふやだったこともあり、データを受け取るところとデータを自システム用に変換するしくみはロジックを分離
- そのときの知見をサンプルコードと合わせ記事を書いて社内共有をする
  - [CSV→スペース区切りに変換する処理でも、真面目に入出力とルールを分離をしてみる](https://qiita.com/jnuank/items/bbd46f5868d2ca723aa6)


#### 2018/07 - 2020/03： 小売基幹システムの保守運用
役割: Webアプリケーションエンジニア（メンバー　→　リーダー）

チーム：2〜3人

- 客先のオンプレサーバ(CentOS）、AWS上のサーバの保守・運用
- AWSの使用コスト削減の提案や改修案件の提案実施
- システムへの機能追加を要件定義から開発・保守運用まで実施
  - 賞味期限管理システム
  - 商談系システムの軽減税率対応
- この時から要件定義による要件の認識違いが多く発生していたのと、文書や口頭でのやりとりに非効率さを感じたため、RDRAを取り入れることにしました。
  - 要件定義で威力を発揮したので、引き継いだ既存システムの可視化にも応用しました。
  - この知見はイベントで登壇
    - [モデリングで既存システムの可視化に臨んだ話](https://speakerdeck.com/jnuank/moderingudeji-cun-sisutemufalseke-shi-hua-nilin-ndahua)
- チームリーダーとして、顧客との課題調整、新規メンバーへのオンボーディング、1on1の実施
  - 今までのキャリアで初のリーダー経験だったので、そのときの手探り感や得た知見を社内で共有
    - [「君、今日からリーダーね」と 言われた私が取り組み始めたこと](https://speakerdeck.com/jnuank/jun-jin-ri-kararidane-to-yan-waretasi-gaqu-rizu-mishi-metakoto)

#### 業務外

- bashによる入出力と計算・判断ロジックが結合した開発に疑問を持ち、正しいものを正しくつくる塾の設計コースに参加し、それを社内で共有しました。
  - [正しくつくるための設計を学ぶ\_中間報告](https://speakerdeck.com/jnuank/zheng-sikutukurutamefalseshe-ji-woxue-bu-zhong-jian-bao-gao)
  - [正しくつくるための設計を学ぶ\_最終報告](https://speakerdeck.com/jnuank/zheng-sikutukurutamefalseshe-ji-woxue-bu-zui-zhong-bao-gao)
- 自身がDDDを社内で布教したいが為に、外部講師を呼んで業務後に勉強会を主催
  - [ドメイン駆動設計のモデリングハンズオンを開催して頂きました！｜ハンズラボエンジニアブログ｜ハンズラボ株式会社](https://www.hands-lab.com/tech/entry/5391.html#more-5391)
- 社内での輪読会の主催
  - [エンジニアのためのマネジメントキャリアパス](https://www.amazon.co.jp/%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AE%E3%83%9E%E3%83%8D%E3%82%B8%E3%83%A1%E3%83%B3%E3%83%88%E3%82%AD%E3%83%A3%E3%83%AA%E3%82%A2%E3%83%91%E3%82%B9-%E2%80%95%E3%83%86%E3%83%83%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%89%E3%81%8B%E3%82%89CTO%E3%81%BE%E3%81%A7%E3%83%9E%E3%83%8D%E3%82%B8%E3%83%A1%E3%83%B3%E3%83%88%E3%82%B9%E3%82%AD%E3%83%AB%E5%90%91%E4%B8%8A%E3%82%AC%E3%82%A4%E3%83%89-Camille-Fournier/dp/4873118484)
  - [チーム・ジャーニー](https://www.amazon.co.jp/%E3%83%81%E3%83%BC%E3%83%A0%E3%83%BB%E3%82%B8%E3%83%A3%E3%83%BC%E3%83%8B%E3%83%BC-%E9%80%86%E5%A2%83%E3%82%92%E8%B6%8A%E3%81%88%E3%82%8B%E3%80%81%E5%A4%89%E5%8C%96%E3%81%AB%E5%BC%B7%E3%81%84%E3%83%81%E3%83%BC%E3%83%A0%E3%82%92%E3%81%A4%E3%81%8F%E3%82%8A%E3%81%82%E3%81%92%E3%82%8B%E3%81%BE%E3%81%A7-%E5%B8%82%E8%B0%B7-%E8%81%A1%E5%95%93/dp/4798163635/ref=sr_1_2?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&dchild=1&keywords=%E3%83%81%E3%83%BC%E3%83%A0%E3%82%B8%E3%83%A3%E3%83%BC%E3%83%8B%E3%83%BC&qid=1603429352&s=books&sr=1-2)

### 2016/10 - 2018/06 : 株式会社Vヴィズリア

この時点でエンジニアとしての経験がなかった為、一度現場経験を積んでおきたいと思い、SES業界で働くことにしました。

C#、ASP.NET MVCでの開発経験を積み、その後半年間以上Excelでの詳細設計に従事しました。

100人規模（遠隔オフィス含む）のウォーターフォール開発で度重なる要件・仕様変更を経験し、もっとより良い開発手法や設計手法があるのではないかと思い、

アジャイルな開発や受託ではなくて自社で内製をやっている環境が良いと思い、転職をしました。

#### 2017/04 - 2018/06： 広告代理店向けのプロジェクト管理支援ツールの開発
役割：アプリケーションエンジニア（メンバー）

- C#、ASP.NET MVCを利用した開発と、基本・詳細設計を担当しました。
- 広告代理店という業界特有のロジックに戸惑いながらも、近くにいた要件定義チームと何度も意見を交わし設計を進めていきました。

#### 2016/10 - 2017/03： スマートフォンテスター
役割：テスター

- スマートフォンの不具合修正されたアプリケーションをテストすることを担当しました。

#### 業務外

- 会社で毎週土曜日にC#の勉強会を開催していましたので参加
  - 後に新人を教えるメンター役となりました。

### 2009/04 - 2016/09 : 日本サード・パーティ株式会社

専門卒業後に新卒として入社し、医療機器のメンテナンス、修理、据付を業務委託で請け負っていました。

レントゲン・MRI・CTなどの専門性の高い技術・知識を学ぶことや、訪問先で顧客対応は勉強になりましたが、

同じ会社・部署にいても一人で仕事をすることが多く、もっとチームで何か一つのモノやサービスを作って届ける仕事をしたいと思い、エンジニアとして転職することにしました。


## 課外活動

### 運営に携わっているコミュニティ
- [DDD-Community-Jp](https://ddd-community-jp.connpass.com/)
  - 主にDDDに関する輪読会を主催する事が多いです
    - 実践ドメイン駆動設計(2019/10〜2020/07)
    - エリック・エヴァンスのドメイン駆動設計(2020/08〜)
  - 架空の会議室予約システムのドメインをモデリングし、実際にC#で実装をしてみる勉強会をやっています


### 直近の企画・運営歴
| Date | Event | 
|---|-----|
|2020/08/08〜現在|[エリック・エヴァンスのドメイン駆動設計 輪読会](https://ddd-community-jp.connpass.com/event/185352/)|
|2020/08/01|[TDD Boot Camp 2020 Online \#1 ](https://tddbc.connpass.com/event/181973/)|

### 過去の登壇資料

| Date | Event | Slide |
|---|-----|-----|
|2020/08/07|[カイゼンの旅、チームの旅。現場の軌跡を語ろうライトニングトーク回 \- DevLOVE](https://devlove.doorkeeper.jp/events/109556?utm_campaign=event_109556_130263&utm_medium=email&utm_source=not_replied_message)| [対話から始めていく私たち開発チームのジャーニー](https://speakerdeck.com/jnuank/dui-hua-karashi-meteikusi-tatikai-fa-timufalsesiyani) |
|2019/12/14|[レガシーをぶっつぶせ。現場でDDD！2nd 「インプット＜アウトプット！」第一部 ](https://genbade-ddd.connpass.com/event/156060/)|[モデリングで既存システムの可視化に臨んだ話](https://speakerdeck.com/jnuank/moderingudeji-cun-sisutemufalseke-shi-hua-nilin-ndahua) |

