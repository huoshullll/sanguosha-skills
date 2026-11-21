# sanguosha-skills

新月杀（FreeKill）武将技能在线查询页 —— 固定网址：https://huoshullll.github.io/sanguosha-skills/

## 更新方式

1. 页面文件必须叫 `index.html`，放在仓库根目录（改名会 404）。
2. 用新版覆盖同名文件后提交，GitHub Pages 会在 1–2 分钟内自动重建，网址不变。
3. 提交前确认页面已去掉豆包导出的运行时 SDK（水印/埋点/评论 iframe），本仓库里维护的是纯静态版。
4. 验证：`curl -sI https://huoshullll.github.io/sanguosha-skills/ | head -1` 返回 200，且返回字节数与本地文件一致。

## 站点设置

- Pages 源：Deploy from a branch，`main` 分支 `/ (root)`
- 仓库可见性：Public（免费 Pages 不支持私有仓库）
