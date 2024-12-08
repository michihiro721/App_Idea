■サービス概要
利用者からの情報（質問）をもとにニーズ（理想の体型）にあった筋トレメニューを生成し、作ったメニューの内容を記録できるアプリ。
※初心者には初心者にあったメニューを提案するが、玄人には自身でカスタマイズできる

■ このサービスへの思い・作りたい理由
・筋トレをしていて、元々は筋トレメニューや結果などをノートに記載して管理していた。
　それからフィットネスアプリの存在を知り、アプリを使って管理を始めたが、使い勝手が良くない部分があったため、
　それらの使い勝手のよくない部分や、この機能があったら使いやすいなと思う機能が搭載されたアプリを作りたいと思ったから。
・友人から筋トレのメニューを考えて欲しいとお願いされる機会が何度かあったため、アプリを作ってしまえば
　アプリを教えて終わりなので、いいなと思ったから。
・特にエンジニアという職業自体が座りっぱなしで、運動不足になりがちなので、周りのエンジニアになる仲間たちにも運動習慣を身につけて、健康でいてもらいたい。

■ ユーザー層について
・ユーザー層：筋トレ初心者、運動習慣がない忙しい社会人、健康的な体作りを目指す全ての人
・理由：運動不足と自覚していて、運動をしたいと思っている筋トレ初心者の人は、「何をしたらいいかわからない」と思うので、その問題を解決することができるから。
　　　　また、忙しい社会人の人についても、短時間で行うことができる筋トレメニューの提案もできると思ったから。

■サービスの利用イメージ
1. ユーザーは目標（例: ダイエット、筋力アップ）や現状の体型情報(体重など)を入力。
2. アプリが理想の体型に向けたトレーニングプランを提案。（※玄人は自身でカスタマイズ可能）
3. ユーザーはメニューに沿ってトレーニングを行い、その結果を記録。
4. 継続的な利用により、達成状況や進捗がグラフで可視化され、モチベーションを維持できる。
5. 成果が出ることで満足感を得られ、筋トレ習慣が形成される。
   ※筋トレの習慣が形成されることがユーザーにとっての価値となる。

■ ユーザーの獲得について
・Xでの拡散
・口コミ（RUTEQ生など）

■ サービスの差別化ポイント・推しポイント
・ 初心者から玄人まで幅広く対応: 初心者には筋トレメニューを提案、玄人には筋トレメニューを完全カスタマイズ可能な機能。
・ 数値管理が出来る： 体重などの数値データを扱っている項目について、変化の推移を可視化できる。（グラフ）
・　基礎代謝を計算：　体重と身長と年齢を入力することで基礎代謝が提示される。
・　トレーニングでの消費カロリーを計算：　トレーニングメニューをもとに消費カロリーを計算し表示させる。
・　1日の消費カロリーを計算：　1日の歩いた歩数を入力することで、その日の消費カロリー（基礎代謝、筋トレでの消費カロリー含む）の合計を算出してくれる（現状はAPIを使わない予定だが、制作する中でAPIで自動入力にする可能性あり）
・　摂取カロリーを管理：　摂取カロリーを入力することで、基礎代謝と消費カロリーをもとに、その日のカロリーが摂り過ぎなのかを客観的にわかるようにする。（摂取カロリーは別に個人で管理してもらう。自分の場合は「あすけん」）
・　ダイエットの説明：　筋トレやダイエットにおいて重要な内容についての説明ページを作成することで、ダイエットにおいて重要な、マインド面のサポートができる
・　インターバルをお知らせ：　インターバルの時間を設定して、時間が経過したら音でお知らせしてくれる

■ 機能候補
現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないのでMVPリリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。
⚫️MVPリリース時に実装したい機能
•ユーザー登録・ログイン機能
•目標設定ができる機能
•トレーニングメニューを提案する機能
•筋トレメニューのカスタマイズ機能
•トレーニング記録の登録・表示機能（カレンダーみたいに表示させる予定）
•トレーニング種目を登録した際に、種目の横に、その種目のMAX重量もしくはMAX回数が表示される機能（※この機能は地味にありがい機能）
•ダイエットについて説明するページを追加
•トレーニング時間の計測とアラート通知する機能
•消費カロリーを算出させる機能（トレーニング）
•基礎代謝を計算させる機能
•1日の歩数を登録・表示・消費カロリーの計算機能
•1日の消費カロリーを算出させる機能
•摂取カロリーを記録させる機能
•摂取カロリーと消費カロリーをもとに、1日のカロリーが摂り過ぎなのかを判断させる機能
•体重や摂取カロリー、消費カロリー、などの管理機能（記録とグラフ表示）
•プライバシー規約の表示機能
•お問い合わせフォーム機能

⚫️本リリースまでに追加したい機能
•トレーニングメニューや感想などを投稿（共有）する機能
•投稿された内容に対して、いいねとコメントができる機能
•誰からいいねされたのか、投稿者にわかるように通知される機能
+αアプリ作成中に追加したいと思った機能

■ 機能の実装方針予定
※ざっくりのイメージになります。


・ユーザー登録・ログイン機能の実装方法:
　　→ユーザー名、メールアドレス、パスワードを入力してアカウントを作成。ログイン後に専用ページへリダイレクトし、安全にセッション管理を行う。
　技術詳細:
　データベース: usersテーブルにユーザー情報（メールアドレス、暗号化パスワードなど）を保存。
　バックエンド: Devise Gemを使用して認証機能を実装。バリデーションで入力値の安全性を確保。
　セキュリティ: Deviseによる暗号化（bcrypt）、CSRFトークンでリクエスト保護を実施。
　追加機能: パスワードリセット機能を有効化し、メールでリンクを送信して再設定を可能にする。



・目標設定ができる機能の実装方法：
　 技術詳細：
   GoalsControllerを作成し、CRUD操作（目標の作成、編集、削除）を実装。



・トレーニングメニュー提案機能の実装方法:
　→ユーザーが入力した目標（ダイエット、筋力アップ）、体型情報（体重、身長）、経験値（初心者・中級者・上級者など）に基づき、条件分岐でプリセットメニューを動的に生成。
	技術詳細:
	データベース: workoutsテーブルに各種トレーニング種目、部位、消費カロリーを記録。
	ロジック: Railsのモデルでルールベースのロジックを実装。


 ・筋トレメニューのカスタマイズ機能の実装方法:
　　→ユーザーが提案されたメニューを編集したり、新しい種目を追加できるフォームを提供。種目ごとのセット数、回数、重量を入力できるUIを作成。
	技術詳細:
	フロントエンド: JavaScriptで動的フォームを作成し、編集操作をリアルタイム反映。
	バックエンド: RailsのCRUD操作でユーザーごとのカスタマイズデータを保存。


　・トレーニング記録の登録・表示機能の実装方法:
　　→カレンダー形式でトレーニング履歴を表示し、詳細をクリックするとその日の種目とセット内容が確認できる。
	技術詳細:
	フロントエンド: カレンダーUIにはFullCalendar.jsなどのライブラリを使用。
	バックエンド: トレーニングデータをtrainingsテーブルに保存し、日付で紐づけて表示。



 ・トレーニング種目を登録した際に、種目の横に、その種目のMAX重量もしくはMAX回数が表示される機能の実装方法：
	技術詳細
 　     データベース
	• workoutsテーブル（トレーニング種目を管理）に以下のカラムを追加：
	• max_weight（MAX重量）
	• max_reps（MAX回数）
	Ruby on Rails
	• モデルに計算やデータ取得のロジックを追加。
	• コントローラーでworkoutsデータを取得してビューに渡す。
	フロントエンド
	• ビューでトレーニング種目のリストを表示し、各種目の横にmax_weightまたはmax_repsを表示させる。
 　　  ※工夫：データが変更された際、JavaScript（例: Stimulus.js）を使ってリアルタイムで更新を反映する。（必要に応じてやってみる）



     ・ダイエットの説明ページの実装方法:
  　　→静的ページとして実装。ダイエットにおける重要ポイントをテキストと画像で表示。
	技術詳細:
	RailsのビューにMarkdownを組み合わせてコンテンツを管理。
	ページの管理にはHighVoltageなどの静的ページジェムを利用。



   ・トレーニング時間の計測とアラート通知の実装方法:
  　→タイマー機能を追加し、インターバル時間の終了時に音声や画面通知で知らせる。
	技術詳細:
	フロントエンド: JavaScriptのsetTimeoutを使用してカウントダウンを表示。
	通知機能: Web Notifications APIを利用してブラウザ通知する。
        音声：Audio オブジェクトを使用して音声を鳴らす。
	音声通知はユーザーの操作（タイマースタートボタン）をトリガーとして再生。
 　　　　


　・消費カロリー算出機能（トレーニング）の実装方法:
　　→トレーニングの消費カロリーが計算される。
   技術詳細:
   種目ごとの消費カロリー計算をRailsで実装。（種目ごとの消費カロリーは一つずつ調べる）



 ・基礎代謝を計算させる機能の実装方法：
 　技術詳細：
  データベース
	•usersテーブルに以下のカラムを追加：
	•weight（体重）
	•height（身長）
	•age（年齢）
	•gender（性別）
　Railsで基礎代謝を計算するメソッドを定義。
	•計算式（ハリス・ベネディクト方程式）:
	•男性: (10 × 体重) + (6.25 × 身長) - (5 × 年齢) + 5
	•女性: (10 × 体重) + (6.25 × 身長) - (5 × 年齢) - 161




 ・1日の歩数を登録・表示・消費カロリーの計算機能の実装方法:
　→歩数を登録し、日付ごとに消費カロリーを計算して表示する機能。
　技術詳細:
　データベース: stepsテーブルに日付、歩数、計算された消費カロリーを保存。
　バックエンド: 歩数 × 0.04 kcal/歩 で消費カロリーを算出し保存。
　フロントエンド: 歩数と消費カロリーをリストまたはグラフ（Chart.js）で表示。



 ・1日の消費カロリーを算出させる機能の実装方法:
　　→基礎代謝、トレーニング消費カロリー、歩数消費カロリーを合計して1日の消費カロリーを計算して表示。
　技術詳細:
　データベース: daily_caloriesテーブルに基礎代謝、各消費カロリー、合計カロリーを保存。
　バックエンド: 基礎代謝 + (歩数 × 0.04 kcal/歩) + トレーニング消費カロリーで算出。
　フロントエンド: 1日の消費カロリーを数値とグラフ（Chart.js）で表示。



・摂取カロリーを記録させる機能の実装方法:
　　→1日の摂取カロリーを入力し、記録・表示できる機能。
　技術詳細:
　データベース: intake_caloriesテーブルに日付と摂取カロリーを保存。
　バックエンド: ユーザーが入力した摂取カロリーをバリデーションして保存。
　フロントエンド: 入力フォームを提供し、記録した摂取カロリーを日付ごとにリストまたはグラフ（Chart.js）で表示。
 
 

　・摂取カロリー記録と過剰摂取の判断機能の実装方法:
　　→摂取カロリーを入力すると、基礎代謝と消費カロリーを比較して、その日のカロリー収支を計算。
	技術詳細:
	カロリー収支 = 摂取カロリー -（基礎代謝 + 消費カロリー）
	Railsでロジックを実装し、結果をグラフやテキストで表示。



  ・体重や摂取カロリー、消費カロリー、などの管理機能（記録とグラフ表示）の実装方法:
　　→履歴を登録し、日付ごとの推移をグラフで可視化。
	技術詳細:
	データベース: weightsテーブルに体重データを保存。（体重の場合の例）
	フロントエンド: Chart.jsで折れ線グラフを表示。
 


 ・プライバシー規約とお問い合わせフォームの実装方法:
　→プライバシー規約を静的ページとして追加し、フォームからメールでのお問い合わせができるようにする。
	技術詳細:
	プライバシー規約: Markdown形式で記載し、Railsで表示。
	お問い合わせフォーム: Action Mailerを使用してメール送信を実装。



　本リリース用の追加機能

 •トレーニングメニューの共有や感想投稿には、RailsのCRUD操作を拡張して投稿機能を実装。
 •「いいね」機能は、acts_as_votable Gemを利用して実装。 コメント機能は、commentsテーブルを用いて投稿に関連付けを実装。
 •通知機能はAction Cableを活用し、リアルタイムで投稿者にフィードバックを提供。
 
