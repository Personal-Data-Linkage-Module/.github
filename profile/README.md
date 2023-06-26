## 概要
こちらは**パーソナルデータ連携モジュール**の開発者コミュニティサイトです。
**パーソナルデータ連携モジュール**とは、サービス事業者が保有しているパーソナルデータを組織をまたがって共有できるトラスト層／データ連携層のAPI群です。

## 活動情報
### 開発活動
プロダクトの状況は、
[メンテナンス用プロジェクト](https://github.com/orgs/Personal-Data-Linkage-Module/projects/1)
で管理されています。
バグや質問への対応状況を確認することができます。
また、本コミュニティは、運営および開発メンバーを随時募集しています。
メンバーとして参加を希望する方は、
[メンバー加入希望チャット](https://github.com/orgs/Personal-Data-Linkage-Module/discussions/new?category=%E3%83%A1%E3%83%B3%E3%83%90%E3%83%BC%E5%8A%A0%E5%85%A5%E5%B8%8C%E6%9C%9B)
から参加希望のご連絡をお願いします。


### 普及活動
[一般社団法人データ社会推進協議会 (DSA) ](https://data-society-alliance.org/)
にて、
本モジュールを利用してエリア・データ連携基盤の実装を目指す自治体様および関連事業者様を対象に、セミナーを開催しています。
セミナーの詳細情報は
[セミナー情報 | 一般社団法人データ社会推進協議会(DSA)](https://data-society-alliance.org/area-data/seminar)
をご確認ください。

## コントリビューションガイド
### バグの報告
コードのバグを報告する場合、`bug`ラベルを付与したIssueを発行してください。ドキュメントの修正を含む場合には、`documentation`ラベルも付与してください。

### 新機能の提案
新たな機能を提案する場合、`enhancement`ラベルを付与したIssueを発行してください。

### 質問
新規に質問する場合、`question`ラベルを付与したIssueを発行してください。

### Git ブランチルール
Pull Requestを送る場合、git-flowをベースとした以下のルールに従ってブランチをpushしてください。
また、Pull Requestを送る前には必ずIssueを発行してIssueと紐づけてください

* `feature/#issue-number` 新たな機能を開発するために使います。**開発者**は**develop**ブランチから分岐して開発を始めます。
* `bugfix/#issue-number` リリース済バージョンのバグを修正するために使います。**開発者**は**develop**ブランチから分岐して開発を始めます。

## リポジトリ構成

**リポジトリ一覧表**
|No. |Repository Name |Description |
|:-|:-|:-|
| 1 |pxr-linkage |複数のモジュールを連携して利用するために必要なファイルを管理します。 |
| 2 |pxr-operator-service |オペレータ (運営メンバー, 個人)のアカウント管理と認証を行うoperatorモジュールのソースコードや設定ファイルを管理します。 |
| 3 |pxr-catalog-service |My-Condition-Data[^1]カタログの管理を行うcatalogモジュールのソースコードや設定ファイルを管理します。 |
| 4 |pxr-catalog-update-service |My-Condition-Data[^1]カタログのうち特殊な手順で管理を行うcatalog-updateモジュールのソースコードや設定ファイルを管理します。 |
| 5 |pxr-block-proxy-service |各サービスへproxyを行うblock-proxyモジュールのソースコードや設定ファイルを管理します。 |
| 6 |pxr-notification-service |オペレータへ通知や承認要求を行うnotificationモジュールのソースコードや設定ファイルを管理します。 |
| 7 |pxr-book-manage-service |My-Condition-Book[^2]の管理を行うbook-manageモジュールのソースコードや設定ファイルを管理します。 |
| 8 |pxr-book-operate-service |My-Condition-Book[^2]へデータの蓄積と共有を行うbook-operateモジュールのソースコードや設定ファイルを管理します。 |
| 9 |pxr-identity-verificate-service |本人性の確認を行うidentity-verificateモジュールのソースコードや設定ファイルを管理します。 |
|10 |pxr-ctoken-ledger-service |CToken台帳の管理を行うctoken-ledgerモジュールのソースコードや設定ファイルを管理します。 |
|11 |pxr-local-ctoken-service |Local-Ctoken-Storeの更新とCToken台帳への差分送信を行うcertification-authorityモジュールのソースコードや設定ファイルを管理します。 |
|12 |pxr-certification-authority-service |証明書の生成や取得、検証を行うcertification-authorityモジュールのソースコードや設定ファイルを管理します。 |
|13 |pxr-certificate-manage-service |証明書の管理を行うcertificate-manageモジュールのソースコードや設定ファイルを管理します。 |
|14 |pxr-access-control-manage-service |API間のアクセス設定とデータ操作定義の確認、APIトークンの生成指示を行うaccess-control-manageモジュールのソースコードや設定ファイルを管理します。 |
|15 |pxr-access-control-service |APIトークンの生成と照合を行うaccess-controlモジュールのソースコードや設定ファイルを管理します。 |
|16 |pxr-binary-image-service |バイナリファイルのアップロードとダウンロードを行うbinary-manageモジュールのソースコードや設定ファイルを管理します。 |

[^1]: 蓄積されるパーソナルデータ
[^2]: 個人が保持するMy-Condition-Dataの集合体

## 連絡先
パーソナルデータ連携モジュールの開発に貢献したい方、コミュニティの運営に参加したい個人・団体の方は、
[こちらのチャット](https://github.com/orgs/Personal-Data-Linkage-Module/discussions/new?category=%E3%83%A1%E3%83%B3%E3%83%90%E3%83%BC%E5%8A%A0%E5%85%A5%E5%B8%8C%E6%9C%9B)
へご連絡頂くとともに
[Code for Japan (Slack) ](https://www.code4japan.org/activity/community)
に記載の手順でslackのワークスペースへご参加ください。
認証認可・同意管理については、#proj-cityos_auth というチャンネルでやり取りしているので、そちらにご参加をお願いします。

エリア・データ連携基盤に関するお問合せは、
[DSA (エリア・データ連携基盤に関するお問合せ) ](https://data-society-alliance.org/area-data/contact/)
フォームからご連絡お願いします。

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
