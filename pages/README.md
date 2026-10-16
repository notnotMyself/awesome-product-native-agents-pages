# GitLab Pages

此目录是 GitLab Pages 的公开站点源码。

- `index.html`：为什么使用 GitLab，以及面向新手的 GitLab × AI 完整首次上手 SOP。页面用非技术语言解释 GitLab 的通用 AI 入口、完整协作能力和唯一真理源价值，并提供可直接复制的 AI 提示词，覆盖登录与令牌、在固定 Group 建仓、上传 miniColorDesign 沉淀项目、准备 Shared + 业务本地目录、按案例创建任务分支、提交推送和合并请求维护 main。SOP 之后独立展示新建业务、功能迭代和负责人接手三个案例。业务仓库不得散落在个人空间，必须遵循 `L3-AI-Native / Design System`、负责人、可见范围和模板规则。
- `assets/`：GitLab 令牌配置的原始操作截图，以及从本地 miniColorDesign Storybook 真实运行页面截取的小布笔记 Design System 与页面 Story 截图。

`.gitlab-ci.yml` 只发布 `index.html` 和白名单截图资产。不要把整个 `pages/` 或 `docs/` 目录自动复制到 `public/`，避免未来的草稿或其他附件被意外公开。
