# SynapseRack-TouchDesigner-Starter
## SRTDpf
SynapseRack の出力を TouchDesigner で即利用でき、TD側でもVJが出来ます。

このリポジトリは、SynapseRack のオーディオデータを TouchDesigner に直接取り込み、
すぐにリアクティブ表現を制作できるスターターテンプレートです。

### ✨ 特徴
- SynapseRack の各アウトプットを TD で自動受信
- Spectrum / Waveform / Envelope / Band-split の信号をまとめて利用可能
- そのまま VJ プレイができるシンプルな TD セットアップ
- SynapseRack → TouchDesigner → Spout/OBS/Resolume のパイプラインに対応
- 軽量構成のため長時間の VJ セットでも安定

### 📂 内容
- `SRTDpf.toe` : SynapseRack 連携済み TouchDesigner プロジェクトファイル
- `src/` : ノード構成図、バンド情報などの補助ファイル（あれば）
- `example/` : テスト用ビジュアルまたは参考パッチ（任意）

### 🚀 使い方
1. SynapseRack を起動し、Audio Routing を有効化  
2. TouchDesigner を開き、`SRTDpf.toe` を読み込む  
3. Audio CHOP に信号が入っていることを確認  
4. 任意の TOP / CHOP に接続してビジュアルを拡張

### 🛠 推奨環境
- TouchDesigner 2023 以降
- SynapseRack 最新版
- NVIDIA GPU 搭載 Windows 環境（推奨）

---

必要であればスクショ用の画像・Diagram・より丁寧な英語版 README も追加で作れます。
