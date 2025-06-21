# 株式会社 コーポレートサイト

参考サイト：[https://www.kk-bright.com/company](https://www.kk-bright.com/company) をベースに制作したコーポレートサイトです。

## 概要

シンプルで洗練されたデザインの企業サイトです。レスポンシブ対応でPC・タブレット・スマートフォンすべてのデバイスで最適に表示されます。

## ページ構成

- **トップページ** (`index.html`) - 企業の概要とサービス紹介
- **会社紹介** (`pages/about.html`) - 企業理念、歴史、経営陣紹介
- **地図** (`pages/map.html`) - アクセス情報と地図
- **お問い合わせ** (`pages/contact.html`) - 問い合わせフォームとよくある質問
- **採用情報** (`pages/careers.html`) - 求人情報と福利厚生
- **会社概要** (`pages/profile.html`) - 基本情報、事業内容、沿革

## 特徴

### デザイン
- シンプルで清潔感のあるデザイン
- ブルー系のカラーパレット（#2c5aa0）を使用
- 白を基調とした背景で視認性を向上

### 機能
- 完全レスポンシブ対応
- ハンバーガーメニュー（モバイル対応）
- スムーズスクロール機能
- お問い合わせフォームのバリデーション
- SEO最適化

### SEO対策
- 各ページにメタタグ設定
- 構造化データ（JSON-LD）実装
- sitemap.xml作成
- robots.txt設置
- OGP（Open Graph Protocol）対応

## ファイル構成

```
corporate-website/
├── index.html              # トップページ
├── sitemap.xml            # サイトマップ
├── robots.txt             # ロボット制御ファイル
├── README.md              # このファイル
├── css/
│   └── style.css          # スタイルシート
├── js/
│   └── script.js          # JavaScript
├── images/                # 画像ファイル用ディレクトリ
└── pages/
    ├── about.html         # 会社紹介
    ├── map.html           # 地図・アクセス
    ├── contact.html       # お問い合わせ
    ├── careers.html       # 採用情報
    └── profile.html       # 会社概要
```

## 技術仕様

- **HTML5** - セマンティックなマークアップ
- **CSS3** - Grid Layout、Flexbox、アニメーション
- **JavaScript** - バニラJS（フレームワーク不使用）
- **レスポンシブ** - モバイルファースト設計

## カスタマイズ方法

### 会社情報の変更
各HTMLファイル内の以下の情報を実際の会社情報に変更してください：

- 会社名
- 住所
- 電話番号
- メールアドレス
- 設立年
- 事業内容

### 色の変更
`css/style.css`内の以下の色コードを変更：

```css
/* メインカラー */
color: #2c5aa0;
background-color: #2c5aa0;

/* ホバー時の色 */
background-color: #1e3d6f;
```

### 地図の実装
`pages/map.html`内のマップ部分は現在プレースホルダーになっています。
実際の実装にはGoogle Maps APIを使用してください。

## ブラウザ対応

- Chrome（最新版）
- Firefox（最新版）
- Safari（最新版）
- Edge（最新版）
- Internet Explorer 11以上

## 注意事項

- 画像ファイルは`images/`ディレクトリに配置してください
- 実際の運用時は、プレースホルダーの内容を実際の情報に置き換えてください
- Google Mapsの実装には別途APIキーが必要です
- お問い合わせフォームは現在フロントエンドのみの実装です。実際の送信機能にはサーバーサイドの実装が必要です

## ライセンス

このプロジェクトはMITライセンスの下で公開されています。