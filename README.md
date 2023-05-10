# 株式会社VRST 開発研修カリキュラム:beginner:

### [研修カリキュラムディレクトリ](https://drive.google.com/drive/u/0/folders/1TBYsHoriqXbEHuW3WiRZ2AYVwuY9VE_C)

## :high_brightness:Environment
- Windows x64
  - [IDEダウンロード_JDK17](https://ftp.jaist.ac.jp/pub/mergedoc/pleiades/2022/pleiades-2022-12-java-win-64bit-jre_20230124.exe)
- Mac
  - [IDEダウンロード_JDK17](https://ftp.jaist.ac.jp/pub/mergedoc/pleiades/2022/pleiades-2022-12-java-mac-jre_20230124.dmg)
- Windows x32 :warning:
  - 現在、32bitバージョンはIT関係の仕事をする上でスペック不足のため、基本的にはサポートが止まっていっています。ITリテラシー向上も含め自身のPCスペックが足りない方はPCを貸与してもらうか、32bitバージョン以外のPCで開発環境を整えるようにして下さい
  - [IDEダウンロード_JDK8](https://ftp.jaist.ac.jp/pub/mergedoc/pleiades/2018/pleiades-2018-09-java-win-32bit-jre_20181004.zip)

## :high_brightness:Why
実践編をするにあたっての最低限のjava技術を身につけ、効率的なスキルアップを図る

## :high_brightness:Target
- ***人間面***
  - コミュニケーションの取り方を学ぶ
  - 問題解決能力を身につける
- ***技術面***
  - javaのコードが読める
  - オブジェクト指向の概要を掴む
  - 簡単なコード実装ロジックを組めるようになる

## :high_brightness:Work
- ***研修課題***
  - [`カリキュラム`](https://drive.google.com/drive/u/0/folders/1xXsSve61DZ8HeRqd-9Nu8E0ZwpvhssOn)へアクセスができたら、【技の書】java基本文法編や社内にあるJavaの基礎を網羅している書籍で文法の概要を読み、【実装力チェックテスト】のアウトプットに取り組んでください。<br>【実装力チェックテスト】01_条件分岐などChapter毎にプログラム課題が用意されています 
  - 入社月毎の[`カリキュラム進捗表`](https://drive.google.com/drive/u/0/folders/1TBYsHoriqXbEHuW3WiRZ2AYVwuY9VE_C)のスプレッドシート内にご自身のシートがあります。<br>期限が引いてありますので、原則<span style="color: red; font-weight: bold;">期限に間に合うよう</span>取り組むようにして下さい。<br>こちらは毎日業務開始・14時・業務終了時に研修担当者が確認します。シートの進捗率の更新と、更新に合わせてご自身のGithubにコミットを必ず忘れないようにして下さい。
    - `※期限に間に合いそうにない場合`<br>issue発行(下記記述)・ハンズオン希望などを駆使して必ず期限調整ができるよう[`#05_09_eng_開発課-研修業務報告`](https://vrst-engineer.slack.com/archives/C031M69L7MH)チャネルで自身の業務報告したスレッド内で`@dev-edu`のメンションをつけてやりとりして下さい
    - `@dev-edu` で連絡が返ってくる方々が皆様の研修をサポートする**研修担当者**になります
      * 高橋 壮人(たかはし たけと)
      + 鈴木 秀也(すずき しゅうや)
      + 林　壱聖(はやし いっせい)
      + 稲垣 和允(いながき かい)
      + 森田 茂之(もりた しげゆき)
      + 菅井 慎太(すがい しんた)
      + 二本柳 清繁(にほんやなぎ きよしげ)
  - 研修担当者も皆様と同じく、現場で通常業務を行っているため、ハンズオン希望時は研修担当者の時間を必ずご自身からスケジュールを抑えに来て下さい
- ***研修課題提出方法***
  - Chapter毎にbranchをdevelopから切り、取り組んだChapterがわかるようにbranchからPull Requestを出して下さい。
    - ex.) chapter1 に取り組む場合 `feature/chapter1` とする 
  - Pull Requestを出したら、[`#05_09_eng_開発課-研修業務報告`](https://vrst-engineer.slack.com/archives/C031M69L7MH)チャネルで自身の業務報告したスレッド内に `@dev-edu`メンションをつけてPull Requestを出した旨を必ず報告する
  - *Reviewが完了次第、Mergeをして delete head branch まで行う*
    - Reviewが終わるまで、[`カリキュラム進捗表`](https://drive.google.com/drive/u/0/folders/1TBYsHoriqXbEHuW3WiRZ2AYVwuY9VE_C) は90%から更新しないこと。Mergeが終わって初めて100%とチェックボックスを更新する。
    - ※Review待ちの間、余裕があれば次のChapter着手は問題ありません。branchは忘れずに切り替えて下さい
  - Reviewの指摘内容が不明になった場合、恐れずにReviewerに聞き返す・issueを発行するなどして抱え込まないこと
- ***参考資料***
  - 下記以外にも助けになる書籍は社内にありますので必要に応じてご利用ください
    - スッキリわかるJava入門
    - プロになるJava
    - Java本格入門
    - [`#03_01_学習広場`](https://vrst-engineer.slack.com/archives/C02SC2103SR) チャネルにピン留めされているUdemy VRSTアカウント(Git,Javaなど)

## :high_brightness:How
- ***進まなくなった時***
  - 問題やエラーは、まずは調べて**30分**は自分でなんとかしようと努力してみる
  - それでも分からない場合は、**同期**と話す
  - 同じ人(同期や先輩)ばかりと話さない
    - 社内にいる色々な人とコミュニケーションをとれるようになりましょう
    - 自分も含め、色々な人にアウトプットの場を提供して下さい
  - それでも分からない場合は、**研修担当に質問**をする
- ***質問の仕方（誰に質問を投げる時も同じ）***
  - 口頭でいきなり質問しない
  - 皆様の解決になるべく早く辿り着ける助けになるよう、聞きたい内容を整理できるテンプレートとして`issueを発行できる`ようにしてあります。一度テキストベースで考えを整理してからPull Request時同様に、[`#05_09_eng_開発課-研修業務報告`](https://vrst-engineer.slack.com/archives/C031M69L7MH)チャネルで自身の業務報告したスレッド内に `@dev-edu`メンションでissueを発行した旨を連絡して下さい
  - 解決した・してないに関係なく、同期や先輩方に時間を割いてもらったことに感謝を忘れないこと（伝えると尚良）

## :high_brightness:Wanted
- ***質問を受けた際に、自分なりに必ず回答を出してみる（調べても良い）***
  - 問題を解く以外にも、人に教えることで自分の知識の整理になる
  - 周辺知識が増え知識が定着するきっかけになる

## :high_brightness:Finally

鈴木 秀也からのメッセージ

	みなさん、こんにちは、こんばんは、またはおはようございます。
	これからVRSTの社員として、険しく厳しい道のりを歩んでいくことになります。
	
	研修も面談も案件参画後も、ずっと大変です。
	未経験2ヶ月で開発現場に入るというのは、想像以上に大変すぎることです。
	
	ただ、心が折れなければ、諦めなければ、そして考えることをやめなければ、
	必ず成長できる環境が、VRSTにはあります（他の会社でもそうかもしれませんが笑）。
	
	僕が思うVRSTのいいところは、支えてくれる仲間がいることです。
	他のSES会社だと、自分以外の社員に会ったことがないということも往々にしてあります。
	困った時は、いつでも相談して欲しいです。頼って欲しいです。
	
	自分が諦めない限り、僕らは支え続けます。
