# hello-git

本地 Git + GitHub 接通后的第一个仓库。

## 当前环境

| 项目 | 值 |
| --- | --- |
| Git | 2.56.0.windows.3（C:\Program Files\Git） |
| 默认分支 | main |
| 提交身份 | yanxing-debug / 3653854796@qq.com |
| 认证方式 | SSH ed25519，经 ssh.github.com:443 |
| 密钥指纹 | SHA256:bUNZRryhvoZhw4IURNvBRJa4Rji+Ubo1WnUu+RLv5jI |

## 常用命令

```bash
git status                 # 看当前改动
git add .                  # 暂存全部改动
git commit -m "说明"       # 提交
git push                   # 推到 GitHub
git pull                   # 拉取远端更新
git log --oneline --graph  # 看提交历史
```

## 首次推送到 GitHub

先在 GitHub 上新建一个**空仓库**（不要勾选 README、.gitignore、License），然后：

```bash
git remote add origin git@github.com:yanxing-debug/hello-git.git
git push -u origin main
```
