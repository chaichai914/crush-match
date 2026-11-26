# 用 GitHub Desktop 发布（3 分钟）

这个文件夹已经是一个本地 Git 仓库，不要重新 init。

1. 打开 GitHub Desktop。
2. 菜单 File → Add Local Repository。
3. 选择：
   `D:\桌面\赛博日记\0-求职\crush-match-github`
4. 如果提示“not a Git repository”，确认文件夹里能看到 `.git`（隐藏文件夹）。
5. 右上角点 **Publish repository**。
6. Name 填 `crush-match`；
   **取消勾选 “Keep this code private”**（免费 GitHub Pages 需要公开仓库）。
7. 点 Publish。浏览器会打开你的 GitHub 仓库。
8. 在仓库页：Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / `(root)`
   - Save
9. 等 1—2 分钟，页面顶部会出现：
   `https://你的用户名.github.io/crush-match/`
10. 手机打开测试；正常后，把链接放到小红书群聊/私信/主页，不要放正文。

## 如果 404
- 等 2 分钟再刷新；
- 确认仓库根目录有 `index.html` 和 `.nojekyll`；
- Settings → Pages 里确认分支是 `main`、目录是 `/ (root)`；
- 如果仓库是 Private，改成 Public，或升级 GitHub Pro。

## 注意
- 发布按钮需要你的 GitHub 账号登录，我无法代点。
- 本地 `file://` 打开时，“复制结果链接”复制的是本地路径，不能发人；部署成 https 后才能当公网链接。
