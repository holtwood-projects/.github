# holtwood-projects/.github

本仓库承载 **holtwood-projects 组织级社区健康文件**与组织主页，本身不含业务代码。

## 内容

| 路径 | 作用 |
|------|------|
| `profile/README.md` | 组织主页（显示在 <https://github.com/holtwood-projects>） |
| `CONTRIBUTING.md` | 贡献指南，作为全组织仓库的默认值 |
| `CODE_OF_CONDUCT.md` | 行为准则 |
| `SECURITY.md` | 安全策略与漏洞上报方式 |
| `ISSUE_TEMPLATE/` | 全组织默认 Issue 模板 |
| `PULL_REQUEST_TEMPLATE.md` | 全组织默认 PR 模板 |

## 生效方式

GitHub 会将这些文件作为**组织内所有仓库的默认值**：当某个仓库没有自己的同名文件时，自动启用这里的版本。因此修改此处会影响到组织下全部仓库。

## 维护约定

- 新增 / 重命名项目时，**必须同步更新** `profile/README.md`，并与门户站点 [`holtwood-projects.github.io`](https://github.com/holtwood-projects/holtwood-projects.github.io) 的 `index.html` 保持一致。
- 修改后需 commit 并 push 到 `main` 分支。
- 完整的组织维护规范见本地工作区的 `AGENTS.md`。
