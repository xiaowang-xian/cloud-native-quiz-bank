# 云原生命令模拟答题器（校招秋招版）

校招秋招云原生高频题练习器：Linux / Ansible / Kubernetes / Docker / Shell / MySQL / Git / 运维 / 运维开发 / 计算机基础 / 网络协议 / 面试场景 十二大模块，命令模拟作答 + 八股问答。

## 直接打开（手机 / 电脑通用）

- 长期链接（跟随更新）：https://cdn.jsdelivr.net/gh/xiaowang-xian/cloud-native-quiz-bank@main/index.html
- 固定版本链接（内容锁定）：https://cdn.jsdelivr.net/gh/xiaowang-xian/cloud-native-quiz-bank@f7eb92b4c4fd90b1e808c79b4a7344a36cabdd9f/index.html

## 特性

- 322 道题：命令操作题 141 + 问答八股 181
- 11 大模块独立练习（含网络协议专题深挖、面试场景综合题）
- 命令输入模拟：回车执行、Shift+Enter 换行、相似度判定、评分与提示
- 题库浏览：按科目 / 题型筛选、关键词搜索
- 答题进度保存在本机浏览器（localStorage），可离线使用
- 深色终端主题，手机端自适应

## 部署说明

- 纯前端单页应用；题库经 gzip 压缩后分块存放于 `_chunks/`，入口 `index.html` 为 loader，浏览器端用 DecompressionStream 解压渲染。
- 本仓库作为长期托管载体，通过 jsdelivr CDN 分发，不依赖任何后端服务。
