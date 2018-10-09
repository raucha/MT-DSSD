## 学習データ
* 画像データ
* 画像のバウンディングボックス  
`/train/buondingbox/`内に画像名と同じテキストファイルを置き,下記のフォーマットでバウンディングボックスを記載
```plane
[クラス名] xmin ymin xmax ymax
[クラス名] xmin ymin xmax ymax
・・・
```
* セグメンテーションラベル画像  
```
/train/segmentation/***.png
```
convertC2G.pyにRGBからクラス値への変換テーブルが記載(最新版ではcommon_params.pyに移動)
* セグメンテーション
