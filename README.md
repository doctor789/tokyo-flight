# ✈ TOKYO FLIGHT — 実写フライトシミュレーター

実写の東京を飛ぶ、ブラウザ完結（単一HTML）のフライトシミュレーターです。羽田空港 C滑走路（34R）からジェット練習機で離陸し、レインボーブリッジ・東京タワー・スカイツリーを巡る10個のリングをくぐって戻ってきましょう。

**▶ プレイ: https://doctor789.github.io/tokyo-flight/** 

## 特徴

- **実写の地形**: 国土地理院の航空写真タイル＋標高データをリアルタイムにストリーミング（APIキー不要）
- **実測3D都市**: 国土交通省 Project PLATEAU の2025年版 3D都市モデル（都心10区）
- **実機3Dモデル**: Aermacchi MB-339 ジェット練習機 / Chengdu J-10 戦闘機
- **本格的な飛行物理**: 揚力・抗力・失速・オートトリム、離着陸、G表示、姿勢指示器
- **東京遊覧チャレンジ**: 都心ランドマークを巡る10リングのタイムアタック
- **Google Photorealistic 3D Tiles 対応**（任意・APIキー入力で有効化）

## 操作

| キー | 操作 | キー | 操作 |
|---|---|---|---|
| ↑ / ↓ | ピッチ（↓で機首上げ） | W / S | スロットル 増減 |
| ← / → | ロール | A / D | ラダー / 地上ステア |
| F | フラップ | B | ブレーキ |
| C / 1〜4 | カメラ切替 | R | リセット |
| P | ポーズ | M / L | サウンド / 地名ラベル |

**離陸のコツ**: F でフラップ T.O. → W 長押しでフルスロットル → 約250km/h で ↓キーを引いて機首上げ。

## クレジット / 出典

- 地図・航空写真・標高: [国土地理院タイル（地理院タイル）](https://maps.gsi.go.jp/development/ichiran.html)
- 3D都市モデル: [国土交通省 Project PLATEAU](https://www.mlit.go.jp/plateau/) (CC BY 4.0)
- 機体モデル: MB-339 by helijah, J-10 by andertan (CC BY 4.0)
- 描画: [three.js](https://threejs.org/) / [3d-tiles-renderer](https://github.com/NASA-AMMOS/3DTilesRendererJS)

## 動作環境

WebGL対応のモダンブラウザ（PC推奨、キーボード操作）。初回はタイル読み込みに数十秒かかります。
