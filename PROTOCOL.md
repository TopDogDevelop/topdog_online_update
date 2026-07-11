# TopDog Online Update Protocol

静态内容热更目标仓（Top Dog）。

- 版号：`YYYY.M.D.vN`（当前：`2026.7.11.v1`）
- 流程：`GET version.json` → `manifest.json` → 按清单下载 `content/**`
- 联机：双方本地 `contentVersion` 字符串必须一致（可都过时）

## 索取基址

- raw：https://raw.githubusercontent.com/TopDogDevelop/topdog_online_update/main/
- Pages：https://topdogdevelop.github.io/topdog_online_update/
