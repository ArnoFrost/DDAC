# 贡献指南

感谢你对 DDAC 的关注与贡献！为了让协作更高效，请遵循以下流程与规范。

## 如何贡献
- 提交 Issue：
  - 选择合适的模板（Bug/建议/文档改进）
  - 提供简要复现步骤或改进动机
  - 附上相关链接（仅限公开仓库内的 `docs/*`、`templates/*`）
- 提交 Pull Request：
  - 从最新主分支创建特性分支：`feature/<topic>`、`fix/<topic>`
  - 关注最小变更原则（Small PR）
  - 关联 Issue（如有），在 PR 描述中说明动机与变更范围

## 变更范围
- 公开范围仅包含：`docs/*` 与 `templates/*`
- 禁止包含任何私有实现、个人信息或 `.internal/*` 路径

## 文档规范
- 使用 Markdown + YAML 头部（title/tags/updated）
- 标题层级清晰，尽量提供导航回到 `docs/01-核心概念.md`
- 链接范围合规：仅指向 `docs/*`、`templates/*`

## 提交规范
- 使用清晰的提交信息：
  - `docs: 更新实施指南章节`
  - `feat(template): 新增轻量路书模板`
  - `fix(docs): 修正死链`
- 每个提交尽量聚焦单一变更

## 审阅与合并
- 通过基础检查（语法、链接、死链）
- 由维护者进行内容一致性审阅
- 通过后合并至主分支并更新 `CHANGELOG.md`

## 行为准则
请遵循项目的《行为准则》（`CODE_OF_CONDUCT.md`）。

## 许可证
贡献内容遵循本项目许可证：CC BY-SA 4.0。