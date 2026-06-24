# Awesome GitHub Profile README

> GitHub Profile README 最佳实践、工具集、以及 AI 领域标杆人物参考。
> 持续更新。

---

## 目录

- [核心原则](#核心原则)
- [工具 & Widget](#工具--widget)
- [内容结构建议](#内容结构建议)
- [AI 领域标杆人物](#ai-领域标杆人物)
- [常见陷阱](#常见陷阱)

---

## 核心原则

| 原则 | 说明 |
|:-----|:------|
| **3 秒定生死** | 访客扫读前 5 行决定是否继续往下看。头部必须有身份定位 + 价值主张 |
| **当下 > 过去** | 当前在做什么放前面，历史成就放后面或折叠 |
| **数据胜过描述** | "84 CLI, 719 calls" 比 "热爱自动化" 有说服力 100 倍 |
| **不编造、不夸大** | GitHub 是公开的，面试官会点进你的仓库看代码 |
| **移动端优先** | 大量表格 / 长代码块在手机上体验差；优先用列表和 inline badge |
| **信息有据可查** | 每条能力标签都要能找到对应的项目/仓库支撑 |

---

## 工具 & Widget

### 统计卡片

| 工具 | 用途 | 示例 |
|:-----|:----|:-----|
| [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) | 通用 stats + 语言分布 | `![Stats](https://github-readme-stats.vercel.app/api?username=imjaden&show_icons=true&theme=dark)` |
| [github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) | 贡献连续天数 | `![Streak](https://streak-stats.demolab.com?user=imjaden&theme=dark)` |
| [github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) | 成就徽章（星级/贡献/PR 等） | `![Trophy](https://github-profile-trophy.vercel.app/?username=imjaden&theme=radical)` |
| [github-readme-activity-graph](https://github.com/Ashutosh00710/github-readme-activity-graph) | 贡献活动图 | `![Graph](https://github-readme-activity-graph.vercel.app/graph?username=imjaden&theme=tokyo-night)` |

**使用建议：**

- **活跃账号**（日 commit > 1）→ Streak + Activity Graph 效果好
- **中等活跃**（周 commit > 3）→ Stats Card 足够
- **低活跃** → 不建议加 Stats，会暴露空白
- 30+ 主题可选：`dark`, `radical`, `tokyonight`, `dracula`, `gruvbox` 等

### Badge 生成

| 工具 | 用途 |
|:-----|:------|
| [shields.io](https://shields.io) | 标准 badge：技能标签、社交链接、CI 状态 |
| [Simple Icons](https://simpleicons.org) | 品牌 SVG 图标库，shields.io 的 logo 来源 |

**Badge 数量控制：**

| 场景 | 建议数量 |
|:-----|:--------:|
| 核心技能 | 6-8 个 |
| 社交链接 | 4-5 个（inline 排一行） |
| 语言/工具 | 8-12 个（可折叠） |

> 超过 15 个 badge 在手机上会折得乱七八糟。

### 视觉效果

| 工具 | 用途 | 注意 |
|:-----|:-----|:-----|
| [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg) | 打字动画标语 | 最多 1 个动画元素，多了喧宾夺主 |
| [Capsule Render](https://github.com/kyechan99/capsule-render) | 渐变色页眉图 | 简单大方，适合替代 Banner SVG |
| 自定义 SVG Banner | 品牌色+标语 | 工作量稍大，但独特性最高 |

### 动态内容

| 工具 | 用途 |
|:-----|:------|
| [waka-readme](https://github.com/athul/waka-readme) | WakaTime 每周编码统计 |
| [github-activity-readme](https://github.com/jamesgeorge007/github-activity-readme) | 最近 GitHub 活动自动更新 |
| [todoist-readme](https://github.com/abhisheknaiidu/todoist-readme) | Todoist 任务统计 |
| [Visitor Badge](https://visitor-badge.glitch.me) | 访客计数 |

### 推荐组合

```
轻度（简洁风）：
  shields.io badge × 6 + Stats Card

中度（标准配置）：
  SVG Banner + Badge × 6 + Stats Card + Streak + Project List

重度（满分卷）：
  SVG Banner + Typing SVG + Badge × 8 + Stats + Streak + Trophy
  + Activity Graph + Projects + Folded Certs + Dynamic Content
```

---

## 内容结构建议

### 推荐区块顺序

```
1. Header（H1 + 一句话定位）
2. SVG Banner / 视觉元素
3. Badge（核心技能 6-8 个）
4. What I Do（当下能力放前，历史成就放后）
5. Projects & Tools
   ├ 当前项目（正在 build 的）
   ├ 工具集（CLI / 自建脚本等）
   └ 历史成就（标注 "Past"，可折叠）
6. What I'm Doing Now（具体项目名称）
7. Connect（inline badge，1-2 行）
8. 可选尾部：Philosophy / Random Facts（折叠）
```

### 判断标准

| 检查项 | 自查 |
|:-------|:-----|
| 访客 3 秒内知道你是谁、做什么？ | ✅ / ❌ |
| 每一条能力有项目或数据支撑？ | ✅ / ❌ |
| 没有重复内容？ | ✅ / ❌ |
| 没有敏感信息？ | ✅ / ❌ |
| 所有链接 200 通？ | ✅ / ❌ |
| 移动端阅读体验 OK？ | ✅ / ❌ |

---

## AI 领域标杆人物

以下是在 AI 领域有广泛影响力的 GitHub 账号，适合作为 Profile 设计和技术方向的参考：

| 人物 | GitHub | 定位 | Profile 特点 |
|:-----|:-------|:-----|:-------------|
| **Andrej Karpathy** | [@karpathy](https://github.com/karpathy) | 前 Tesla AI 总监、OpenAI 创始成员 | 极简风，靠 repo 质量说话，无需花哨装饰 |

### 从他们身上学什么

| 人物 | 可借鉴的点 |
|:-----|:----------|
| karpathy | 项目质量 > Profile 装饰。做一个足够好的开源项目，Profile 自然有说服力 |

---

## 常见陷阱

### 🔴 致命

- **编造成就** — 面试官或同行会验证，一旦发现信任归零
- **泄露敏感信息** — API Key、Token、客户数据、内部系统地址
- **断链** — 链接 404 或证书过期，让人觉得不维护了

### 🟡 减分

- **信息过时** — "当前在做的" 还是半年前的内容
- **过度包装** — 20+ badge、5 个动画、3 个 stats card，页面加载慢、视觉拥堵
- **中英混杂无规则** — 技术名词用英文 OK，但描述语种不统一显杂乱
- **重复内容** — "What I Do" 和 "What I'm Doing Now" 说同一件事

### 🟢 可优化

- **表格滥用** — 表格在移动端折行严重，优先用列表
- **长段无分段** — 超过 3 行的段落很少有人读完
- **忽略暗色模式** — GitHub 默认暗色主题，浅色 SVG 在暗色下刺眼

---

## 参考资源

| 资源 | 链接 |
|:-----|:-----|
| Awesome GitHub Profile README | [abhisheknaiidu/awesome-github-profile-readme](https://github.com/abhisheknaiidu/awesome-github-profile-readme) |
| Awesome README Tools | [dhyeythumar/awesome-readme-tools](https://github.com/dhyeythumar/awesome-readme-tools) |
| Shields.io Badge 生成 | [shields.io](https://shields.io) |
| GitHub Stats Card | [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) |
| GitHub Profile Trophy | [ryo-ma/github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) |

---

## 📋 元信息

| 项目 | 内容 |
|:---|:---|
| 助手名称 | IRIS (byHermes) |
| 创建时间 | 2026-06-16 19:15:00 |
| 信息来源 | DEV Community Top Tools 2026, awesome-github-profile-readme, GitHub 搜索 |
