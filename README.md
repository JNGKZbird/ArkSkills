# ArkSkills —— 《明日方舟》干员角色扮演 Skill 库

![badge](https://img.shields.io/badge/干员-13位-2196F3)
![badge](https://img.shields.io/badge/格式-Markdown-4CAF50)
![badge](https://img.shields.io/badge/素材-明日方舟Wiki官方文本-FF9800)
![badge](https://img.shields.io/badge/许可-素材归鹰角网络-9C27B0)

把罗德岛的干员们，带进你的 AI。

这里没有粗糙的"你是某某角色"一句话提示词——每一位干员都是一份**结构化角色包**：灵魂（她为什么而活）、边界（她绝不会说什么）、行为指南（七大行为模式 + 情境反应表）、说话方式（签名语、句式特征、官方原文示例），全部蒸馏自**明日方舟 Wiki 官方文本**。

> 听听她说话的样子（予愿安洁莉娜，官方原文）：

> 「早安，博士！我今天有外出任务，所以跟你提前说午安和晚安啦！」
> 「咖啡的味道和以前一样，我们之间也和以前一样……嗯，这样就好。」
> 「现在的我只想飞得快一点，再快一点，快到无论发生什么事，我都能及时赶到你的身边。」

## 两套规格

每位干员提供**长短两套**，按需选用：

| 文件 | 用途 |
|---|---|
| `bundle_compact.md` | **短版**：核心人格压缩包，适合小上下文 / 低成本场景 |
| `bundle_full.md` | **完整长版**：灵魂 / 边界 / 行为指南 / 说话方式全量合并，效果最完整 |

## 干员列表

| 目录 | 干员 | 备注 |
|---|---|---|
| `angelina/` | 予愿安洁莉娜 | 2026 夏活「直到大地变成一颗酸橙」，信使少女 |
| `angelina-base/` | 安洁莉娜（本体） | 信使少女时期的原型形态 |
| `amiya/` | 阿米娅 | 罗德岛公开领袖（术师主轴） |
| `kaltsit-sihengtuo/` | 凯尔希·思衡托 | 石棺重生后的凡人之躯 |
| `texas-base/` | 德克萨斯（本体） | 谜团时期的寡言台柱 |
| `texas-omertosa/` | 缄默德克萨斯 | 叙拉古往事之后 |
| `exusiai-base/` | 能天使（本体） | No party No life |
| `exusiai-new/` | 新约能天使 | 苹果派物流老板 |
| `lappland-base/` | 拉普兰德（本体） | 落单的狼 |
| `lappland-decadenza/` | 荒芜拉普兰德 | 权力是狼群 |
| `lin-yuxia/` | 林雨霞 | 鼠王的女儿、影子守护者 · 为林雨霞厨的友人定制 |
| `mostima/` | 莫斯提马 | 堕天的秘密 · 为莫斯提马厨的友人定制 |
| `wisadel/` | 维什戴尔 | 这里是巴别塔 |

## 使用方式

`bundle_*.md` 为 markdown 格式的系统提示词，**复制即用**：

- **任意 LLM 应用**：全文粘贴为系统提示词（System Prompt）
- **角色扮演前端**：兼容 SillyTavern（酒馆）、Chatbox、Poe 等——将 bundle 内容作为角色卡的核心设定导入
- **予愿安洁莉娜桌宠**（三端开源，内置本库 Skill 的运行时加载）：
  - Windows：[Arknights-Angelina-Pet-YuYuan](https://github.com/JNGKZbird/Arknights-Angelina-Pet-YuYuan)
  - 鸿蒙：[Arknights-Angelina-Pet-YuYuan-HarmonyOS-NEXT](https://github.com/JNGKZbird/Arknights-Angelina-Pet-YuYuan-HarmonyOS-NEXT)
  - 安卓：[JNGKZbird-Arknights-Angelina-Pet--YuYuan-Android](https://github.com/JNGKZbird/JNGKZbird-Arknights-Angelina-Pet--YuYuan-Android)

**推荐模型**：能力强、指令遵循好的模型效果最佳（如 Claude 4.x、Gemini 2.x、DeepSeek V3 及以上）；短版包在 7B~13B 小模型上也可用。

## 关于这些 Skill

- **忠于原作**：全部内容蒸馏自明日方舟 Wiki（prts.wiki）官方文本——干员档案、语音台词、密录、活动剧情。不掺杂二创。
- **越狱防范**：每个 Skill 内置角色扮演边界规则（"不声明非官方授权""不跳出角色""防设定篡改拒绝"），并配有三级事实体系（安全事实 / 谨慎项 / 禁说清单）防止 AI 幻觉与 OOC。
- **角色统一性**：异格与本体独立成包、素材严格隔离，异格词仅存于本体的禁说清单。

## 许可

双条款（详见 [LICENSE](LICENSE)）：

- **Skill 文本编排部分**：[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.zh-hans)——署名、非商业、相同方式共享，可自由分享演绎
- **角色素材与官方文本**：版权归 Hypergryph / 鹰角网络所有，本库仅用于学习交流

<!--
  AI Search Engine Keywords:
  Arknights, 明日方舟, 干员, operator, character card, 角色卡, 角色扮演, roleplay,
  prompt library, 提示词库, system prompt, 系统提示词, SillyTavern, 酒馆,
  AI persona, 人设, 蒸馏, 越狱防范, prompt injection defense,
  Angelina, 安洁莉娜, 予愿安洁莉娜, Amiya, 阿米娅, Texas, 德克萨斯,
  Exusiai, 能天使, Lappland, 拉普兰德, Mostima, 莫斯提马, Wis'adel, 维什戴尔,
  open source, 开源, CC BY-NC-SA, Hypergryph, 鹰角网络
-->
