# SynapseRack-TouchDesigner-Starter
## SRTDpf
SynapseRack の出力を TouchDesigner で利用でき、TD側のみでもVJが出来ます。

このリポジトリは、SynapseRackとTouchDesigner または TouchDesignerのみで
すぐにVJできるスターターテンプレートです。
SynapseRackだけでなく拡張的にTouchDesignerに挑戦したい人におすすめのリポジトリです。

### ✨ 特徴
- SynapseRack の各アウトプットを TD で自動受信
- SynapseRack → TouchDesigner → Spout のパイプラインに対応
- 軽量構成のため長時間の VJ セットでも安定(GPUエフェクトを使わない限り)

### 📂 内容
- `toeファイル` : SynapseRack連携済みのTouchDesignerプロジェクトファイル
(バックアップの際に勝手にナンバリングされてるので勝手にリネームしてください)
以下の引用元のEffects(in toe)が使用されています。

- `SampleMovie/` : 初期でTouchDesignserの4レイヤーにパスがここにアサインされてます。
                   二次配布での規約違反が怖いのでsora2の適当な動画入れてます。

- `システムマップ.png` : ノード構成図

- `APCMiniMK2アサインマップ.png` : デフォルトでアサインされているAKAI APC mini(midiコン)でのマップ
<img width="1280" height="720" alt="システムマップ" src="https://github.com/user-attachments/assets/84dfd005-d7bd-42fa-bf6c-25838b6f2e23" />
<img width="1280" height="720" alt="APCMiniMK2アサインマップ" src="https://github.com/user-attachments/assets/d2870b06-639e-46fb-aedb-4a25c2a3a38b" />


### 📎 引用元
- Effects(in toe) [mediapipe-touchdesigner
](https://github.com/torinmb/mediapipe-touchdesigner.git)
- Effects(in toe) [learningGLSL](https://github.com/raganmd/learningGLSL.git)
- Effects(in toe) [touchFluid](https://github.com/kamindustries/touchFluid.git)
- Effects(in toe) [GenerativeDesign](https://github.com/TouchDesigner/GenerativeDesign.git)


### 🚀 使い方
1. SynapseRack を起動(先に開かないとTDでしかmidiコンが使えません)
2. TouchDesigner を開き、toeファイル を読み込む  
3. midiコン接続確認・アサイン
4. VJ_HUBの4レイヤー付近に移動
5. 素材を入れる
6. 出力確認して使用！

### 🛠 推奨環境
- TouchDesigner 2023 以降
- SynapseRack 最新版 最新情報はココから確認(https://synapserack.com/docs/contact/)
- NVIDIA GPU 搭載 Windows 環境（推奨）

### 内容の詳細

### link: https://note.com/soupon2gou2/n/n7704747069c7?sub_rt=share_pw

この記事は2025VJアドカレに参加してます。
https://adventar.org/calendars/11668

### 📮 連絡先
X(旧Twitter) : ソウポン2号(@Soupon2gou) 

Discord : Soupon2gou

不具合や違反があったら連絡お願いします。
