# サイバー攻撃被害に係る情報の公開情報まとめ

サイバー攻撃被害に遭ってしまった組織が、情報共有または被害公表のために公開している情報をまとめます。
網羅度は低いです。

守る側の視点で参考にし易いように、サイバー攻撃被害に遭ってしまった原因を分かりやすくしたいと思います。このため、 MITRE ATT&CK の TA0001 Initial Access のなかの、どの Techniques に該当するかを想定して整理します。

## TA0001 Initial Access

### T1190 Exploit Public-Facing Application
Known Vulnerability  
* 2022/12/27 社会医療法人生長会 [サイバー攻撃被害によるシステム障害のお知らせ（第 2 報）](https://www.seichokai.or.jp/system/upload/bellkitchen/news/1672125435_020263400.pdf)
* 2023/4/3 新潟医療福祉大学 [本学ウェブサイトの改ざんに関するお詫びと復旧のご報告](https://www.nuhw.ac.jp/n/topics/10664/)
* 2023/6/22 志布志市 [本市が運営する「志布志市ふるさと納税特設サイト」への不正アクセスによる個人情報漏えいに関するお詫びとお知らせ](https://www.city.shibushi.lg.jp/soshiki/5/22233.html)  
* 2023/7/4 株式会社シーアイエス [当社サーバーへの不正アクセスについて（第２報）](https://www.cisjp.com/news/detail/post-20200331.html)
* 2023/7/7 日本コンクリート工業株式会社 [【状況報告】ランサムウェア被害の調査結果について](https://www.ncic.co.jp/wp/wp-content/uploads/2023/07/230707.pdf)
* 2023/10/11 株式会社マウンハーフジャパン [「MHJストア」への不正アクセスによる個人情報漏えいに関するお詫びとお知らせ](https://www.mhjcom.jp/n-news/22819.html)
* 2023/11/02 一般社団法人共同通信社 [不正アクセスによる職員等の個人情報漏えいの恐れのお知らせとおわび](https://www.kyodonews.jp/information/2023/post-108.html)

Zero-day Vulnerability
* 2023/8/4 内閣官房内閣サイバーセキュリティセンター [内閣サイバーセキュリティセンターの電子メール関連システムからのメールデータの漏えいの可能性について](https://www.nisc.go.jp/news/20230804.html)

Unique Vulnerability
* 2022/2/28 株式会社メタップスペイメント [不正アクセスによる情報流出に関するご報告とお詫び](https://www.metaps-payment.com/company/20220228.html)
* 2023/10/13 株式会社リコー [不正アクセスによる情報流出に関するお知らせとお詫び](https://jp.ricoh.com/info/notice/2023/1013_1)

Misconfiguration
* 2022/2/7 新潟県 [新潟県土木防災情報システムのメールサーバを利用され、不正メールが送信された件について、調査と対策を実施しました。](https://www.pref.niigata.lg.jp/sec/kasenkanri/20220207-bousaisystem.html)
* 2023/3/27 住友不動産株式会社 [「住友不動産のふれあい＋Ｓ」システムへの第三者によるアクセスについて](https://www.sumitomo-rd.co.jp/uploads/20230327_01.pdf)
* 2023/11/8 カシオ計算機株式会社 [ClassPad.net不正アクセスによる個人情報漏えいの経緯と対策状況について](https://classpad.net/jp/news/041/)
* 2023/11/28 積水ハウス株式会社 [システム開発用クラウドサーバーのセキュリティ設定不備によるお客様情報等の外部漏えいについて
](https://www.sekisuihouse.co.jp/company/topics/library/2023/20231128/20231128.pdf)

### T1566 Phishing
* 2023/3/23 福岡県暴力追放運動推進センター [お知らせとお詫び](http://www.fukuoka-boutui.or.jp/news/wp-content/uploads/2023/03/%E3%81%8A%E7%9F%A5%E3%82%89%E3%81%9B%E3%81%A8%E3%81%8A%E8%A9%AB%E3%81%B3.pdf)
* 2023/3/31 株式会社地元カンパニー [不正アクセス発生に関するお詫びとご報告](https://www.jimo.co.jp/administration/wp-content/uploads/2023/03/20230331_news_unauthorized_access.pdf)
* 2023/6/20 青梅市 [青梅市ファミリー・サポート・センターのパソコンへの不正アクセスによる個人情報の漏えいのおそれのある事故の結果について](https://www.city.ome.tokyo.jp/soshiki/34/68110.html)
* 2023/11/29 京都教育大学附属桃山中学校 [サポート詐欺による公用パソコン遠隔操作被害について](https://momochu.kyokyo-u.ac.jp/index/pickup/%E3%82%B5%E3%83%9D%E3%83%BC%E3%83%88%E8%A9%90%E6%AC%BA%E3%81%AB%E3%82%88%E3%82%8B%E5%85%AC%E7%94%A8%E3%83%91%E3%82%BD%E3%82%B3%E3%83%B3%E9%81%A0%E9%9A%94%E6%93%8D%E4%BD%9C%E8%A2%AB%E5%AE%B3%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6.pdf)

### T1566.001 Phishing: Spearphishing Attachment
* 2023/10/24 東京大学 [東京大学大学院総合文化研究科・教養学部への不正アクセスによる情報流出について](https://www.u-tokyo.ac.jp/focus/ja/press/z0109_00952.html)

### T1199 Trusted Relationship
* 2023/11/27 LINE ヤフー株式会社 [不正アクセスによる、情報漏えいに関するお知らせとお詫び](https://ly.swcms.net/ja/ir/news/auto_20231127594672/main/0/link/Notice%20and%20apology%20regarding%20information%20leakage%20due%20to%20unauthorized%20access_JP.pdf)

### T1078 Valid Accounts
* 2023/6/2 東京都 [個人情報の不正閲覧・取得及び漏えいについて](https://www.metro.tokyo.lg.jp/tosei/hodohappyo/press/2023/06/02/12.html)
* 2023/9/28 兼松株式会社 [元従業員の逮捕について](https://www.kanematsu.co.jp/press/files/press/20230928_release.pdf)
* 2023/10/20 独立行政法人日本学生支援機構 [委託事業者における個人情報の漏洩事案の発生について](https://www.jasso.go.jp/news/1208184_1579.html)
* 2023/12/1 仙台市 [懲戒処分の公表について](https://www.city.sendai.jp/somu-jinji-jinji/kisha/20231201.html)

### T1078.001 Valid Accounts: Default Accounts
* 2023/3/31 国土交通省 [配信を停止している簡易型河川監視カメラの再開について](https://www.mlit.go.jp/report/press/mizukokudo03_hh_001168.html)

## その他
* [「サイバー攻撃被害に係る情報の共有・公表ガイダンス（案）」に対する意見募集の結果及び「サイバー攻撃被害に係る情報の共有・公表ガイダンス」の公表](https://www.meti.go.jp/press/2022/03/20230308006/20230308006.html)
