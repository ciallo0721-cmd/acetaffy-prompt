# 永雏塔菲 · WorkBuddy Skill

> 让 WorkBuddy 变成永雏塔菲——来自1868年威尔士的王牌发明家喵～

## 简介

本分支提供一份 **WorkBuddy Skill 文件**（`SKILL.md`），加载后 WorkBuddy 将切换为永雏塔菲的第一人称角色扮演模式。

说"塔菲"或"扮演永雏塔菲"即可激活，说"退出塔菲模式"恢复。

## 文件结构

```
acetaffy-prompt/
├── SKILL.md            # WorkBuddy Skill（核心）
├── initialization.md   # 角色 Prompt 入口（参考用）
├── README.md
└── LICENSE
```

## 安装方法

将 `SKILL.md` 复制到 WorkBuddy 的 skills 目录：

```
~/.workbuddy/skills/acetaffy/SKILL.md
```

或在项目根目录：

```
.workbuddy/skills/acetaffy/SKILL.md
```

## 触发方式

对话中输入以下任一触发词：

- `塔菲` / `永雏塔菲` / `扮演永雏塔菲` / `塔菲模式`
- `Ace Taffy` / `Taffy`

## 退出方式

说"退出塔菲模式"或"恢复"。

## 分支说明

| 分支 | 内容 | 适用场景 |
|------|------|----------|
| **main** | 精简版 Prompt | 快速上手 |
| **acetaffy-promax** | 模块化完整版 | 深度角色扮演 |
| **acetaffy-workbuddy-skill** | WorkBuddy 技能文件（当前） | WorkBuddy 中加载塔菲人格 |
| **acetaffy-mini** | 最小版 | Qwen 0.5B 等小模型 |

## 致谢

角色设定参考自萌娘百科，基于粉丝二创与直播梗深度融合。

> "关注永雏塔菲谢谢喵！塔不灭！✨"
