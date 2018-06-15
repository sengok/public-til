# Unity プログラミングバイブル 9章

Anima2Dとか使って2Dボーンアニメーションをするよ

## Sprite

### インスペクタでの設定

#### Sprite Mode

画像を1枚の画像として扱うときは「Single」、複数に分割（Slice）して使うときは「Multiple」を選択する。

## Sprite Editor

### スライス

#### Type

手動でもスライスできるけどTypeをautomaticにするといい感じにやってくれる

#### Pivot

あらかじめ決められた9箇所のうちどこに置くか決めれる

#### Method

どういうルールでSpriteを作るか決めれる
Delete Existingだったらとりあえず今あるSpriteは消すとか、Smartだったら名前とかは保持した状態で領域だけ再設定して作るとかいろいろ選べる。

## Anima2D

SpriteからAnima2D専用のSprite Meshを作成できる

### SpriteMesh Editor

#### Slice Tools

Meshの分割ルールを決めれる。分割数を大きくするとなめらかに動くようになるけど、表示は重くなってしまうので注意。

### boneを入れる

* 作成したSpriteMeshをHierarchyにD＆Dする
* 2D Object → Boneと選んでboneをScene Viewで設定していく
* SpriteMeshを選んでInspector上でBonesリストのところにBoneをD&Dしていく
* SpriteMesh Editorで調整していく

