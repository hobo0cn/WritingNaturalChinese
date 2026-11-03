# writingNaturalChinese

让 AI 写出真正自然的中文的 Agent Skill。

## 项目结构

```
writingNaturalChinese/
├── SKILL.md              # 技能主定义（起草阶段的句式与语气规则）
├── prompts/
│   ├── ultimate.md       # 终极 Prompt 负向限制模板
│   └── advanced.md       # 高阶句式连贯性严控指令
├── examples/
│   └── rewrite-demo.md   # 改写示例
└── README.md
```

## 使用方式

- 起草阶段：按 `SKILL.md` 的规则写，先定文体、句子基线、受众。
- 提示词阶段：在 Prompt 中加入 `prompts/ultimate.md` 的负向限制。
- 后期润色：按 `SKILL.md` 的「交付前扫描」和改写技巧处理。

## 核心原则

- 不设问，直接推因果。
- 长短错落，不连击（连续短句 ≤ 2）。
- 语气选定后贯彻全文。
- 禁止市面自媒体高频短语（说白了、其实不然、不得不说等）。
- 用复杂织网取代口语短语堆砌。
