# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

カレンダー連動ギフティングサービス
*制作の経緯

　親、兄弟、友人、恋人の誕生日、親の結婚記念日、母の日、父の日、クリスマスなど、ギフトを送る機会がたくさんあるが、忙しい日々を過ごす中で、忘れてしまうことがある。また、母の日、父の日などは、その年によって違うため、調べる必要がある。これをカレンダー登録、通知、商品の選択、決済を行うサービスをつくることによって解決する。

*制作期限

　目標　１週間
　期限を設定することによって早期の開発を目指す

機能概要・流れ

１、ユーザー登録　ログイン機能

２、カレンダーへイベント登録
　家族、友人、知人の誕生日、記念日、クリスマス等を登録
（グーグルカレンダーまたは、iPhoneのカレンダーに連動させたいが技術的、期間的に不可能　　　　だと判断した場合、簡単に直近のカレンダーをビューで再現する）

３、カレンダーのイベントの一週間前に通知
　　（iOS,Android等アプリ化して、スマホに通知が来ることを目標としたいが、今回はWeb　　　　での再現を目指すため、メールにて通知としたい。）

４、通知をタップすると、イベントにあわせて例えば、
例）２０代　妹の誕生日
の場合、２０代、女性と年齢、性別ごとにカテゴライズされたギフトをランキング表示
（本来は、商品にアフィリエイトを設定したり、サービスが拡大した場合広告を募集したり、または、自分がよく使う高島屋などの百貨店の商品を連動させて掲載料を頂くなどのマネタイズを意識したい。今回は、あくまでも短期での開発を目指すため、簡単にビューでの再現を目指す）

５、商品をクリックすると、購入画面へ飛ぶ

６、クレジットカード決済
（こちらも、技術的、期間的または、金銭的に実装可能かわからないが、調べてみる）

以上の流れのサービスを作りたい。

*DB設計

[AutoGift.pdf](https://github.com/NaoyaW/AutoGift/files/2280094/AutoGift.pdf)
