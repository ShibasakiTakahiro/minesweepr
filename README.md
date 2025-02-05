# Minesweeper (マインスイーパー)
このプロジェクトは、CまたはPythonで実装されたマインスイーパーゲームです。

## 実行例
- python: pythonをインストール後、`python minesweeper.py`を実行してください。

- c: Cコンパイラ（gccなど）をインストールし、`gcc -o minesweeper minesweeper.c`でコンパイルした後、`./minesweeper`で実行してください。

## ゲーム概要
プレイヤーはマスを開き、地雷を避けながらすべての安全なマスを開くことを目指します。

## ゲームボード
ファイルを起動すると以下の写真のようにゲームボードが表示されます。横軸（x）は0から7まで、縦軸（yは下から上に0から7までの座標を持ちます。ボード内のxは、未開示のマスを示します。

|![image](https://github.com/user-attachments/assets/a0ee15c4-cdb7-4830-8127-e6e95a282bcb) |
|:-:|

## 操作方法

- モード1: セルを開く

|![image](https://github.com/user-attachments/assets/a2656a8c-e25b-40b6-b1d8-0ce41c8cb27f)|
|:-:|

- モード2: フラグを設置/解除　(操作例はモード1と同様)


## 勝利条件
すべての安全なマスを開くと勝利。

## ゲームオーバー
地雷 (-1) のあるマスを開いてしまうとゲームオーバー。
