## 概要
こちらは**パーソナルデータ連携モジュール**の開発者コミュニティサイトです。
**パーソナルデータ連携モジュール**とは、サービス事業者が保有しているパーソナルデータを組織をまたがって共有できるトラスト層／データ連携層の機能群です。

## 活動情報
### 開発活動
プロダクトの状況は、
[メンテナンス用プロジェクト](https://github.com/orgs/Personal-Data-Linkage-Module/projects/1)
で管理されています。
バグや質問への対応状況を確認することができます。

### 普及活動
本コミュニティでは、エリア・データ連携基盤の実装を目指す自治体様および関連事業者様を対象にセミナーを開催しています。
セミナー詳細は
[セミナー情報 | 一般社団法人データ社会推進協議会(DSA)](https://github.com/Personal-Data-Linkage-Module/.github/assets/87103717/e25e809e-0344-498c-a6b7-f04de6195220)
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

|No. |Repository Name |Description |
|:-|:-|:-|
|1 |pxr-linkage |複数のモジュールを連携して利用するために必要なファイルを管理します |
|2 |pxr-{}-service |単体モジュールのソースコードや設定ファイルを管理します |
|3 |docs |作成中 |
|4 |test |作成中 |

## 連絡先
パーソナルデータ連携モジュールの開発に貢献したい方、コミュニティの運営に参加したい個人・団体の方は、
[Code for Japan(Slack)](https://www.code4japan.org/activity/community)
に記載の手順でワークスペースにご参加ください。
認証認可・同意管理については、#proj-cityos_auth というチャンネルでやり取りしているので、そちらにご参加をお願いします。

エリア・データ連携基盤に関するお問合せは、
[DSA(エリア・データ連携基盤に関するお問合せ)](https://data-society-alliance.org/area-data/contact/)
フォームからご連絡お願いします。

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
