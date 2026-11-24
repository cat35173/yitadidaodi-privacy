# 一塌到底 · 隐私政策

《一塌到底》（Android 版 v1.2）的隐私政策页面，用于 TapTap 开发者中心「APK 隐私合规」配置项的隐私政策链接。

## 目录

| 文件 | 说明 |
| --- | --- |
| `index.html` | 隐私政策页面（GitHub Pages 首页，手机/桌面自适应） |
| `隐私合规-填报清单.md` | TapTap 后台逐项怎么填 + 可直接粘贴给审核的权限/SDK 清单与话术 |

## 启用 GitHub Pages（给出公网链接）

1. 打开本仓库 → **Settings** → 左侧 **Pages**。
2. `Build and deployment` → Source 选 **Deploy from a branch**。
3. Branch 选 `main`，目录选 `/ (root)`，点 **Save**。
4. 等 1–2 分钟，地址为：

```
https://<你的用户名>.github.io/<仓库名>/
```

5. 把这个地址填到 TapTap 后台「APK 隐私合规 → 隐私政策链接」。

## 应用事实（与本政策一致）

- 包名 `com.yitadidaodi.ta`，versionCode 2 / versionName 1.2
- AndroidManifest **未声明任何权限**（含 `INTERNET`），应用全程离线
- 不收集任何个人信息；无账号、无定位、无设备标识、无统计埋点
- 未集成任何第三方 SDK；无广告
- 本地数据仅为游戏进度（WebView localStorage），卸载即删除
- 应用内隐私政策入口：设置 → 隐私政策（内置 `assets/privacy.html`，内容与本页一致）

## 更新记录

| 日期 | 版本 | 说明 |
| --- | --- | --- |
| 2026-11-24 | v1.2 | 首次发布隐私合规页；补全开发者信息与联系方式，移除「请填写」占位 |
