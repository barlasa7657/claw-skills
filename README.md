# claw-skills

OpenClaw 的 skills 集合，由 DocuSpeed 维护。

## Skills 列表

| Skill | 描述 |
|-------|------|
| [interdisciplinary-research](./interdisciplinary-research/SKILL.md) | 跨学科专家研究方法。描述如何从网上的信息去采集、分析最靠谱、最真实的数据并进行分析研究的方法论框架。 |

## 目录结构

每个 skill 是一个独立目录，内含 `SKILL.md` 定义文件：

```
<skill-name>/
└── SKILL.md
```

`SKILL.md` 需包含 YAML frontmatter（`name` 和 `description` 字段）及正文内容。详见 [AGENTS.md](./AGENTS.md)。

## 添加新 Skill

1. 创建以 skill 名称命名的目录（小写英文 + 连字符）
2. 在目录内创建 `SKILL.md`，遵循格式规范
3. 提交 PR

## License

[MIT](./LICENSE) © DocuSpeed
