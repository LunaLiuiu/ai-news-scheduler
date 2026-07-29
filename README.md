# AI News Scheduler

每日自动搜索 GitHub 上 AI 相关的最新消息，生成报告并归档。

## 功能

- 🕘 每日北京时间 9:10 自动执行
- 🔍 搜索 GitHub Trending AI 项目
- 📦 跟踪 AI/LLM 最新动态
- 📁 按日期归档报告到 `reports/` 目录
- 📄 最新报告始终在 `latest.md`

## 查看报告

- 最新报告：[`latest.md`](latest.md)
- 历史报告：[`reports/`](reports/) 目录

## 手动触发

在仓库的 Actions 页面点击 "Run workflow" 即可手动执行。

## 自动过期

此仓库计划运行 3 个月（至 2026-10-29），届时可手动禁用 workflow。
