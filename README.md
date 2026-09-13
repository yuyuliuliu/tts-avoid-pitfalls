# tts-avoid-pitfalls

**中文 AI 配音避坑技能包（试吃层）**——ChatTTS 词表 24 真/11 假标记判决清单、数字读不出 bug 判定、迁移 CosyVoice 3 决策数据。基于 2026-09 真实流水线实测，非教程转述。

## 是什么

一个标准的 [Agent Skill](https://agentskills.io)（根目录 `SKILL.md`，可直接被支持 Agent Skills 规范的 Agent 加载）：

- **✅ 24 个真标记 / ❌ 11 个假标记**完整判决清单——哪些标记安全生效，哪些会被逐字念进你的视频
- 一条铁律判定法：`[xxx]` 里只有英文小写下划线命名的是真 token
- 三个核心判决：数字读不出 bug、越快越糊的架构级天花板、迁移 CosyVoice 3 的决策数据
- 语速两条路线实测对比（字错率差一倍）

## 适合谁

- 用 ChatTTS / CosyVoice 做短视频配音、有声内容的创作者
- 被网传"情绪标注教程"坑过的人
- 在 Windows 上部署 CosyVoice 失败或犹豫是否迁移的人

## 试吃内容（本仓库全部）

见 [`SKILL.md`](SKILL.md)——判决清单与结论层完整开放，免费。

## 完整版（付费）

完整判决书包含本仓库**没有**的内容：8 个 Windows 部署坑的逐坑解法、四大丝滑工具用法、ASR 质检门禁方法论、可运行脚本包。

👉 [UUMit 知识商店 ·《中文 AI 配音避坑包》](https://www.uumit.com)

## License

[CC BY-NC-SA 4.0](LICENSE) —— 可自由转载与改编（需署名、同方式共享），**禁止商用转售**。
