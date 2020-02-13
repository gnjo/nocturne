
# nocturne
```
世界は善悪の彼岸にあり、なべて世は斑。
```
```
テーマ一覧、テーマは偏らせず、対立軸を並立させる。
善悪
神魔
極統
成失
淡悦
勃斜
条無
乱沈
喜怒哀楽
衣食住
種族、部族、異邦人
修羅、挫折
王邪
創造、破壊
奇天烈、塞翁が馬、意味不明
```
```
大方針

二択選択肢は、考えるを追加する。はい、いいえ、考える。考えるを選ぶと解説がある。解説の主語は基本省略。

序盤、中盤、終盤とキャラクター育成が違ってくる。
序盤、レベルを規定レベルまであげる。規定レベルは十五。
中盤、攻略に有用なスキルを整える。スキル付きの武具が多く登場する。
終盤、強力な武具を揃える。全ての装備を一新するような強力な物を登場させる。

街で受ける依頼は、章を進める依頼。物語の依頼は、報酬を放棄すれば難易度維持。報酬を得ると難易度が二つ上がる。
迷宮内で受ける依頼は、ランダム階層の迷宮を一層生成する。報酬を放棄すれば難易度が下がる。

A.迷宮のマップを埋める事が面白い。
B.依頼は基本、その階層で達成する。
C.現在の進行度を即座に情報として提示する。
D.マップを即座に情報として提示する。
E.ひとつの依頼に複数の解決策があり、それぞれ報酬が違う。報酬は三択。
F.重要職を使って解決する事ができる。
G.道具を使って解決する事ができる。
H.魔法を使って解決する事ができる。
I.財産を使って解決する事ができる。

依頼は章を進める為にある。一つの周回は十章で終わる。難易度は常に確認する。最重要。
依頼の報酬は破格だが、難易度を上げる。報酬を放棄する事で難易度は下がる。
難易度は、魔物の生命力と耐性に反映する。難易度の最大は２０。
他魔物は、生命力を難易度＊５加算する。全耐性を難易度＊１％上げる。
アークは、生命力を難易度＊５０加算する。全耐性を難易度＊４％上げる。
難易度１０以上は再生付き。難易度１５以上は裏アークつき。

右上に、パッシブマークを４つ入れる。

迷宮を探索する為の要職を設けないが、輪廻という職がいる。
輪廻が１０から１に戻る時、命の石を貰える。命の石は生命力５上昇。
輪廻の代用として、レアアイテムが迷宮から落ちる。同等の効果をもたらす。

```
```
仕様は番号を振る。大方針の英字を加える。

１．


```
```
迷宮探索の要素。
上。四行、メッセージ。
上。四行、詳細メッセージ。
右上。パッシブ、エンカウント、難易度。
中央。一行帯。気づき、章コール、ああっと。
中央フェイス。敵表示、左、中央、右。
下。七行、戦闘、キャンプ、選択肢。一行と六行選択肢。

XYはあまり使わず、常に固有の動作をする。
Yを押すと常に詳細。Bで閉じる。

```
## 魔技体系
```
魔法と技能は共通で、自身のレベルと同じだけ使用できる。
```

## 隠し扉
```
隠し扉を発見する事は楽しみの一つである。
```

## 戦闘後宝箱
```
アイテム蒐集に面白さを見出すため、戦闘後の宝箱は重要な要素である。
戦闘後には、宝箱があり稀にフェイが閉じ込められている。迷宮内効果がある間。
１．フェイが閉じ込められているか確認する。フェイは一割の確率で出現する。
２．フェイ以外の場合、宝箱は、テーブルを二つ参照し、一割の確率で上位のテーブル。九割の確率で適正テーブル。

戦闘後には宝箱があり、稀にフェイが閉じ込められている事がある。
１．輪廻を除く、全員の使用回数を５回復する。
２．宝石が欲しい。数と種類は気まぐれ。
３．全員の死亡を除く状態異常を回復する。
４．二人まで蘇生する。
５．立ち去る。
フェイ出現後、迷宮内効果は消える。
```

## 迷宮内宝箱
```
迷宮内の宝箱は、イベントに重要なものか、迷宮内効果を得る為にある。
イベント以外の場合、半々の確率でミミックか迷宮内効果。パーティーで最も高い幸運を上限に、確率を上げる。
確率は提示する。ミミックの出現率７５％
迷宮内効果は、唯一つ。
１．通常敵の生命力を半減させる。
２．通常敵は常に最大数出現する。
３．宝箱のレア確率を一割上げる。
４．立ち去る。
```

## ワイヤーフレーム
```
描画の最後に、枠の一つ内側に太い黒枠で消す。枠ギリギリの線を消す為。
奥行きは四まで。
０１２　正面は見える。
３４５　全て見える。
６７８　全て見える。
９ＡＢ　Ａに立つ。自身の立つ場所。自分の足元は見える。左右の壁は半分見える。

```

## 能力値
```
古典的なものを採用するが、六種類目に鞄量を加える。鞄量はパーティー全員で加算される。
レベルによる能力値の上限は２５。鞄量は８。最大５０まで計算される。
腕力：２５
知恵：２５
信仰：２５
敏捷：２５
幸運：２５
鞄量：８
```

## 鞄量
```
迷宮内で、装備の変更、道具の使用は出来ない。
鞄量はパーティー全員で累積される。死亡しても変わらない。
上限を超えても持ち歩く事ができるが、最終ダメージを半減する。
鞄量は、迷宮進入時に固定される。
```


