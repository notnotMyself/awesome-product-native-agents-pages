# GitLab × AI 首次上手教程

这是 `GitLab × AI 使用指引` 的公开 GitHub Pages 发布仓库。

在线访问：<https://notnotmyself.github.io/awesome-product-native-agents-pages/>

教程面向第一次使用 GitLab 与本地 AI 工具协作的成员，覆盖：

- 登录并配置个人访问令牌
- 由业务负责人复制提示词，让 AI 在 `L3-AI-Native / Design System` 创建业务仓库并上传已沉淀项目
- 复制项目地址并交给本地 AI 工具
- 同时准备 Shared 与业务目录并启动本地服务
- 从最新 `main` 创建任务分支
- 修改、检查、提交与推送任务分支
- 由业务负责人维护正式知识资产，通过合并请求审核后进入 `main`
- 在 SOP 之外查看真实小布笔记 Storybook 成果，以及新建业务、功能迭代和负责人接手三个案例

## 内容边界

本仓库只保存公开教程站点及其白名单图片，不保存原项目中的 Agent 定义、内部文档或其他业务资料。

站点源码位于 `pages/`；GitHub Actions 只会把这个目录发布为 Pages 站点。

业务仓库应统一创建在 `L3-AI-Native / Design System` 下。这个个人项目仅用于公开教程的 Pages 发布，不作为业务仓库归属示范。

## 发布

向 `main` 推送后，`.github/workflows/pages.yml` 会自动构建并发布 GitHub Pages。
