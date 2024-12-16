# パーティクルライフシミュレーター

[デモを見る](https://quantum-simulation.netlify.app)

このプロジェクトは、パーティクル間の相互作用をシミュレートし、その動きを音に変換する3Dビジュアライゼーションツールです。

## 機能

- 3種類のパーティクル(赤・緑・青)の相互作用シミュレーション
- パーティクル間の引力・斥力の調整
- パーティクルの動きを音に変換(Sonification)
- インタラクティブな設定パネル
- リアルタイムなパラメーター調整

## 使い方

1. ブラウザでindex.htmlを開きます
2. 右側の設定パネルでパラメーターを調整できます:
   - グローバル設定: パーティクル数、サイズ、相互作用距離など
   - パーティクルタイプごとの設定: 各色のパーティル間の相互作用
   - Sonification設定: 音の周波数や音量の調整
3. 「ランダム生成」ボタンで相互作用をランダムに設定できます
4. 音を有効にするには画面をクリックしてください

## 設定パラメーター

### グローバル設定
- パーティクル数: シミュレーション内のパーティクルの総数
- パーティクルサイズ: パーティクルの基本サイズ
- 最小/最大相互作用距離: パーティクル間の相互作用が発生する距離の範囲
- 距離減衰係数: 距離による力の減衰の強さ
- 力の強さ: パーティクル間の相互作用の強さ
- 速度減衰: パーティクルの運動の減衰率
- ランダム力: パーティクルにかかるランダムな力の大きさ

### Sonification設定
- 基本周波数: 各色のパーティクルの基本音の周波数
- 周波数変化範囲: エネルギーによる周波数の変化範囲
- エネルギー→周波数影響度: エネルギーが周波数に与える影響の強さ
- エネルギー→音量影響度: エネルギーが音量に与える影響の強さ

## 技術仕様

- Babylon.js: 3Dグラフィックスエンジン
- Web Audio API: サウンド生成
- HTML5 Canvas: レンダリング
- カスタムGUIシステム: パラメーター調整用インターフェース

## 動作環境

- モダンなWebブラウザ(Chrome, Firefox, Safari, Edge等)
- WebGL対応
- Web Audio API対応

## デプロイ

このプロジェクトは[Netlify](https://quantum-simulation.netlify.app)でホストされています。

## ライセンス

MIT License

Copyright (c) 2024 riku ogawa

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE. 
