# dart-lsp

讓 Claude Code 使用 Dart SDK 內建的語言伺服器（`dart language-server`），
在編輯 `.dart` 檔後自動取得診斷，並支援跳轉定義、尋找引用、hover 型別資訊。

## 前置需求

`dart` 必須在 `PATH` 中。Flutter SDK 已內建 Dart，把 `<flutter>/bin` 加入 `PATH` 即可：

```bash
dart --version
```

## 安裝

```
/plugin marketplace add xubojun/claude-plugins
/plugin install dart-lsp@xubojun-plugins
```

安裝後重新啟動 Claude Code。
