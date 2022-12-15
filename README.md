# CLI MineSweeper
CLI上でマインスイーパーを遊ぶ

## Requirement
- Python3.8 ~ latest version

これだけ
## Usage
```bash
$ git clone git@github.com:KerorinNorthFox/MineSweeper_on_CLI.git # 自分の環境に持ってくる

$ cd MineSweeper_on_CLI # ディレクトリ移動

$ python main.py # ゲーム起動!!
```
これだけ

## Update the Game
```bash
$ git pull # 更新を取り込みます
```

## How to play
### 1.ゲーム起動
次を実行してゲームを起動します。<br>
```$ python main.py```


### 2.ゲームステージ設定
ステージの大きさを入力(5～20の間で)してください。<br>入力した数でステージの縦横の大きさが決まります。(5の場合5x5=25マスのステージ、20の場合20x20=400マスのステージ!!)


### 3.ゲームスタート
カウントダウンが始まりゲームが始まります。<br>画面上に表示された"o"(マル)がマス目を表しています。


### 4.メニューについて
ゲームが始まると、メニューが選択できます。
<br>メニュー選択後は操作を実行するマス目を縦横の順で数字の間にカンマを入れ、座標を入力してください。(例:縦2マス目、横3マス目に操作->"2,3"と入力)

#### 4-1.メニュー1:「旗を立てる/除ける」
この次の入力で指定した座標に旗を立てることができます。既に旗が経っている場合は、旗を除けることができます。旗が立った場所は画面が更新された後、"F"(FLAG)と表示されます。
#### 4-2.メニュー2:「マスを開放する」
この次の入力で指定した座標の場所のマスを解放します。爆弾に当たった場合、爆発するアニメーションが入ります。

これらの操作を行い爆弾を除去していき、最後まで旗を正しい場所に立て終わったらゲームクリアです。


### 5.コンティニューについて
爆弾に爆発した後三回までコンティニューができます。(コンティニューの数はステージの大きさで変わりません。つまり、ステージが広くなるほど難易度が上がります。)

## Playing Hints by developer

