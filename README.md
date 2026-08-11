# Media & IP Industry Financial Cost Structure Dashboard (2024–2025)

An interactive financial intelligence dashboard analyzing the cost structure, fixed-cost ratios, content investments, and business models of 15 major media and entertainment companies across Japan, the US, and Europe.

日本の民放キー局5社と、国内外のメガIPホルダー（東映・東宝）、ハリウッド主要スタジオ（WBD・Paramount・Comcast/NBCU・Sony Pictures）、Super Indies（Banijay・Fremantle）、グローバル配信（Disney・Netflix）の計15社の財務コスト構造（コンテンツ投資額 vs 固定費比率 vs 事業規模）を可視化するインタラクティブな分析ダッシュボードです。

---

## 🌐 Live Dashboard

* **Web公開URL**: [https://naohisastry.github.io/media-ip-financial-dashboard/](https://naohisastry.github.io/media-ip-financial-dashboard/)
  *(※リポジトリ名に応じて適宜設定されます)*

---

## 🏷️ Keywords

Media Industry, Financial Analysis, Cost Structure, Fixed Cost Ratio, Content Investment, Arms Dealer Model, Cost-Plus Production, SVOD, Broadcasters, Hollywood Studios, Super Indies, Chart.js, Financial Dashboard, Market Intelligence

民放キー局, メガIP, ハリウッドスタジオ, Super Indies, グローバル配信, 財務分析, コスト構造, 固定費比率, 番組制作費, コンテンツ投資, 損益分岐点, 製作委員会, アセットライト

---

## 📊 ダッシュボードの主な機能 (Key Features)

### 1. コスト構造・財務体質ポジショニングマップ（散布図）
* **X軸（年間コンテンツ投資額）**: 攻めの規模を対数スケール（初期 100億円〜5兆円）で表現。自社リスク投資枠ベース。
* **Y軸（自社固定費比率）**: 費用の身軽さを0%〜100%反転表示（上端0%＝身軽・変動費型 ／ 下端100%＝重厚・高固定費型）。
* **バブル面積（コンテンツ部門売上高）**: 各社の映像・コンテンツ事業セグメント外部売上高を面積比例で表現（不動産・通販・テーマパーク等の非コンテンツ事業を厳格除外）。

### 2. 比較フォーカス（横軸動的オートズーム機能）
* 画面上部のクイックフィルターボタン（「民放キー局」「国内メガIP」「Super Indies」「ハリウッド」「グローバル配信」「全体比較」等）または凡例（Legend）をクリックして対象を切り替えるたびに、**表示中データの最小・最大値に合わせて横軸（X軸）スケールが自動的に最適ズーム・再計算**されます。

### 3. 5大財務体質インサイトカード
* **🔴 民放キー局**: 高固定費（平均78.6%）・電波インフラ型
* **🔵 国内メガIP・映画**: アセットライト（固定費30〜35%）・製作出資型
* **🟡 Super Indies**: グローバル受託（固定費18〜20%）・変動費（Cost-plus）型
* **🟣 ハリウッド・スタジオ**: メガ制作・Arms Dealer（外部供給）型
* **🟢 グローバル配信**: 直販D2C・超巨大投資（年2.4〜3.8兆円）型

### 4. 財務指標データ一覧（確定値テーブル）
* 全15社の公表連結売上高、除外事業の内訳・金額、採用部門売上高、営業利益/EBITDA（マージン）、年間コンテンツ投資額、固定費比率を一覧比較。

### 5. 主要出典情報カード（個別エビデンス＆推計注記）
* 各社の有価証券報告書、決算説明資料、SEC Form 10-K、Euronext開示等の【公表一次開示数値（確定実績値）】引用文と、【推計・加工注記】を明記。公式開示への直リンク付き。

---

## 🛠️ プロジェクトファイル構成

本プロジェクトは、外部サーバー不要でブラウザ単体で完全に動作する静的シングルページWebアプリケーション（SPA）です。

```text
├── index.html          # ダッシュボード本体（HTML5 / Vanilla CSS / Chart.js / JSロジック）
├── README.md           # プロジェクト概要・機能説明・ライセンス
├── DATA_SOURCES.md     # 公式一次開示資料・原本アーカイブ一覧
├── METHODOLOGY.md      # 財務データ定義・固定費比率算定モデル・制約事項
└── CHANGELOG.md        # 更新履歴とバージョニング
```

---

## 📚 Documentation / 関連ドキュメント

* [DATA_SOURCES.md](DATA_SOURCES.md) — 各社グループ別の公式開示資料、一次ソースリンク、原本保管情報
* [METHODOLOGY.md](METHODOLOGY.md) — 財務データ定義、非コンテンツ事業除外基準、固定費算定モデル、制約事項
* [CHANGELOG.md](CHANGELOG.md) — バージョン更新履歴

---

## 🚀 ローカル起動方法

特別なサーバー設定やインストール作業は不要です。

1. 本リポジトリをダウンロードまたはクローンします。
2. `index.html` をお使いのWebブラウザ（Google Chrome, Microsoft Edge, Safari, Firefoxなど）で開きます。

---

## 📝 版権・著作権 (Copyright & License)

© 2026 Naohisa Hashimoto. All rights reserved.

本ダッシュボードに掲載されている財務データは、各社の有価証券報告書、決算説明資料、SEC Form 10-K等の公式公表資料に基づいて収集・算定したものです。
