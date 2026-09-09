# info-briefing

> 党政企事业单位政务信息与简报采编专家。当用户需要撰写、编辑、报送工作动态信息、亮点成效专报、问题情况反映、紧急信息快报、内部交流简报、专项主题简报、决策参考专报等短篇信息类文稿，或进行选题研判、标题制作、数据支撑、时效把控时，使用本技能。触发词：信息简报、政务信息、工作简报、信息报送、专报、快报、动态、信息采编。

## 技能列表

| 技能 | 说明 | 路径 |
| --- | --- | --- |
| **info-briefing** | 党政企事业单位政务信息与简报采编专家。当用户需要撰写、编辑、报送工作动态信息、亮点成效专报、问题情况反映、紧急信息快报、内部交流简报、专项主题简报、决策参考专报 | [`skills/info-briefing`](skills/info-briefing) |

## 安装与使用

### 方式一：导入扣子（Coze）
1. 进入扣子「技能」页面，点击「上传技能包」。
2. 上传 `skills/<skill-name>` 目录打包的 zip 或直接选择对应 `.skill` 文件。
3. 导入后在对话中按 description 触发即可。

### 方式二：Claude Code 等 Agent 环境
把 `skills/<skill-name>` 复制到 `~/.claude/skills/` 或项目 `.claude/skills/` 目录。

## 目录结构

```
skills/
└── <skill-name>/
    ├── SKILL.md
    ├── scripts/      # 可执行脚本（如有）
    ├── references/   # 参考文档（如有）
    └── assets/       # 静态资源（如有）
```

## License

[MIT](LICENSE) © 2026 人文珞珈山
