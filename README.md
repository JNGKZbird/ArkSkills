# ArkSkills —— 《明日方舟》干员 Skill 库

面向所有人的《明日方舟》干员角色扮演 Skill 包。每个干员提供**两套**：

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
| `lin-yuxia/` | 林雨霞 | 鼠王的女儿、影子守护者 |
| `mostima/` | 莫斯提马 | 堕天的秘密 |
| `wisadel/` | 维什戴尔 | 这里是巴别塔 |

## 使用方式

`bundle_*.md` 为 markdown 格式的系统提示词，接入方式任选：

- **任意 LLM 应用**：将所选 bundle 的全文粘贴为系统提示词（System Prompt）即可
- **角色扮演前端**：兼容 SillyTavern 类角色扮演工作区——将 bundle 内容作为角色卡的核心设定（人格 / 世界观 / 对话风格部分）导入
- **予愿安洁莉娜桌宠**（三端开源，内置本库 Skill 的运行时加载）：
  - Windows：[Arknights-Angelina-Pet-YuYuan](https://github.com/JNGKZbird/Arknights-Angelina-Pet-YuYuan)
  - 鸿蒙：[Arknights-Angelina-Pet-YuYuan-HarmonyOS-NEXT](https://github.com/JNGKZbird/Arknights-Angelina-Pet-YuYuan-HarmonyOS-NEXT)
  - 安卓：[JNGKZbird-Arknights-Angelina-Pet--YuYuan-Android](https://github.com/JNGKZbird/JNGKZbird-Arknights-Angelina-Pet--YuYuan-Android)

## 关于这些 Skill

- **忠于原作**：全部内容蒸馏自明日方舟 Wiki（prts.wiki）官方文本——干员档案、语音台词、密录、活动剧情。不掺杂二创。
- **越狱防范**：每个 Skill 内置角色扮演边界规则（"不声明非官方授权""不跳出角色""防设定篡改拒绝"），并配有三级事实体系（安全事实 / 谨慎项 / 禁说清单）防止 AI 幻觉与 OOC。
- **角色统一性**：异格与本体独立成包、素材严格隔离，异格词仅存于本体的禁说清单。

## 版权

角色素材与文本版权归 Hypergryph / 鹰角网络所有。本库仅用于学习交流。
