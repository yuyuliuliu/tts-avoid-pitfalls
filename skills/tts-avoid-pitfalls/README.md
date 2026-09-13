# 中文 AI 配音避坑技能包（试吃层） | TTS Avoid-Pitfalls Skill

> 中文在前，English below. Agent Skills 标准格式（`SKILL.md`），支持 Agent Skills 规范的 Agent 可直接加载。

## 这是什么（中文）

**ChatTTS / CosyVoice 配音避坑**：基于 2026-09 真实流水线实测（非教程转述），免费开放判决结论：

- **24 个真标记 / 11 个假标记**完整判决清单——哪些安全生效，哪些会被逐字念进你的视频
- 一条铁律：`[xxx]` 里只有英文小写下划线命名的才是真 token
- 三个核心判决：阿拉伯数字读不出 bug、越快越糊的架构级天花板、迁移 CosyVoice 3 决策数据（字错率 22%→12%）
- 语速两条路线实测对比（字错率差一倍）

**适合谁**：用 ChatTTS/CosyVoice 做短视频配音的创作者；被"情绪标注教程"坑过的人；犹豫是否迁移 CosyVoice 3 的人。

## 完整判决书（付费）

本仓库是**试吃层**。完整版包含仓库里**没有**的内容：8 个 Windows 部署坑逐坑解法、四大丝滑工具用法、ASR 质检门禁方法论、可运行脚本包。

👉 [UUMit 知识商店 ·《中文 AI 配音避坑包》](https://www.uumit.com)

## 数据边界

2026-09-12 实测：Fun-CosyVoice3-0.5B + ChatTTS 当期版，Windows + RTX 4060 Laptop + Python 3.10。标记听感只验证了时长与 ASR 字错率，不夸大。

## License

CC BY-NC-SA 4.0（可转载改编需署名、禁商用转售）

---

## What is this (English)

A free "tasting layer" skill for Chinese TTS pitfalls, based on real pipeline testing (2026-09):

- Complete verdict list of **24 real / 11 fake ChatTTS tokens** — which ones work, which get read aloud into your audio
- The killer bug: Arabic numerals are 100% unreadable (with the fix direction)
- Migration decision data: CosyVoice 3 CER 0.81 vs ChatTTS unlisted; CC BY-NC license warning for commercial use
- Speed-control A/B results: native instructions beat parameter stretching (CER halved)

**For**: creators using ChatTTS/CosyVoice for short-video dubbing; anyone bitten by fake "emotion tag" tutorials; anyone deciding whether to migrate to CosyVoice 3.

## Full verdict (paid)

The complete playbook — per-pitfall fixes for 8 Windows deployment traps, the four smoothness tools, ASR-gate QC methodology, runnable scripts — is sold on our UUMit store: https://www.uumit.com

## License

CC BY-NC-SA 4.0
