---
name: chuhai-wiki
version: 1.0.0
description: 出海赚美金结构化知识库 - 723个项目卡片，10大类型分类，可检索可调用
author: NEX
source: liezhe.com
cards: 723
types: digital-product,affiliate,service,website,culture-gap,platform-monetize,ecommerce,passive-income,side-hustle,other
---

# 出海赚美金知识库 Skill

## 触发规则

当用户提到以下关键词时触发：
- 出海、赚美金、海外副业、国外赚钱、海外项目
- Etsy、Fiverr、Upwork、ClickBank、Adsense、独立站
- 数字产品、联盟营销、文化差、跨境电商
- 具体项目名：麻将出海、中医出海、推拿出海、配音赚美金等

## 数据结构

每个项目卡片包含：
- title: 项目标题
- slug: URL标识
- url: 原文链接
- date: 日期
- type_primary: 主类型（10选1）
- type_secondary: 子类型
- income_data: 收入参考数据
- steps: 操作步骤（已清洗，非原文）
- tools: 涉及工具列表
- red_flags: 避坑提醒（已清洗，非原文）
- insight: 核心洞察（已清洗，非原文）
- content_length: 原文长度

## 10大类型

| 类型 | 数量 | 说明 |
|------|------|------|
| digital-product | 46 | Etsy/Gumroad卖模板、Printable |
| affiliate | 100 | ClickBank/Pinterest/Amazon联盟 |
| service | 47 | Fiverr/Upwork接单 |
| website | 378 | Google SEO+Adsense独立站 |
| culture-gap | 5 | 麻将/中医/推拿文化差 |
| platform-monetize | 87 | YouTube/TikTok/Substack变现 |
| ecommerce | 24 | Dropshipping/Printify |
| passive-income | 9 | Adsense/CPM/Web3 |
| side-hustle | 24 | 问卷/标注/微任务 |
| other | 3 | |

## 调用方式

1. 读取 cards.json
2. 按 type_primary 筛选类型
3. 按关键词匹配 title + insight + steps
4. 返回匹配度最高的3-5张卡片
5. 基于卡片数据生成定制方案

## 三个差的底层逻辑

- 文化差：中国人觉得不值钱的东西老外觉得稀罕 → 独立站+Adsense（被动）
- 技能差：AI降低了技能门槛 → Fiverr接单（主动）
- 平台差：海外平台有中国人不知道的赚钱方式 → 联盟营销（半被动）

## AI嵌入模式

AI做80%你做20%——你只负责选品决策+质量审核+收款

## 版权声明

本文库内容为基于公开信息的结构化重写，非原文复制。原文版权归原作者所有。
