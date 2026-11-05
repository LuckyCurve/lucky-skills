# lucky-skills

我自己的开发技能集。**只有一个入口**：`/lucky`（`skills/lucky/SKILL.md`）。

- 偏好：人给愿景、agent 定实现；只在产品取舍上问人；验证到底；不写 spec。
- 机制：`GLOSSARY.md` / `DECISIONS.md` 统一话术，`LESSONS.md` / `docs/code-standards.md` 给 agent 记账，第一次要写时才在目标项目里建。
- 入口支持自动匹配，也可显式调用。

## 安装

全局（装到 `~/.agents/skills/lucky`，并 symlink 给各 agent）：

```bash
npx -y skills@latest add LuckyCurve/lucky-skills -g
```

只装到当前项目（`./.agents/skills/lucky`）：去掉 `-g`。

安装是 copy 而非引用，仓库更新后跑 `npx skills@latest update` 生效。
