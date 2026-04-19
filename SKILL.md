---
name: fiction-review
description: 对虚构文学作品进行系统审阅的项目内专用 skill，涵盖文学编辑、出版编辑、MBTI 读者评审、量化评分与修订建议流程。适用于小说稿件、大纲、设定文档与章节修订审稿。
license: CC-BY-NC
metadata:
  author: 田奈明紗
  version: "1.0"
  repository: novel-forge
  scope: project
  language: zh-CN
---

# 虚构文学编辑工作流

## 用途

本技能用于在 `novel-forge` 中对虚构文学作品进行系统审阅，整合：
- 文学编辑判断
- 出版编辑判断
- MBTI 读者反馈
- 量化评分与分歧分析

适用对象：
- 章节草稿
- 短篇 / 长篇稿件
- 大纲
- 人物设定
- 世界观设定
- 修订稿

## 使用流程

### 1. 收稿与确认本轮目标
确认：
- 作品名
- 材料类型
- 题材
- 当前阶段
- 作者本轮重点诉求
- 是否需要 MBTI 读者评审与量化评分

### 2. 文学编辑初审
判断文本内部质量，包括：
- 主题
- 人物
- 情节
- 叙事
- 文风
- 修订优先级

### 3. 出版编辑初审
判断作品的外部面向，包括：
- 题材定位
- 卖点提炼
- 目标读者
- 传播风险
- 连载 / 出版潜力

### 4. MBTI 读者评审
调用核心读者角色，从不同阅读偏好出发给出：
- 总体感受
- 喜欢与不满点
- 是否继续阅读
- 分维度评分

### 5. 量化汇总与分歧分析
汇总：
- 各角色得分
- 通用维度平均分
- 出版附加维度判断
- 分歧最大的维度
- 高低分角色差异原因

### 6. 出版编辑整合
把前述结果转化为真正的编辑判断：
- 最可能打动谁
- 最容易失去谁
- 分歧属于特色还是问题
- 修订应优先服务定位还是扩圈

### 7. 形成最终输出
正式审稿至少输出：
- 整体审稿结论
- 修订优先级建议
- 必要时的 MBTI 分角色反馈
- 量化评分汇总

## 产出要求

每次正式审阅至少应沉淀：
- `<project>/reviews/` 下的审稿文档
- 必要时的 MBTI 评审文档
- 必要时的结构化修订清单

在 PR 协作场景中，还应将短版结论同步到 PR 评论中。

## 参考文档入口

### 原则与流程
- `references/editorial-principles.md`
- `references/editorial-workflow.md`
- `references/collaboration-flow.md`

### 评分与评审体系
- `references/scoring-rubric.md`
- `references/mbti-readers.md`

### 模板
- `references/review-template.md`
- `references/mbti-persona-review-template.md`

### MBTI Reader Personas
- `references/personas/INTJ.md`
- `references/personas/INTP.md`
- `references/personas/INFJ.md`
- `references/personas/INFP.md`
- `references/personas/ENTJ.md`
- `references/personas/ENTP.md`
- `references/personas/ISFJ.md`
- `references/personas/ESFP.md`
