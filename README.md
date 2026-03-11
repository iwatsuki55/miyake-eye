# 🏥 眼科三宅病院 DX プロジェクト｜PM タスク管理

院内デジタル化・属人化業務マニュアル化を管理するPMツールです。  
HTMLファイル1枚で動作し、サーバー不要でブラウザから使えます。

## 🚀 GitHub Pages で見る

👉 **https://&lt;your-username&gt;.github.io/miyake-dx-pm/**

## 📋 機能

| 機能 | 説明 |
|------|------|
| 📋 タスク一覧 | タスクの追加・編集・削除、検索・フィルター |
| 📅 ガントチャート | 3〜9月のスケジュールをビジュアル表示 |
| 📤 エクスポート | CSVダウンロード・クリップボードコピー |
| 🗓 カレンダーピッカー | 開始日・完了予定日をクリックで選択 |
| 🔽 ドロップダウン | ステータス・優先度をリストから選択 |

## 🗂 プロジェクト構成

```
miyake-dx-pm/
├── index.html   # メインアプリ（これ1枚で完結）
└── README.md
```

## 💻 ローカルで使う

```bash
git clone https://github.com/<your-username>/miyake-dx-pm.git
# index.html をブラウザで開くだけ
open index.html
```

## 🌐 GitHub Pages で公開する手順

1. このリポジトリを GitHub に push
2. リポジトリの **Settings → Pages**
3. Source を `main` ブランチの `/ (root)` に設定
4. **Save** → 数分後に公開URL が発行される

## 📁 タスク追加はチャットで

Claudeのチャットに以下のテンプレートを貼って送るだけで更新できます。

```
プロジェクト：P1（院内デジタル化）/ P2（属人化マニュアル化）/ 新規（名前：〇〇）
フェーズ：既存フェーズ名 または 新規（名前：〇〇）
タスク名：〇〇
担当者：〇〇（省略可）
優先度：高 / 中 / 低
開始日：YYYY/MM/DD
完了予定日：YYYY/MM/DD
備考：〇〇（省略可）
```

---

*Powered by Claude / Anthropic*
