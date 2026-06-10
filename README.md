# 英雄联盟 — 全英雄技能总览

一个纯静态的英雄联盟英雄技能查看器，收录所有英雄的技能图标、技能说明和官方演示视频，支持按位置/职业快速筛选。

## 功能

- **英雄浏览** — 侧边栏列出全部英雄，点击即可查看技能详情
- **标签筛选** — 按刺客、战士、法师、射手、辅助、坦克等职业快速过滤
- **搜索** — 支持英雄名称搜索
- **技能展示** — 每个英雄展示被动 + Q/W/E/R 技能，含图标和文字说明
- **技能视频** — 使用 Riot 官方在线视频地址，无需下载
- **自带图标** — 仓库内置英雄头像和技能图标，不依赖外部图床

## 快速使用

部署到 **GitHub Pages** 即可直接访问：

1. 仓库 Settings → Pages → Source 选 `Deploy from a branch`
2. Branch 选 `master`，目录选 `/ (root)`
3. 保存后等待一两分钟，访问 `https://wizenard.github.io/LOL_WIKI`

或者本地直接用浏览器打开 `index.html`。

## 文件说明

| 文件 | 说明 |
|---|---|
| `index.html` | 主页面入口 |
| `champions_github.html` | 备用入口（内容相同） |
| `lol_github_assets/champions/` | 英雄头像图片 |
| `lol_github_assets/spells/` | 技能图标图片 |
| `.nojekyll` | 确保 GitHub Pages 正确处理静态文件 |