<div align="center">

# 大模型娘表情包

[English](README.md) · **简体中文**

[![授权: CC BY-NC-SA 4.0](https://img.shields.io/badge/%E6%8E%88%E6%9D%83-CC%20BY--NC--SA%204.0-lightgrey.svg)](LICENSE.md)
![角色](https://img.shields.io/badge/%E8%A7%92%E8%89%B2-12-ff69b4)
![表情](https://img.shields.io/badge/%E8%A1%A8%E6%83%85-312%20%C3%97%202-blue)
![格式](https://img.shields.io/badge/%E6%A0%BC%E5%BC%8F-PNG%20%C2%B7%20%E9%80%8F%E6%98%8E%20%2F%20%E7%99%BD%E5%BA%95-success)
![尺寸](https://img.shields.io/badge/%E5%B0%BA%E5%AF%B8-512%20%C2%B7%20240-informational)
[![GitHub stars](https://img.shields.io/github/stars/ChengAoShen/LLM-chan-stickers?style=social)](https://github.com/ChengAoShen/LLM-chan-stickers/stargazers)

社区里大家熟悉的**大模型娘** Q 版表情包，加上 [Textus](https://github.com/CatVinci-Studio/Textus) 编辑器的吉祥物 **Textus 娘**。

![Textus 娘](previews/textus-stickers.png)

</div>

每个角色 8 个表情、8 个动作（动作有朝左、朝右、正面三种朝向），透明背景，可以直接用在微信、QQ、Telegram、Discord、Slack。

## 角色

| | 对应 | 表情 | 动作 | 动作（正面） |
|---|---|---|---|---|
| Textus 娘 | Textus（CatVinci Studio） | ![](previews/textus-expressions.png) | ![](previews/textus-poses.png) | ![](previews/textus-poses-front.png) |
| DeepSeek 娘 | DeepSeek | ![](previews/deepseek-expressions.png) | ![](previews/deepseek-poses.png) | ![](previews/deepseek-poses-front.png) |
| GLM 娘 | 智谱 GLM | ![](previews/glm-expressions.png) | ![](previews/glm-poses.png) | ![](previews/glm-poses-front.png) |
| 豆包 Seed 娘 | 豆包 | ![](previews/doubao-expressions.png) | ![](previews/doubao-poses.png) | ![](previews/doubao-poses-front.png) |
| MiniMax 娘 | MiniMax | ![](previews/minimax-expressions.png) | ![](previews/minimax-poses.png) | ![](previews/minimax-poses-front.png) |
| Kimi 娘 | Kimi（月之暗面） | ![](previews/kimi-expressions.png) | ![](previews/kimi-poses.png) | ![](previews/kimi-poses-front.png) |
| Claude 娘 | Claude | ![](previews/claude-expressions.png) | ![](previews/claude-poses.png) | ![](previews/claude-poses-front.png) |
| GPT 娘 | GPT | ![](previews/gpt-expressions.png) | ![](previews/gpt-poses.png) | ![](previews/gpt-poses-front.png) |
| Gemini 娘 | Gemini | ![](previews/gemini-expressions.png) | ![](previews/gemini-poses.png) | ![](previews/gemini-poses-front.png) |
| 通义千问娘 | 通义千问 | ![](previews/qwen-expressions.png) | ![](previews/qwen-poses.png) | ![](previews/qwen-poses-front.png) |
| Grok 娘 | Grok | ![](previews/grok-expressions.png) | ![](previews/grok-poses.png) | ![](previews/grok-poses-front.png) |
| 文心一言娘 | 文心一言 | ![](previews/wenxin-expressions.png) | ![](previews/wenxin-poses.png) | ![](previews/wenxin-poses-front.png) |

## 文件

```
stickers/<角色>/expressions/512/01-smile.png ... 08-teary.png
stickers/<角色>/poses/512/01-writing.png ... 08-asleep.png
stickers/<角色>/poses-right/512/01-writing.png ... 08-asleep.png
stickers/<角色>/poses-front/512/01-writing.png ... 08-asleep.png
stickers/textus/stickers/512/01-heart.png ... 08-cheer.png
```

每张都有 512 × 512（Telegram、Discord）和 240 × 240（微信、QQ）两种尺寸，各有两套：透明背景（`512/`、`240/`）和白底（`512-white/`、`240-white/`），后者用在会把透明显示成黑色的地方。Claude 娘和文心一言娘在 `expressions-alt/` 里还有一套表情。动作有三种朝向：`poses/` 朝左，`poses-right/` 朝右，`poses-front/` 正面朝向观众。

- **表情：** 微笑 · 平静 · 惊讶 · 害羞 · 鼓腮 · 偷笑 · 认真 · 委屈
- **动作：** 写字 · 发呆 · 打盹 · 开心 · 惊讶 · 好奇 · 庆祝 · 睡着

## 出处

- **角色设定：** 大模型娘的角色形象与原始设定来自 **[ZipZipPipe](https://space.bilibili.com/4168597)** 等社区画师，角色版权归原作者所有。
- **参考设定图：** [lmy414/ai-chan-sheets](https://github.com/lmy414/ai-chan-sheets) 和同人整理站 [蓝色大肥鱼.com](https://xn--pssy23gqgbz2d718b.com/)。
- **本仓库的 Q 版图：** 由 [CatVinci Studio](https://catvinci.com) 参照上述设定，用 ChatGPT 的图像模型重绘。为做桌宠略有调整：GPT 娘的眼睛与其他角色统一，文心一言娘改为站姿。
- **Textus 娘** 是 CatVinci Studio 的原创角色、[Textus](https://textus.catvinci.com) 的吉祥物，完整设定见 [CatVinci-Studio/textus-chan](https://github.com/CatVinci-Studio/textus-chan)。

本项目为非商业同人作品，与 OpenAI、Anthropic、Google、DeepSeek、智谱、字节跳动、MiniMax、月之暗面、阿里巴巴、xAI、百度均无关联，也未获其认可。角色的权利人如认为不妥，请提 Issue，我们会立即修改或删除。

## 授权

[CC BY-NC-SA 4.0](LICENSE.md)：可免费用于非商业用途、可改编，需署名（链接本仓库和原作者）并以相同协议分享；禁止商用。
