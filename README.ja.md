# ai-rhythm

Neural Drum Machine Density Remix

## デモ
[https://code4fukui.github.io/ai-rhythm/](https://code4fukui.github.io/ai-rhythm/)

## 機能
- ディープニューラルネットワークで動作する実験的なドラムマシン
- シードパターンを定義し、ニューラルネットワークを使用して続きのパターンを生成可能
- Density、Tempo、Swing、Temperatureの調整コントロールを提供

## 必要環境
- Webブラウザ

## 使い方
ドラムマシンの使用手順:
1. 左側でシードパターンを定義します
2. 「generate」ボタンを押し、ニューラルネットワークに続きのパターンを生成させます
3. 各種コントロールを調整して出力を変化させます

## データ / API
このプロジェクトは以下のオープンソースライブラリとモデルを使用しています:
- [Google Magenta](https://magenta.tensorflow.org/) の [Drums RNN](https://github.com/tensorflow/magenta/tree/master/magenta/models/drums_rnn) および [MusicVAE](https://github.com/tensorflow/magenta/tree/master/magenta/models/music_vae) モデル
- [Magenta.js](https://goo.gl/magenta/js)、[TensorFlow.js](https://js.tensorflow.org/)、[Tone.js](https://tonejs.github.io/)

## ライセンス
MIT License — 詳細は [LICENSE](LICENSE) を参照してください。
