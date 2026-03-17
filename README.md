# Microsoft Graph 3D Visualization

> Microsoft Graph API の全体像を、インタラクティブな 3D グラフとスライドで直感的に理解できるデモサイトです。

🔗 **デモ**: [https://icy-ocean-07678e700.2.azurestaticapps.net](https://icy-ocean-07678e700.2.azurestaticapps.net)

![Microsoft Graph 3D Visualization](https://img.shields.io/badge/Azure-Static%20Web%20Apps-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## どんなデモ？

ふだん使っているメール・予定表・ファイル・チャット。これらを裏側でつないでいる **Microsoft Graph** の構造を、3D ビジュアライゼーションで可視化します。

| 左パネル | 右パネル |
|:--|:--|
| スライド形式のプレゼンテーション（全 6 ステップ） | Three.js による 3D グラフ表示 |

### スライド構成

| # | テーマ |
|---|--------|
| 0 | Microsoft Graph とは |
| 1 | ユーザー中心のデータモデル |
| 2 | Graph の仕組み（REST API） |
| 3 | Microsoft 365 コアサービス |
| 4 | Enterprise Mobility + Security |
| 5 | まとめ — データ構造化の重要性 |

### 主な機能

- **3D ノード・エッジ可視化** — Microsoft Graph の各リソースとつながりを立体的に表示
- **レイヤー切り替え** — M365 コアサービス / EMS をフィルタリング
- **インタラクティブ操作** — ノードのホバーで API パスや詳細を表示
- **ストーリーナビゲーション** — スライドに連動してカメラアングルが変化

## 使い方

ブラウザで開くだけで動作します。ビルドツールやサーバーは不要です。

```bash
# ローカルで開く
start index.html    # Windows
open index.html     # macOS
```

## 技術スタック

| 技術 | 用途 |
|------|------|
| HTML / CSS / JavaScript | 単一ファイル構成 |
| [Three.js](https://threejs.org/) | 3D レンダリング |
| [Azure Static Web Apps](https://azure.microsoft.com/services/app-service/static/) | ホスティング |
| GitHub Actions | CI/CD 自動デプロイ |

## ライセンス

MIT
