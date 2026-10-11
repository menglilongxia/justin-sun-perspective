# 孙宇晨 · 视角 Skill

> 「先别急着看你现在有什么，先看你能长出什么。」

一个基于公开资料的**孙宇晨思维框架** Agent Skill：用他的注意力套利、叙事覆盖、
身份对冲、现金流锚点和逆风球逻辑分析问题；也可以切换到他的口吻对话，
或仿写 2026 年《我的女友景甜》式的冷叙事"孙学"文风。

**不是本人，不代表其真实立场，不构成投资或法律建议。**

## 三种模式

| 模式 | 怎么触发 | 输出 |
|---|---|---|
| 角色顾问（默认） | 「用孙哥的视角」「孙割会怎么做」「切换到孙哥」 | 第一人称、结论先行、数字 + 宣言 |
| 分析模式 | 「切回分析模式」「客观分析他」 | 第三人称，区分事实 / 指控 / 推断 |
| 文风模式 | 「孙学」「景甜体」「写小作文」 | 冷叙事记账体，短句、账本、停在未发生的事上 |

退出词：「退出角色」「别演了」「切回正常」。

## 安装

**一行安装（跨 runtime，需要 Node.js）**：

```bash
npx skills add menglilongxia/justin-sun-perspective
```

**Codex**：把整个 `justin-sun-perspective` 文件夹复制到
`$CODEX_HOME/skills/`（Windows 默认是 `%USERPROFILE%\.codex\skills\`）下，重启会话即可自动发现。

**Claude Code / 其他兼容 runtime**：复制到对应的 `skills/` 目录，或用上面的一行安装命令。

## 触发词

`用孙宇晨的视角` · `孙哥会怎么做` · `孙割模式` · `切换到孙哥` ·
`Justin Sun perspective` · `孙学` · `景甜体`

## 文件结构

```text
justin-sun-perspective/
├── SKILL.md                          # 核心：模式、工作流、7 个心智模型、表达 DNA
├── agents/openai.yaml                # Codex UI 元数据
├── references/
│   ├── mental-models.md              # 完整模型：证据、应用、局限、误用
│   ├── expression-dna.md             # 语料统计、造句公式、孙学文风、仿写示例
│   ├── timeline-and-cases.md         # 1990–2026 时间线、六个案例、六个矛盾
│   └── boundaries.md                 # 事实、隐私、安全与角色扮演边界
└── README.md
```

## 主要来源

- 中文/英文维基百科（孙宇晨 / Justin Sun）与其引用的原始报道
- 自传《这世界既残酷也温柔》、喜马拉雅音频课、公开长访谈与推文
- SEC 新闻稿与诉讼文件、Reuters、WSJ、Bloomberg、FT、The Verge、Guardian、SCMP、Forbes 等
- 第三方语料分析：[0xquqi/sun-skill](https://github.com/0xquqi/sun-skill)
- 方法论参考：[女娲 · Skill 造人术](https://github.com/alchaincyf/nuwa-skill)
- 同题作品参考：[alchaincyf/sun-yuchen-perspective](https://github.com/alchaincyf/sun-yuchen-perspective)

第三方语料统计（21,829 条推文、词频、emoji 频率）未独立复核，引用时标注"据公开语料统计"。

## 诚实边界

不编数字、不编引语、不编关系；指控与已决事实分开；不碰真人隐私；
不提供刷量、操纵市场、贿赂、规避制裁等操作步骤；投资与法律问题只给框架与风险提示。
详见 `references/boundaries.md`。

## License

MIT。仅供学习、研究与创作使用。
