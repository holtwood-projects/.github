# 参与贡献

感谢你愿意为 Build Workbench 组织下的项目做出贡献!这是一个由个人维护、面向教学与学习的小型组织,简单的规则就能让协作顺畅。

## 通用约定

- **语言**:Issue / PR 使用中文或英文均可;代码中的标识符与注释建议保持项目原有语言习惯。
- **代码风格**:遵循各仓库已有的 lint / format 配置(Prettier、ESLint、rustfmt、clang-format 等)。
- **提交信息**:建议遵循 [Conventional Commits](https://www.conventionalcommits.org/)(`feat:` / `fix:` / `docs:` / `refactor:` / `chore:` …)。

## 提 Bug / 建议

- 先搜索现有 Issues,避免重复。
- 使用各仓库提供的 Issue 模板(bug 报告请附上复现步骤、环境、日志)。

## 提交代码

1. **Fork** 目标仓库并基于 `main` 分支创建功能分支(`git checkout -b feat/my-feature`)。
2. 小步提交,提交信息清晰。
3. 运行项目的 lint 与测试,确保全部通过(见各仓库 README 的构建说明)。
4. 发起 Pull Request,使用模板描述变更;如有关联 Issue 请 `Closes #xxx`。

### 贡献规范速查

| 场景 | 要求 |
|------|------|
| 新增功能 | 附带测试与文档(README 或 docs/) |
| Bug 修复 | 附上复现方式,说明修复思路 |
| 文档 | 保持语言风格与既有文档一致 |

## 行为准则

参与本项目即表示你同意遵循组织的 [CODE_OF_CONDUCT](https://github.com/holtwood-projects/.github/blob/main/CODE_OF_CONDUCT.md)。

## 问题?

在每个仓库的 Issues 中提问即可,我们会尽快回复。
