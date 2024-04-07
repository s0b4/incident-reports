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
* 2023/12/07 株式会社徳岡 [弊社が運営する「ボルドープリムール」「ボンルパ」への不正アクセスによる個人情報漏えいに関するお詫びとお知らせ](https://tokuoka.jp/upload/pdf/upPdf/20231206174829_20231207.pdf)
* 2023/12/15 株式会社マルミミ [不正アクセスによる個人情報漏洩のお詫びとご報告](https://www.marumimi.co.jp/news?id=11692086)

Zero-day Vulnerability
* 2023/8/4 内閣官房内閣サイバーセキュリティセンター [内閣サイバーセキュリティセンターの電子メール関連システムからのメールデータの漏えいの可能性について](https://www.nisc.go.jp/news/20230804.html)
* 2023/10/19 独立行政法人国立科学博物館 [電子メール関連システムへの不正アクセスに伴う個人情報等漏えいのおそれについて](https://www.kahaku.go.jp/information/pdf/kahaku_20231019.pdf)
* 2023/11/7 国立環境研究所 [国立環境研究所が運用するオンラインストレージサービス（Proself）への不正アクセスについて](https://www.nies.go.jp/whatsnew/2023/20231030-1.html)
* 2023/11/17 独立行政法人日本学術振興会 [不正アクセスによる個人情報漏えいのお詫びとご報告](https://www.jsps.go.jp/file/storage/j-news/2023/oshirase_20231117.pdf)

Unique Vulnerability
* 2022/2/28 株式会社メタップスペイメント [不正アクセスによる情報流出に関するご報告とお詫び](https://www.metaps-payment.com/company/20220228.html)
* 2023/10/13 株式会社リコー [不正アクセスによる情報流出に関するお知らせとお詫び](https://jp.ricoh.com/info/notice/2023/1013_1)
* 2023/12/19 朝日新聞社 [個人情報流出(本年9月6日判明)に関する調査結果のお知らせ](https://www.asahi.com/corporate/info/15087850)
* 2023/12/15 サービス等生産性向上IT導入支援事業費補助金 [事務局における個人情報を含むIT導入支援事業者情報の流出についてのお詫びとご報告](https://it-shien.smrj.go.jp/news/10158)

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
* 2023/11/30 株式会社シグマ [弊社Instagram公式アカウントに関するお詫びとご報告](https://www.sigma-global.com/jp/news/2023/11/30/231130/)

### T1566.001 Phishing: Spearphishing Attachment
* 2023/10/24 東京大学 [東京大学大学院総合文化研究科・教養学部への不正アクセスによる情報流出について](https://www.u-tokyo.ac.jp/focus/ja/press/z0109_00952.html)

### T1195 Supply Chain Compromise

企業が利用しているサービス側が不正アクセスを受けたケースは、 "T1195 Supply Chain Compromise" に整理するのか、それとも "T1199 Trusted Relationship" に整理するのか迷いました。
現状の MITRE ATTA&CK では、どちらにも捉えられるように思います。 

一旦は "T1195 Supply Chain Compromise" に整理しておきます。
いずれ見直すかもしれません。  

* 2023/10/19 千葉県教育委員会 [不正アクセスによる個人情報漏えいについて](https://www.pref.chiba.lg.jp/kyouiku/shidou/giga/2023casiorouei.html)
* 2023/3/10 京セラ株式会社 [当社利用サービスへの不正アクセスについて](https://www.kyocera.co.jp/newsroom/information/2023/002149.html)

### T1199 Trusted Relationship

ビジネスサプライチェーン攻撃 という名称で説明されていることもあるようです。 
MITRE ATTA&CK では "T1199 Trusted Relationship" の Techniques が最も合致しているようだったため、このように整理しています。  

* 2023/9/5 関西ペイント株式会社 [当社海外子会社への不正アクセスについて](https://www.kansai.co.jp/news/press23/publicrelationsnewsarticle.html-35)
* 2023/11/16 ヤマハ発動機株式会社 [フィリピン子会社に対する不正アクセスについて](https://global.yamaha-motor.com/jp/news/2023/1116/corporate.html)
* 2023/11/27 LINE ヤフー株式会社 [不正アクセスによる、情報漏えいに関するお知らせとお詫び](https://ly.swcms.net/ja/ir/news/auto_20231127594672/main/0/link/Notice%20and%20apology%20regarding%20information%20leakage%20due%20to%20unauthorized%20access_JP.pdf)

### T1078 Valid Accounts
* 2023/6/2 東京都 [個人情報の不正閲覧・取得及び漏えいについて](https://www.metro.tokyo.lg.jp/tosei/hodohappyo/press/2023/06/02/12.html)
* 2023/9/28 兼松株式会社 [元従業員の逮捕について](https://www.kanematsu.co.jp/press/files/press/20230928_release.pdf)
* 2023/10/20 独立行政法人日本学生支援機構 [委託事業者における個人情報の漏洩事案の発生について](https://www.jasso.go.jp/news/1208184_1579.html)
* 2023/12/1 仙台市 [懲戒処分の公表について](https://www.city.sendai.jp/somu-jinji-jinji/kisha/20231201.html)
* 2023/12/5 アルプスアルパイン株式会社 [退職した元従業員の逮捕について](https://www.alpsalpine.com/cms.media/20231206_PR_1f894a1571.pdf)

### T1078.001 Valid Accounts: Default Accounts
* 2023/3/31 国土交通省 [配信を停止している簡易型河川監視カメラの再開について](https://www.mlit.go.jp/report/press/mizukokudo03_hh_001168.html)

## TA0006 Credential Access

攻撃者のログイン試行に起因するインシデントは、"TA0001 Initial Access" の中に適した Techniques が見当たらないため、"TA0006 Credential Access" の中の Techniques に割り当てて整理しています。

### T1110.001 Brute Force: Password Guessing
* 2021/07/28 KLab株式会社 [KLab ID への不正ログインに関するお知らせ](https://www.klab.com/jp/press/info/2021/0728/klab_id_1.html)

### T1110.003 Brute Force: Password Spraying
* 2024/01/19 Microsoft [Microsoft Actions Following Attack by Nation State Actor Midnight Blizzard](https://msrc.microsoft.com/blog/2024/01/microsoft-actions-following-attack-by-nation-state-actor-midnight-blizzard/)

### T1110.004 Brute Force: Credential Stuffing
* 2021/06/03 セゾン自動車火災保険株式会社 [「マイページ」ログイン画面への不正アクセスについて](https://news-ins-saison.dga.jp/topics/down2.php?id=9000937&attach_id=1054&seq=1)
* 2023/03/30 エン・ジャパン株式会社 [「エン転職」への不正ログイン発生に関するお詫びとお願い](https://corp.en-japan.com/newsrelease/2023/32484.html)

## TA0042 Resource Development

第三者によるドメインの再利用に起因するインシデントは、"TA0001 Initial Access" の中に適した Techniques が見当たらないため、"TA0042 Resource Development" の中の Techniques に割り当てて整理しています。  

本来、MITRE ATT&CKの Enterprise tactics の順番では、"TA0042 Resource Development" は "TA0001 Initial Access" より手前です。 "TA0001 Initial Access" 側を中心に整理したいため、 "TA0042 Resource Development" を後に記載しています。  

### T1584.001 Compromise Infrastructure: Domains
* 2023/10/27 浜田市 [浜田市が廃止したドメイン名の第三者による取得について](https://www.city.hamada.shimane.jp/www/contents/1700611474937/index.html)
* 2023/11/7 堺市 [「堺旅キャンペーン」で使用したドメインの第三者による再利用について](https://www.city.sakai.lg.jp/kanko/kanko/oshirase/sakaitabi_domain.html)

## その他
* [「サイバー攻撃被害に係る情報の共有・公表ガイダンス（案）」に対する意見募集の結果及び「サイバー攻撃被害に係る情報の共有・公表ガイダンス」の公表](https://www.meti.go.jp/press/2022/03/20230308006/20230308006.html)

