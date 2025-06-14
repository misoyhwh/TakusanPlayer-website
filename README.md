# Takusan Player Website

Apple Store公開用のサポートサイト for Takusan Player - Apple Vision Pro専用マルチ動画プレイヤー

## Site Overview

This website serves as the support URL required for App Store review and provides information about the Takusan Player app.

## ファイル構成

```
TakusanPlayerWebsite/
├── index.html              # メインページ
├── support.html             # サポートページ（App Store必須）
├── privacy.html             # プライバシーポリシー（App Store必須）
├── css/
│   └── style.css           # メインスタイルシート
├── js/
│   └── script.js           # JavaScript機能
├── images/                 # 画像ファイル（準備必要）
│   ├── logo.png
│   ├── hero-mockup.png
│   ├── screenshot-1.png
│   ├── screenshot-2.png
│   ├── screenshot-3.png
│   ├── app-store-badge.png
│   ├── apple-touch-icon.png
│   ├── favicon-32x32.png
│   └── favicon-16x16.png
└── README.md               # このファイル
```

## 機能

### 🏠 メインページ (index.html)
- アプリの概要と主要機能紹介
- スクリーンショットギャラリー
- App Storeダウンロードリンク
- レスポンシブデザイン

### 🛠️ サポートページ (support.html)
- よくある質問（FAQ）
- トラブルシューティング
- システム要件
- お問い合わせ情報

### 🔒 プライバシーポリシー (privacy.html)
- データ収集・使用に関する詳細説明
- App Store審査要件に完全準拠
- 日本語での詳細な説明

## GitHub Pagesでの公開方法

### 1. GitHubリポジトリの作成
```bash
# 新しいリポジトリを作成
git init
git add .
git commit -m "Initial commit: Takusan Player website"
git branch -M main
git remote add origin https://github.com/yourusername/takusan-player-website.git
git push -u origin main
```

### 2. GitHub Pagesの有効化
1. GitHubリポジトリの「Settings」タブを開く
2. 左メニューから「Pages」を選択
3. 「Source」で「Deploy from a branch」を選択
4. 「Branch」で「main」を選択し「Save」をクリック

### 3. アクセスURL
公開後のサイトURL: `https://yourusername.github.io/takusan-player-website/`

## 必要な画像ファイル

以下の画像ファイルを `images/` フォルダに追加してください：

### アプリアイコン・ファビコン
- `TakusanPlayer-icon.png` - アプリアイコン（ロゴ・ファビコン・Apple Touch Icon共通）

### スクリーンショット
- `TakusanPlayer01.png` - ヒーローセクション用・メイン制御パネル
- `TakusanPlayer02.png` - マルチ動画表示
- `TakusanPlayer03.png` - ブラウザ統合

### App Store素材
- `app-store-badge.png` - App Store Download Badge

## カスタマイズポイント

### 連絡先情報の更新
以下のファイルで連絡先情報を実際の情報に更新してください：

1. **index.html**
   - `support@takusanplayer.com` → 実際のサポートメール
   - GitHub URL → 実際のリポジトリURL

2. **support.html**
   - メールアドレス
   - GitHub Issues URL
   - サポート対応時間

3. **privacy.html**
   - 連絡先メールアドレス
   - 最終更新日

### App Store URL
App Store公開後、以下のリンクを実際のURLに更新：
- `https://apps.apple.com/app/takusan-player`

## App Store審査での使用

### サポートURL
App Store Connectでの「サポートURL」に以下を入力：
```
https://yourusername.github.io/takusan-player-website/support.html
```

### プライバシーポリシーURL
App Store Connectでの「プライバシーポリシーURL」に以下を入力：
```
https://yourusername.github.io/takusan-player-website/privacy.html
```

## ブラウザ対応

- Chrome 90+
- Safari 14+
- Firefox 88+
- Edge 90+

## レスポンシブ対応

- デスクトップ (1200px+)
- タブレット (768px-1199px)
- スマートフォン (~767px)

## ライセンス

MIT License - 詳細は[LICENSE](LICENSE)ファイルを参照

---

**注意**: 実際の公開前に、すべての連絡先情報、URL、画像ファイルを適切に更新してください。