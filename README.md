# before-build

一个轻量 Agent Skill：先把需求和验收说清楚，再在需要时查现成方案、做小样验证，最后决定复用、改造还是自研。

整合 brief 的需求回执和 prior-art 的事前调研，消除重复步骤。不替换原有两个技能，不依赖它们，也不要求每个小任务走完整流程。没有脚本、服务或外部依赖。

## 安装

```sh
git clone https://github.com/RUNAWAYRUN/before-build.git ~/.agents/skills/before-build
```

按你的 Agent 使用的技能目录调整路径，刷新技能列表。入口：[SKILL.md](SKILL.md)。

例：「用 before-build 帮我确定这个聊天备份工具有没有必要自研，先比较现成方案，验证关键能力，再继续实现。」

MIT License.
