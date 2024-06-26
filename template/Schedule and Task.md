# Schedule and Task Management
スケジュールマネジメント


## Template
### Report Format
- オンボーディング：（作業依頼・引き継ぎ）
   - I（対象・前フェーズ成果物）
   - P（進め方）
   - O（結果・期限）
-  スプリント キックオフ：体制・スケジュール・メンバー
   - 体制図
   - スケジュール
   - クリティカルパス
- デイリースタンドアップ：進捗状況と阻害要因（15 分以内）
   - XXX
- ウィークリー：課題提起（他チーム・クライアント向け）
   - 定量
   - 定性（バーンダウン） 10/3/100（TODO/WIP/DONE）

<br>

## Contents

### Overview(MTG)
- [効率的で生産的な会議を行い、無駄な時間をなくすためのヒント](https://asana.com/ja/resources/stop-wasting-time-meetings)
- 非同期で収集して、全員の意見を引き出す工夫も必要
- なるべく内部でも資料事前送付必要

### Common Rules
1. ミーティングの目的やゴールを明らかにする
   1. 情報共有
   2. 意思決定
   3. 問題解決
   4. チームビルディング
   5. 壁打ちやフィードバック
2. 全体像や現在地を伝える
3. 前提情報の共有をする

### Scheduled MTG
1. オンボーディング：背景・目標・体制や決まりごとの共通認識をもつ
   - todo
2. [スプリント キックオフ](https://asana.com/ja/resources/project-kickoff-meeting)（1h）
   - 目的
     - メンバー同士でチームの足並みを揃える
   - 内容
     - プロジェクトの目的および目標
     - 計画スケジュール
     - 予算、コスト、見積り
     - チーム体制の説明とメンバー紹介
3. [デイリースタンドアップ](https://asana.com/ja/resources/stand-up-meeting)：進捗状況と阻害要因（15min）
    - 目的
      - 進捗状況とブロッカーについて会話する
      - ※問題を解決するためではなく、計画と実績の同期と修正、改善を行うアクティビティー（問題解決ば別の場で）
    - 内容
      - 全体共有
      - 個別（作業一覧）：必要があれば「催促」・「トリアージ」（★）
        - 概況：（Ahead/On Schedule/Behind）
        - 状態：（TODO/WIP/IN REVIEW/DONE）
      - レポートフォーマット
        - 概況：オンスケ
        - 実績：昨日何を完了したか?
        - 予定：今日何に取り組むか?
        - その他：何かブロッカーはあるか?、休み予定、共有事項
      - e.g.
        - NG:
          - 進捗はどうですか？ → 進行中です／〜をやっています
          - なにか問題はありますか？ → とくにないです
          - 〜までに終わりそうですか？ → たぶん大丈夫だと思います
        - OK：（今のproblemとnextを聞く）
          - 次にやることは何ですか？／このあとは何をしますか？（今のタスクの終わりが見えている）
          - 大変だったことはありますか？（リスク管理。再現性がある場合は対処必要）
          - どうでもいいけど話しておきたいことはありますか？
    - 実施ルール
      - 手短に行う：余分な会話をリーダーが制限する（コミュニケーションオーバーヘッドの増加に対処する）
      - 無意味な進捗報告はNG
      - アジェンダ形式にして、アドホックな相談は原則NGとする（アドホック頻発は小さいチームでしか回らない）
          - FIX（決まったこと）、TODO（次回やること）を自分で展開する
4. ウィークリー：課題提起（他チーム・クライアント向け）
    - 目的
      - リファインメント（グルーミング）：優先順位付け、チケットの統廃合、曖昧なチケットのゴール明確化
      - [優れた進捗報告](https://asana.com/ja/resources/how-project-status-reports)
    - 内容
      - 定量：
        - 進捗報告：10/50/100（完了/対応中/全体）
      - 定性：
        - リスクなど

5. スプリントレビュー（デモ）：プロダクトをチェック
    - todo
6. [レトロスペクティブ](https://asana.com/ja/resources/project-post-mortem-tips)：まず計画が大事（ファシリテータも記載する！）
    - 目的：
      - チームのダイナミクス、プロセス、ツールを具体的にレビューし、改善する。
      - スイートスポットを探し、チームのエンゲージメントを維持していく。
      - インサイトを引き出すアクションを選択するプロセス
      - 開発プロセスやチームの問題を点検して、改善するための活動。生産性、能力、品質の改善を達成することを目的とする
      - プラクティス・プロセスの改善
      - うまくいっていることを知る
      - うまくいかなかったことを知る（理由を理解する）
      - 顧客対応の改善点を見つける
      - 関係を修復する
      - 定期的に立ち止まって過去を評価して、継続的に修正していく
      - 強みのある部分が明らかにして、悪癖を改めることができる（インシデントから学ぶ）
      - 恒久対応、再発防止を行いインシデントを繰り返さない
      - 相手を非難せず建設的な議論を行う
      - 不要な作業の洗い出し：ビルド・デプロイ待ち・手戻り・プロセス待ち（承認）・オーバーエンジニアリング
      - チームは時間とともに改善しているか。（プロセス、速度、コード、ドキュメント、情報整理、コミュニケーション）
    - プロセス
      1. チームのフィードバックを収集する（事前）
          - 「感情」（幸せ・怒り・心配・混乱・悲しい・期待）データもあって良い。（チームとして重要なトピックが検討されるきっかけ）
          - （★）実施ルール
          - （★）テンプレート：KPT?
      2. インサイトを引き出す（会議中）
          - 1 週間のスプリントでは 45 分、2 週間のスプリントでは 1.5 時間、3 週間のスプリントでは 2.25 時間、1 か月のスプリントでは 3 時間確保
      3. アクションアイテムを設定する
          - 担当者と期日を明確にする
7. その他
   - インシデントウォークスルー：アクションを取った意思決定プロセスや技術的背景を詳しく説明する。（体験の共有）
     - インシデントサマリー：出来事のハイレベルな内容を記載（全体影響・対応内容等）
     - 定量フィードバック：簡単に取得できる
     - 定性フィードバック：具体的な背景情報が得られ、改善に繋がりやすい

### Adhoc MTG
- ディスカッション（収束）
  - I：概要、論点、制約など
  - P：想定案①・②
  - O：結果・期限
  - 理想としては、事前に論点整理して会議前に非同期で議論が進み、会議が始まる頃にはある程度解決していること（★）
- レビュー（決定・OK/NG）
  - 事前資料送付
- ブレスト（発散）：
  - 判断・結論を出さない(結論厳禁)
  - 粗野な考えを歓迎する(自由奔放) 
  - 質より量を重視する
  - アイデアを結合し発展させる(結合改善)

### Minutes
[議事録と会議メモを上手に取るためには](https://asana.com/ja/resources/meeting-notes-tips)
- I（インプット）：前提条件・事前準備
  - どのレベルが必要か
- P（プロセス）：進め方
  - 良い議事録（まず内容理解する）
    - 発言録ではない
    - 内容が構造化されている
    - 空気感まで加味されている
- O（アウトプット）：
  - AGENDA（議題）
  - FIX（決まったこと）
  - TODO（次回やること）

#### Tips
[会議の質を高めて、数を減らしたいですか](https://asana.com/ja/resources/meeting-management)
- 注意：コミュニケーションオーバーヘッドの増加に対処する必要あり
- なんの議題もなく、なんの準備もせず、即興力や知識、頭脳に頼って仕事をするのはNG（正しい仕事ぶりとして示す必要がある）
- 内部のコミュニケーション比率が高まりすぎると、有害なサイロ化が発生する
- 情報共有する場では、「行動喚起」と「質疑の時間設ける」ことを徹底する（★★★）
- 役割をローテーションすることが知識のサイロ化抑制につながる（★★★）
- ナッジング：自らの観点を提供して、意思決定を後押しする（★）
- 空中戦ばかりで情報連携ミスが多発→伝達者がチャットなどに情報を残す（★）
- 前提確認（重要な前提は〜）：前提認識が具体的であればあるほど、その認識について掘り下げ、検証しやすい
- VS：グループシンク（集団の考えに同意してしまう傾向）
- VS：ヒエラルキー・エフェクト（自分より地位が高い人の意見に異を唱えることに躊躇する傾向）
- VS：ソーシャル・ローフィング（社会的手抜き：発言すると自分の仕事が増えると思って、黙っている傾向）
- NG：不毛な会議は、やること自体が目的化している
- ミーティングを減らして、業務の負担を減らす工夫が必要。
- 意見を書いてもらう。聞かない。（非同期）
- 発言は多いが、発言時間は短い：シンプルでストレートな会話（評価★）
- 設計判断の話はパブリックの場所で会話して情報を残す
- 正論では動かないことを理解している：共感を得ながら行動喚起する
- 正しければなにをいってもいいは、幼稚な考え。（礼儀正しくレビューするべき）
- プラクティス
  - 愚かな質問をする（★発言を引き出す呼水と自らなっていく
  - アドホックな会議（技術的な対応方針検討）では内容を事前に書いておく（会議前にチャットで非同期で議論が進み会議時には方針決まっているのが理想）

### WBS
WBS作成時に、全ての情報持っているわけではない。
- IPO：定義する
- 良い委譲：チャレンジングなくらいの難易度、必要な時に（遅延しそうな時）把握する
- 悪い委譲（委譲そもそもできてないのもNG）：丸投げ、やり方を強いるタスクを奪う
- 役割をローテーションすることが知識のサイロ化抑制につながる★★★（スイッチングコスト）
- リソース配分
    - WBS
        - 見積もりを行うこと：どんどん精度を上げていく
        - たまたまうまくいったではなく、いい見積もりを続ける（再現性）
    - 人を見極めて・チームの仕事量とキャパシティを見極める（ピープルマネージメント）
    - 担当決め
    - 業務・負荷コントロール
    - トリアージ（必要があるかも検討する必要がある）
    - ボトルネックの解消：障害を取り除く、停滞しているチームのサポートをする

<br><br>

## References
- [アジャイル](https://asana.com/ja/resources/agile-methodology)：https://asana.com/ja/resources/agile-methodology
    - イテレーション（４process：Planning、Design、Implementation、Testing）繰り返す手法
- [スクラム](https://asana.com/ja/resources/what-is-scrum)（プロダクトバックログ、スプリントバックログ、製品インクリメント）
- [スクラムマスター](https://asana.com/ja/resources/scrum-master)（スプリント計画会議、スタンドアップミーティング、振り返り）
- [バーンダウンチャート](https://asana.com/ja/resources/burndown-chart)：残りの作業とそれに必要な時間が一目でわかるチャート
- [アジャイルセレモニー](https://asana.com/ja/resources/agile-scrum-ceremonies)（４つ）
    - スプリント計画
    - デイリースタンドアップ：
    - スプリント レビュー
    - スプリントのふりかえり
- [WBS](https://asana.com/ja/resources/work-breakdown-structure)
  - 役割と責任を確立する 4 つの方法（[RACI チャート](https://asana.com/ja/resources/roles-and-responsibilities)）
  - カンバン：[WIP制限（４つ）](https://www.atlassian.com/ja/agile/kanban/wip-limits)
  - [スコープクリープ](https://asana.com/ja/resources/what-is-scope-creep)
  - クリティカルパス
  - [遅延](https://asana.com/ja/resources/fast-tracking-vs-crashing)
      - クラッシング：追加
      - ファストトラッキング：並行
