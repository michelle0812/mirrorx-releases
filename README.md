# MirrorX 發布通道

這個 repo 只放 MirrorX 的發布產物，**不含原始碼**。

- `latest.json`：目前最新版本的資訊（版本號、下載網址、SHA-256）
- Release 附件：各版本的 `.dmg`

原始碼在 [michelle0812/mirrorx](https://github.com/michelle0812/mirrorx)（私有）。

## latest.json

MirrorX App 會讀 `main` 分支根目錄的 `latest.json` 來檢查更新：

```
https://raw.githubusercontent.com/michelle0812/mirrorx-releases/main/latest.json
```

這個檔案由 `mirrorx release` 自動產生，不要手動編輯。

## 下載

最新版：https://github.com/michelle0812/mirrorx-releases/releases/latest
