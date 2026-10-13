# hello-github

这个仓库是用 `gh` 命令行工具创建的，用来验证 GitHub 环境是否配置正确。

## 环境

| 项目 | 版本 |
|---|---|
| macOS | 26.0.1 (Apple Silicon) |
| git | 2.50.1 (Apple Git-155) |
| gh | 2.102.0 |
| Xcode 命令行工具 | 26.6.0 |

## 测试了什么

- [x] 本地 `git init` / `add` / `commit`
- [x] `gh repo create` 创建远程仓库
- [x] `git push` 推送到 GitHub
- [x] HTTPS 凭证走 `gh auth git-credential`

验证通过在 github.com 上能看到这个文件为准。

---

## SSH 推送测试

本次提交通过 SSH (git@github.com) 推送，端口 22。
时间: 2026-10-14 00:04:45
