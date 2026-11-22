# musical-fishstick

画像をモノクロ（白黒）に変換する、Google Colab 用のノートブックです。

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/y-kanpan/musical-fishstick/blob/main/monokuroimg.ipynb)

## できること

- パソコンから画像をアップロードする
- 画像をグレースケール（モノクロ）に変換する
- 変換した画像をその場で表示する

## 使い方

1. 上の「Open In Colab」ボタンを押して、Google Colab でノートブックを開きます。
2. コードのセルを実行します（セルの左にある ▶ ボタン、または `Shift + Enter`）。
3. 「ファイルを選択」ボタンが出るので、変換したい画像を選びます。
4. しばらくすると、モノクロになった画像が表示されます。

## ファイル

| ファイル | 内容 |
|---|---|
| `monokuroimg.ipynb` | 画像をモノクロに変換するノートブック |

## 使っているもの

- [Google Colab](https://colab.research.google.com/)：ブラウザで Python を動かせるサービス
- [OpenCV](https://opencv.org/)（`cv2`）：画像を処理するライブラリ
