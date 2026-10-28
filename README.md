# AI自动制作3D说明书

让任何 AI Agent 学会「用大模型自动驱动 SolidWorks / CAD 画图与建模」的 Skill 仓库。

本仓库打包了《AI 与机械设计：用大模型驱动 SolidWorks / CAD 使用指南》的完整内容，提供三条可直接照做的玩法：**Kimi 自动制作工程图（CAD）**、**Kimi 驱动 SolidWorks 画 3D**、**GPT-6 自动调用 SolidWorks 画 3D**。

## 完整文档

[《AI 与机械设计：用大模型驱动 SolidWorks / CAD 使用指南》（飞书文档，互联网可读）](https://my.feishu.cn/docx/NrpKd27tHo53X5xcqQ9coU4cnPc)

任何人都可以通过上面的链接直接打开阅读；也可以把本 Skill 装进自己的 AI 客户端，让 Agent 照着本地打包的指南一步步引导你完成 AI 自动出图。

## 快速开始

1. 将 `skills/ai-auto-3d-guide` 目录复制到你所用 AI 客户端的 Skill 目录中（例如豆包工作、Claude 等支持 Agent Skills 的平台，按各自平台的 skill 安装方式放置）。
2. 之后直接对 Agent 说，例如：
   - 「帮我在 SolidWorks 里用 AI 画一个法兰盘 3D 模型」
   - 「用 Kimi 自动制作一张 45 钢的 2D 工程图」
   - 「我想学 AI 驱动 CAD 画图，该装什么软件？」
3. Agent 会自动读取 Skill 内的指南，按步骤引导你完成「安装软件 → 设置权限与模型 → 输入提示词 → 自动出图」；想看完整图文文档时，它会直接给你飞书文档链接。

## 目录结构

```
AI自动制作3D说明书/
├── README.md                         # 本说明
├── LICENSE                           # MIT 许可证
└── skills/
    └── ai-auto-3d-guide/             # Skill 本体
        ├── SKILL.md                  # Skill 触发描述与使用指引
        └── references/
            ├── guide-content.md      # 指南全文（Agent 读取后照做）
            └── doc-link.md           # 文档与资源链接汇总
```

## 内容来源

指南内容整理自「得到大脑 · 短视频制作」知识库中的 4 篇笔记（原始链接见 `skills/ai-auto-3d-guide/references/doc-link.md`），并已整理为不含版本年代要求的通用教程。

## License

[MIT](LICENSE)
