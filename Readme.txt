HAL東京昼間部4年生ゲーム制作コース3年の和田一樹です。見ていただきありがとうございます。こちらには、操作方法と今回の作品のポイントを記載したいと思います。
＜操作説明＞
W：前に移動
S:後ろに移動
A：左回転
D:右回転
Q:弾の変更
R:エモート
T:チャージ
SPACE:弾の発射/画面遷移(タイトル、操作画面、ルール画面、クリア画面、ゲームオーバー画面の時のみ)

※ルール画面からゲーム画面に遷移するとき少し時間がかかります。
勝手に許可もなくモデルを使うのはやめてください。
画面の流れとしては以下の通りです。
タイトル→操作説明→ルール→ゲーム→クリアorゲームオーバー→タイトル
このゲームはいい艇の確率で一度死んでももう一度だけ生き返ることができます。しかしゾンビ状態なので体力バーには体力が表示されません。
一定数の攻撃を受けるとゲームオーバーになります。

今回の作品のポイントは、3つあります。
一つ目に敵のAIです。敵のAIには、ステートマシンを使っています。詳しく説明すると、プレイヤーに向かってくる敵はプレイヤーと一定の距離になるまで近づいてき一定の距離になると攻撃を始めます。攻撃は弾を投げてくるようにし、一定時間攻撃をした後また、プレイヤーを追うようにしてます。
また、プレイヤーから攻撃をうけ一定の体力になるとプレイヤーの向いてる方向を常にとっているのでプレイヤーとは逆方向に逃げるようになっています。
二つ目にコリジョンです。ドアとプレイヤーのコリジョンには、箱型のものを使用しています。箱型のコリジョンを作る際に、いくつか同じ座標があるのでそういったところをインデックスを用いておなじ座標を省くことでコードを見やすく工夫をしました。
三つ目に弾です。プレイヤーは、まっすぐ飛ぶ弾、二本同時に出る弾、二方向に飛ぶ弾、チャージして撃つ弾の四種類があります。
二方向に飛ぶ弾は、プレイヤーの向いてる方向に応じて飛ぶ方向が変わります。チャージする弾は、チャージしている間左下にチャージ量が見え、チャージする量に応じて攻撃力が変わります。
また、弾、回復アイテム、鍵、ドアといったモデルは自作です。

ここまで見ていただきありがとうございました。ぜひ何か気になったポイントがあればzoomのほうに来てください！
