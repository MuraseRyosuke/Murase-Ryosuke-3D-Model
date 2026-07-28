# 🗿 村瀨亮介 3Dモデルライブラリ (Murase Ryosuke's 3D Model Package)

村瀨亮介が制作・提供する汎用3Dアセットパッケージです。オブジェクト・プロップ素材から、キャラクター・人物アバターまで幅広く展開していきます。VRChat、ゲーム開発、各種CGコンテンツ制作にご活用ください。

---

## 🌐 3D View (ブラウザプレビュー)

ブラウザ上で3Dモデルを360度回転・拡大し、インタラクティブに確認できます。

👉 **[Webブラウザで3Dモデルをプレビューする](https://MuraseRyosuke.github.io/Murase-Ryosuke-3D-Model/)**

### プレビュー機能
* **表示モード切替:** 標準 / ソリッド / ホログラム / メッシュ（ワイヤーフレーム）
* **回転・サイズ調整:** 自動回転 / 高速回転（🎠）/ 無段階スケール変更
* **背景カスタマイズ:** 背景色変更 / 背景画像設定 / **リアカメラ映像取り込み（パススルー）**
* **AR対応:** Apple AR Quick Look (iOS) / WebXR (Android) による現実空間へのAR配置
* **ダイレクトDL:** 表示中のモデル（.glb）を画面上から直接ダウンロード

### ⌨️ キーボードショートカット (PC環境向け)
* **3D位置移動 (前後左右):** `W` `A` `S` `D`
* **高さ移動 (上下):** `↑` `↓`
* **ポリゴン精度:** `1` (500p) / `2` (15k) / `3` (70k)
* **表示モード:** `N` (標準) / `R` (ソリッド) / `H` (ホログラム) / `M` (メッシュ)
* **回転制御:** `L` (通常回転) / `C` (高速回転)
* **スケール調整:** `+` / `-`
* **環境・背景:** `B` (色選択) / `P` (画像選択) / `Q` (初期化リセット)

---

## 📦 同梱データ仕様 (Package Details)

```text
Murase-Ryosuke-3D-Model/
├── models/
│   └── statue_bust/
│       ├── murase_statue_bust_500p_low.glb / .fbx / .obj
│       ├── murase_statue_bust_15k_standard.glb / .fbx / .obj
│       └── murase_statue_bust_70k_raw.glb / .fbx / .obj
└── docs/
    ├── index.html        # プレビュービューワー
    └── favicon.ico       # ファビコン
```

### 🗿 石膏胸像モデル (`/models/statue_bust/`)

Tripo AIを用いて制作した汎用石膏胸像データです。用途に合わせてポリゴン数・形式を選択できます。

| ファイル名 | ポリゴン数 (Tris) | 推奨用途 | フォーマット |
| :--- | :--- | :--- | :--- |
| `murase_statue_bust_70k_raw.*` | 約 70,000 | ハイエンドレンダリング、3Dプリント、改変元 | GLB, FBX, OBJ |
| `murase_statue_bust_15k_standard.*` | 約 15,000 | VRChat (Generic/Poorランク最適化)、ゲーム制作 | GLB, FBX, OBJ |
| `murase_statue_bust_500p_low.*` | 約 500 | 背景オブジェクト、モバイル環境、LOD | GLB, FBX, OBJ |

*(※全身モデル・追加アセットも本リポジトリにて順次展開予定です)*

---

## 🛠️ 制作環境・ベース技術 (Technologies & Tools)

* **Base Generation:** [Tripo AI](https://www.tripo3d.ai/)
* **Optimization & Cleanup:** Blender / Unity
* **Web Viewer:** Google model-viewer (WebXR / Three.js)

---

## 📥 利用・ダウンロード方法

1. **Web画面からダウンロード:**  
   [Webプレビュー](https://MuraseRyosuke.github.io/Murase-Ryosuke-3D-Model/) 上の「📥 DL」ボタンから、現在表示しているモデルの `.glb` データをワンタップで保存できます。
2. **個別ファイル取得:**  
   リポジトリ内の `/models/` 以下の各ディレクトリから、必要な形式（FBX, OBJ等）を直接ダウンロードしてください。
3. **一括取得:**  
   ページ右上の **[Code]** ボタン ➔ **[Download ZIP]** から全フォーマットを一元取得できます。

---

## 📜 利用規約 (Terms of Use)

詳細な規約内容は [LICENSE.md](./LICENSE.md) に記載しています。

* **商用・非商用利用:** 許可（VRChat、ゲーム開発、動画・配信、アート作品など）
* **改変・加工:** 許可（メッシュ削減、セットアップ変更、テクスチャ改変など自由）
* **再配布:** 条件付き許可（改変後の二次的配信は可。未改変のままの販売・無断転載は禁止）
* **クレジット表記:** 任意（表記いただける場合は `村瀨亮介 / Ryosuke Murase` とご記載ください）

---

## 👤 クレジット・作者情報 (Credits & Author)

* **3D Base Generator:** Tripo AI
* **製作者 / モデリング調整:** 村瀨亮介 (Ryosuke Murase)
