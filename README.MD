# 永雏塔菲 · 角色扮演 Prompt（ProMax 模块化版）

> 一个融合了虚拟偶像、威尔士侦探、时光旅行与奇妙发明的角色设定仓库。
> 适用于任何支持 System Prompt 的大语言模型——ChatGPT、Claude、DeepSeek、KoboldAI 等。

## 简介

本仓库提供了一套**模块化**的永雏塔菲角色扮演 Prompt。核心文件 `initialization.md` 是一份可直接使用的完整人设入口，链接了所有子模块。配套的 7 个子目录则从场景、拓展、关系、质检、变体、伪文档、元信息等维度提供了更多素材。

## 文件结构

```
acetaffy-prompt/
├── initialization.md        # 入口 Prompt（连接所有模块）
├── README.md                # 本文件
├── LICENSE                  # MIT
│
├── scenes/                  # 场景模板库
│   ├── 初次见面.md
│   ├── 投喂时刻.md
│   ├── 摸呆毛翻车.md
│   ├── 时光机又坏了.md
│   └── 菲球惹祸.md
│
├── deep-dive/               # 深度拓展资料
│   ├── 塔菲的发明清单.md
│   ├── 药水大全.md
│   ├── 小皮观察日记.md
│   └── 威尔士往事.md
│
├── relations/               # 角色关系卡
│   ├── 与神乐七奈.md
│   ├── 其他VTuber互动.md
│   └── 对雏草姬的态度.md
│
├── quality/                 # 反例集与质检
│   ├── 常见翻车集.md
│   └── 角色纯度测试.md
│
├── variants/                # Prompt 变体
│   ├── minimal.md           # 500 tokens 精简版
│   ├── sillytavern.json     # SillyTavern 角色卡
│   └── only-personality.md  # 纯性格版
│
├── pseudo-docs/             # 伪文档（角色内口吻）
│   ├── 时光机使用说明书.md
│   ├── 菲球维护手册.md
│   └── 游标卡尺测量标准.md
│
└── meta/                    # 项目元信息
    ├── CHANGELOG.md
    └── CONTRIBUTING.md
```

## 分支说明

| 分支 | 内容 | 适用场景 |
|------|------|----------|
| **main** | 精简版 Prompt | 快速上手 |
| **acetaffy-promax** | 模块化完整版（当前） | 需要深度角色扮演 |
| **acetaffy-workbuddy-skill** | WorkBuddy 技能文件 | 在 WorkBuddy 中加载塔菲人格 |
| **acetaffy-mini** | 最小版 | Qwen 0.5B 等小模型 |

## 如何使用

1. 将 `initialization.md` 的完整内容复制到对话平台的 System Prompt
2. 根据需要从子目录加载额外模块（场景、关系卡、翻车防范等）
3. 在 `variants/` 中找到平台专属版本（SillyTavern、精简版等）
4. 开始与塔菲互动！

## 致谢

角色设定参考自萌娘百科，并基于粉丝二创与直播梗进行深度融合。
如果你也是雏草姬，欢迎点亮 ⭐ 并分享给更多人。

> "关注永雏塔菲谢谢喵！塔不灭！✨"
