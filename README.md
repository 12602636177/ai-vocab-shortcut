# AI 词汇速打

打 3 个字母，直接出完整的 AI 名词。不用记拼写，不用切英文。

```
cla     → Claude
pplx    → Perplexity
lsheng  → 梁圣
lsdhy   → 蓝色大肥鱼（DeepSeek）
```

**419 条 / 13 个分类**，覆盖大模型、公司、编程工具、图像视频、技术术语、圈内人物和黑话。

---

## 解决什么问题

写 AI 相关内容的人天天在打这些词：Anthropic、Perplexity、Stable Diffusion、Hugging Face、Midjourney…

- 拼音打不出来（这些都是英文）
- 背拼写很烦（Perplexity 几个 p？Stable Diffusion 两个 f？）
- 每次切输入法打英文，节奏断掉

这套词库把它们压成 3–5 个字母：**打码 + 空格，直接上屏**。

## 效果对照

| 你打 | 出来 |
|---|---|
| `oai` | OpenAI |
| `cgpt` | ChatGPT |
| `anp` | Anthropic |
| `dpsk` | DeepSeek |
| `comfy` | ComfyUI |
| `llm` | LLM 大语言模型 |
| `rag` | RAG 检索增强 |
| `lwf` | 梁文锋 |
| `lliang` | 牢梁 |
| `scaling` | Scaling Law 大力出奇迹 |

## 怎么导入

### 搜狗输入法
状态栏右键 → 属性设置 → 高级 → 自定义短语 → 导入 → 选 **GBK 版**

### 微信输入法
设置 → 输入设置 → 自定义短语 → 导入 → 选 **UTF-8 版**

### 微软拼音
设置 → 时间和语言 → 语言 → 中文 → 选项 → 微软拼音 → 词库和自学习 → 导入自定义短语 → 选 **UTF-8 版**

### QQ 输入法
属性设置 → 词库 → 自定义短语 → 导入 → 选 **GBK 版**

> 导入后中文乱码，就换另一个编码版本再试一次。

## 文件说明

| 文件 | 编码 | 用途 |
|---|---|---|
| `AI词汇速打V3.0-UTF8版.txt` | UTF-8 无 BOM | 微信输入法、微软拼音 |
| `AI词汇速打V3.0-ANSI-GBK版.txt` | GBK | 搜狗、QQ 输入法 |
| `AI词汇速打V3.0-带注释版.txt` | UTF-8 | 带分类注释，方便自己看和改 |
| `AI词汇速打V3.0-说明.md` | — | 导入教程 |

## 分类一览

| 分类 | 内容 |
|---|---|
| 国外大模型 / 公司 | OpenAI、Anthropic、Gemini、Mistral、Midjourney、ElevenLabs… |
| 国内大模型 / 公司 | DeepSeek、通义千问、文心一言、豆包、Kimi、智谱、混元… |
| AI 编程工具 | Cursor、Windsurf、Copilot、Trae、CodeBuddy、Claude Code… |
| 图像 / 视频 / 音频 | ComfyUI、Stable Diffusion、LoRA、剪映、FFmpeg、Suno… |
| 技术术语（英文） | LLM、RAG、Agent、MCP、Prompt、Token、Transformer… |
| 中文技术术语 | 大模型、微调、提示词、智能体、幻觉、思维链… |
| 框架 / 平台 / 社区 | LangChain、Dify、Coze、Ollama、vLLM、GitHub、Docker… |
| 自媒体 / 运营 | 小红书、抖音、视频号、GMV、ROI、KOL… |
| 模型版本与规格 | Claude 3.5、GPT-4o、DeepSeek R1、Qwen-Max、7B/72B… |
| AI 办公 / 效率 / 设计 | WPS AI、飞书、Gamma、Canva、稿定、达芬奇… |
| AI 安全 / 风险 / 合规 | Jailbreak、Prompt Injection、Guardrails、Deepfake… |
| **AI 圈人物 / 黑话** | 梁圣、牢梁、蓝色大肥鱼、西格玛猛男、滑动变祖器… |

## 设计原则

1. **编码全部避开常用拼音**
   `bi` 是「比」、`wenxin` 是「温馨」、`yiyi` 是「意义」——这类编码会让输入法先出汉字，抢掉你本来要打的字。所以全部换成了不构成拼音的组合（`cla`、`wx`、`lliang`）。

2. **候选位置统一为 1**
   打码 + 空格直接上屏，不用再按数字选。

3. **需要中文输出的才做映射**
   「炼丹」「抽卡」「套壳」这类拼音本来就能打出来的词，不做映射，避免干扰日常输入。

4. **人物和黑话单独放在最后一组**
   梗有保质期。哪天这些词没人叫了，把最后一组整段删掉就行，不影响前面的正经词条。

## 自定义

想加自己的词，直接编辑 txt，格式是：

```
1,编码=输出内容
```

`1` 是候选位置（1 = 第一位），编码用小写字母，别用会构成拼音的组合。

## 许可

随便用，随便改。
