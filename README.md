# Drama Skills · short-drama-video-prompts

> **[short-drama-video-prompts](https://github.com/simlpandordinary/short-drama-video-prompts)** —— 飞书《WorkBuddy 视频系列 · 全技能与提示词总目录》里推荐的开源技能，已拆分为独立仓库分发（一个技能一个仓库）。

| 项 | 内容 |
| - | - |
| 上游仓库 | <https://github.com/zenstory-ai/drama-skills> |
| 上游路径 | `skills/short-drama-video-prompts` |
| 上游协议 | MIT |
| 上游 Star | 3.7k+ |
| 拆分方式 | 仅抽取该技能自身文件，独立可用 |

## 技能说明

把短剧分镜和冻结关键帧写成可直接复制的视频提示词 Markdown，也可按用户要求写时间线配乐/主题曲意图。用户提到文生/图生视频动作、人物表演、运镜、口型、环境运动、镜头时长、起止状态、把分镜转成视频提示词或写配乐提示词时使用；不生成媒体、不创作歌词、不改分镜边界。

## 目录结构

```
['SKILL.md', 'agents/openai.yaml', 'references/camera-audio-continuity.md', 'references/delivery-profile.md', 'references/generability.md', 'references/minimax-h3.md', 'references/motion-recipe.md', 'references/performance-action-timing.md', 'references/production-prompt-grammar.md', 'references/review-and-fixtures.md', 'references/seedance-2.0.md', 'references/seedance-2.5.md', 'references/stage-contract.md', 'references/target-model-profile.md', 'references/wan-3.0.md', 'LICENSE', 'README.upstream.md']
```

- `SKILL.md` 是技能入口（触发条件 / 工作流 / 约束），安装时必须位于技能根目录。
- `references/`、`scripts/`、`assets/` 为该技能自带的参考文档、脚本与素材。
- `README.upstream.md` 为上游仓库原始说明，保留出处与版权信息。
- `LICENSE` 为上游许可证原文。

## 安装

WorkBuddy 技能目录为 `~/.workbuddy/skills/short-drama-video-prompts/`：

```bash
git clone https://github.com/simlpandordinary/short-drama-video-prompts.git ~/.workbuddy/skills/short-drama-video-prompts
```

也可以直接对 AI 说：「把 <https://github.com/simlpandordinary/short-drama-video-prompts> 装成 Skill」。

安装后用自然语言触发，例如「Drama Skills · short-drama-video-prompts」「用 short-drama-video-prompts 帮我处理这个任务」。

本仓库仅含 Drama Skills 技能包中的 `short-drama` 家族技能之一，其余 10 个技能各自独立成仓。

## 版权

原始作者与版权归上游仓库 `zenstory-ai/drama-skills` 所有。本仓库仅做独立分发与结构整理，未修改技能内容；商用请遵循上游许可证。
