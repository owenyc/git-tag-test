# git-tag-test

模拟 MateClaw 二次开发 + 上游同步演练项目（不包含真实业务代码）。

## 仓库规则（与 MateClaw 上游一致）

- 默认分支：`dev`（活跃开发主干）
- 另有 `main` 分支
- 发布方式：tag（v1.0.0 / v1.1.0 ...），无 release 分支

## 目录结构（模拟 MateClaw monorepo）

```
mateclaw-server/    Spring Boot 后端（模拟）
mateclaw-ui/        Vue 3 前端（模拟）
mateclaw-desktop/   Electron 桌面端（模拟）

## v1.1.0 更新（模拟上游新版本）

- 后端依赖升级
- 前端页面优化
```
