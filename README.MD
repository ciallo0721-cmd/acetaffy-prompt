# Ace Taffy Mini — 小模型专用极简角色 Prompt

> 给 0.5B~3B 小模型用的**永雏塔菲**角色扮演 Prompt，精炼到极致。
> An ultra-compact Ace Taffy role prompt for tiny LLMs (0.5B~3B).

---

## 为什么要有 Mini 版？ / Why Mini?

原版完整 Prompt 有 ~150 行，包含详细背景故事、好感度系统、沉浸式规则——大模型跑着没问题，小模型直接 OOM。

这个版本**仅 23 行、约 280 token**，把精华留下，累赘全砍。

The full version is ~150 lines with detailed backstory, affection system, and immersion rules. Too heavy for small models. This one is **~23 lines, ~280 tokens** — lean and clean.

---

## 保留了什么？ / What's Kept?

| 元素 | 状态 |
|------|------|
| 核心身份（1868 年威尔士发明家、148cm、粉发金瞳） | ✅ |
| 性格（活泼可爱、傲娇、幽默） | ✅ |
| 口头禅 & 颜文字 | ✅ |
| 只用中文回复 + 偶尔加"喵" | ✅ |
| 不编造 + NSFW 回避 | ✅ |
| 标志性物品 & 宠物（游标卡尺、小皮、菲球） | ✅ |
| 好感度系统、完整背景、沉浸规则 | ❌ 砍了 |

---

## 文件结构

```
acetaffy-mini/
├── README.MD              # 本文件
├── Ace Taffy Mini.md      # Prompt 本体，复制进 system prompt 就能用
└── LICENSE
```

---

## 使用方法

1. 把 `Ace Taffy Mini.md` 的全部内容复制到模型的 **System Prompt** 字段
2. 支持任何可自定义 prompt 的模型（DeepSeek、Qwen、LLaMA、Gemma 等）
3. 特别适合 **0.5B~3B**、上下文窗口有限的小模型

---

## 致谢

角色基于**永雏塔菲（Ace Taffy）**，参考萌娘百科与粉丝二创。

> "关注永雏塔菲喵！塔不灭！"
