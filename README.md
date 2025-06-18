# helm-chart

## ディレクトリ構成

```
.
├── charts  # 独自Helmチャート配置用ディレクトリ
├── clusters  # Argo CDのApplicationマニフェスト配置用ディレクトリ
│   ├── common  # ApplicationSetマニフェスト配置用ディレクトリ
│   ├── development  # developmentクラスタのApplicationマニフェスト配置用ディレクトリ
│   ├── management  # managementクラスタのApplicaitonマニフェスト配置用ディレクトリ
│   └── root-app.yaml  # App of appsパターンの親アプリマニフェスト
└── values
    ├── external  # 外部チャートのvalues配置用ディレクトリ
    └── internal  # 独自チャートのvalues配置用ディレクトリ
```
