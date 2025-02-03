# DevContainers用のテンプレート

## 構成
```
.
├── .devcontainer
│   ├── compose.yml
│   ├── devcontainer.json
│   ├── dockerfile
│   └── init.sh
└── README.md
```
- ./devcontainer.json
追加する拡張機能と、設定を追記
- ./init.sh
コンテナ起動時に実行されるシェルスクリプト
`pip install`,`npm install`等を記載
