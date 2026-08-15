# 万灵 (WanLing)

诛仙世界辅助工具 · 绿色便携版。

## 下载

请到 [Releases](https://github.com/MyMoonCat/WanLing/releases) 下载最新 `WanLing.exe`。

## 自动更新

客户端启动时会静默检查本仓库最新 Release 中的 `latest.json`：

```json
{
  "version": "1.0.1",
  "url": "https://github.com/MyMoonCat/WanLing/releases/download/v1.0.1/WanLing.exe",
  "sha256": "..."
}
```

清单地址：`https://github.com/MyMoonCat/WanLing/releases/latest/download/latest.json`

用户数据在 `%LocalAppData%\万灵`，替换 exe 不会清空配置。

## 发布新版本

在构建出的绿色 `WanLing.exe` 上执行：

```powershell
.\ZhuXianFishingCpp\tools\publish_release.ps1 -ExePath .\WanLing.exe -Version 1.0.1
```

## 仓库用途

公开 Release 托管与版本清单；源码可另存私有库维护。