# helm-chart

## ディレクトリ構成

```
.
├── charts  # Helmチャートのルートディレクトリ
│   ├── applications  # ビジネスアプリケーションのチャート
└── clusters  # Argo CDのApplicationマニフェスト
    ├── applicationsets  # ApplicationSetマニフェスト
    ├── development  # developmentクラスタのApplicationマニフェスト
    ├── management  # managementクラスタのApplicaitonマニフェスト
    └── root-app.yaml  # App of appsパターンの親アプリマニフェスト
```
