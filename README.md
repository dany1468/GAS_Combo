# GAS_Combo
Gameplay Ability Systemを使ったベルトスクロール風アクションゲームのサンプルプロジェクトです。
叩き台としてお役立て頂ければ幸いです。

![image](https://user-images.githubusercontent.com/40533980/209134792-ee0f97b4-5de5-4e14-bf05-cfc69c90fbf5.png)

# 特徴
- C++無し、全てBlueprint実装
- Gameplay Ability System関連機能
  - 以下の機能を使用しています(BPで利用できる範囲で)
    - Gameplay Ability
    - Gameplay Tag
    - Gameplay Cue
  - 逆に以下の機能は未使用です
    - Gameplay Effect
    - Gameplay Attributes
- ベルトスクロール風アクション
  - Data TableとData Assetを使ったキャラ別の技表
  - ヒット時のみ派生するコンボ
  - 格闘、掴み、投げ、投げ巻き込み
  - ヒットストップ、ヒットスロー、ヒットシェイク
  - アイテムボックス、消費アイテム、装備アイテム、装備による技変化
  - 簡易なザコ敵制御

# 解説
Wikiで記述予定
TODO: 目次的なページへのリンクを貼る

# 参考資料
ざっくり概要を知る

- [猫でも分かる UE4の新しいサンプル「Action RPG」について【第８回UE4勉強会 in 大阪 2018】 | ドクセル](https://www.docswell.com/s/EpicGamesJapan/KNLLP5-UE4_SGOsaka2018_ActionRPGSampleCat)

見ながら手を動かす

- [[UE4]GameplayAbilitySystemでコンボ攻撃を作る｜株式会社ヒストリア](https://historia.co.jp/archives/15422/)
- [【UE4/UE5初心者向け】GameplayAbilitiesをC++を書かずに使ってみた - YouTube](https://www.youtube.com/playlist?list=PLfKehW5UrkqvSzuAi6JJglclwQCeUQFG8)
- [GameplayAbilitiesの使い方(セットアップ編) - おかわりはくまいのアンリアルなメモ](https://okawari-hakumai.hatenablog.com/entry/2018/07/22/165242)

動くサンプルを見る

- [Action RPG：Epic コンテンツ - UE マーケットプレイス](https://www.unrealengine.com/marketplace/ja/product/action-rpg)
- [Lyra Starter Game：UE ゲームサンプル - UE マーケットプレイス](https://www.unrealengine.com/marketplace/ja/product/lyra)

先人たちの記録を読む

- [ネリスさん備忘録](https://lunanelis.hatenablog.com/archive/category/GAS)
- [UE4 Gameplay Tagを使ってゲームプレイ時のタグ管理をより扱いやすくする - Let's Enjoy Unreal Engine](https://unrealengine.hatenablog.com/entry/2017/02/21/220000)
- [GASのデザインパターン まとめ - じゃっくぽっとラボ](https://jackpot-lab.hateblo.jp/entry/2021/12/24/070000)
- [UE4 GameplayAbility Pluginについてのメモ - Qiita](https://qiita.com/unknown_ds/items/6d4438646827bbe08f4a)
- [[UE] AbilityTask について全部書くよ - Qiita](https://qiita.com/koorinonaka/items/cf26af4433fda41134ac)
- [[UE] AbilityTask のつくりかた - Qiita](https://qiita.com/koorinonaka/items/50b8daed1c4d7f691b62)
- [GASでダッシュアビリティを実装しよう！（アビリティにキー入力を関連付ける） - げーむ開発徒然日記~怠惰のために勤勉~](https://game-dev-study.hatenablog.com/entry/2022/01/04/183632)
- [GameplaySystem カテゴリーの記事一覧 - そうだ、ゲームを作ろう](https://wvigler.hatenablog.com/archive/category/GameplaySystem)

さらに詳しく掘り下げる

- [Unreal Engine のゲームプレイ アビリティ システム | Unreal Engine ドキュメント](https://docs.unrealengine.com/latest/ja/gameplay-ability-system-for-unreal-engine/)
- [【UE4】Gameplay Ability System を使い始めたい人向けの情報 - Qiita](https://qiita.com/sentyaanko/items/314ee39feb62ce67b885)
- [GASDocumentation/README.jp.md at lang-ja · sentyaanko/GASDocumentation](https://github.com/sentyaanko/GASDocumentation/blob/lang-ja/README.jp.md)
- [GASShooter/README.jp.md at lang-ja · sentyaanko/GASShooter](https://github.com/sentyaanko/GASShooter/blob/lang-ja/README.jp.md)

資料を残して下さる方々に感謝致します…🙏

----

以上
