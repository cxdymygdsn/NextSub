# NextSub

**A smart subtitle tool — ASR · Alignment · Editing · NLE Bridge**
<img width="1402" height="928" alt="ScreenShot_2026-09-08_221244_590" src="https://github.com/user-attachments/assets/8de4432c-7aa1-4110-9bac-049d3d1e91d3" />
<img width="1402" height="928" alt="ScreenShot_2026-09-08_221304_543" src="https://github.com/user-attachments/assets/99a08ee0-25eb-4f14-8157-6c9af52741aa" />
<img width="1402" height="928" alt="ScreenShot_2026-09-08_221316_976" src="https://github.com/user-attachments/assets/788e36af-8b8c-4f3f-aa8b-ff4f636d3e53" />
<img width="1402" height="928" alt="ScreenShot_2026-09-08_221924_314" src="https://github.com/user-attachments/assets/f5073edd-3062-4eef-8220-160459022ab0" />
<img width="1402" height="928" alt="ScreenShot_2026-09-08_222002_394" src="https://github.com/user-attachments/assets/1dea2c48-d7f6-4aa3-9285-e06aba28f85b" />

---

## English

### Features

**🎙 Speech to Subtitles**

- ASR subtitle generation (supports qwen3-asr GGUF models)
- Script matching: align your existing transcript to the audio timeline to generate subtitles in one click
- Audio transcription: convert audio content to plain text quickly
- Multi-language: Chinese / English / Japanese / German / French / Spanish and more

**✍️ Smart Text Processing**

- Text splitting: break long text into lines at natural semantic boundaries (punctuation rhythm for Chinese; balanced line width + connector-first breaks for English)
- Text cleaning: one-click conversion between symbols and Chinese units (e.g. "5MPa ↔ 五兆帕")

**📝 Subtitle Post-editing**

- Smart Convert (VIP): convert spoken-style Chinese numbers/units to standard notation (e.g. "三十九项 → 39 项", "五兆帕 → 5MPa")
- Smart Split (VIP): automatically split oversized subtitle blocks at semantic points, dividing duration proportionally by character count
- Display-layer editing: split / merge / delete / undo / reset — WYSIWYG, works directly on imported subtitles

**🎬 DaVinci / Premiere Bridge**

- DaVinci Resolve: push subtitles, pull audio tracks (supports v18.5–21)
- Adobe Premiere Pro: subtitle push / audio pull (supports 2022–2026)

**🖥 Interface**

- Chinese / English UI switching
- Light / Gray / Dark themes
- GPU backends: Vulkan / CUDA / CPU

### Requirements

- Windows 10/11 (64-bit)
- GPU: NVIDIA / AMD / Intel (iGPU works, discrete GPU recommended)

### Install

- Download the release archive and extract — portable, no installation needed
- Models are downloaded on first use (or place them manually in the model directory)

### Quick Start

```
1. Import audio / pull audio track
2. Generate subtitles, or match an existing script
3. Right-click in the output area: Smart Convert / Smart Split / manual fine-tune
4. Export SRT / push to DaVinci Resolve or Premiere Pro
```

### Support

Some advanced features are donor-exclusive (batch processing, Smart Convert, Smart Split, etc.).
Support development on [Afdian](https://afdian.com/a/xfyy_gao) — thank you!

### License

Personal software. Commercial use is not permitted.

---

## 中文

### 功能简介

**🎙 字幕生成**

- 语音识别生成字幕（支持 qwen3-asr GGUF 模型）
- 文稿匹配：已有文稿直接对齐音频时间轴，一键生成字幕
- 音频转写：音频内容快速转为纯文本
- 多语言支持：中文 / 英文 / 日文 / 德文 / 法文 / 西班牙文等

**✍️ 智能文本处理**

- 文本分段：按语义断点智能分行（中文按标点节奏断句；英文按行宽均衡 + 连词优先）
- 文本清洗：符号 ↔ 中文单位一键互转（如 "5MPa ↔ 五兆帕"）

**📝 字幕后处理**

- 智能转换（VIP）：中文数字 / 单位 → 标准符号写法（如 "三十九项 → 39 项"、"五兆帕 → 5MPa"）
- 智能分割（VIP）：超长字幕块自动按语义断点拆分，时间按字数均分
- 显示层编辑：分割 / 合并 / 删除 / 撤销 / 重置——所见即所得，导入的字幕也能直接编辑

**🎬 达芬奇 / Premiere 桥接**

- DaVinci Resolve：推送字幕、拉取音轨（版本号18.5-21）
- Adobe Premiere Pro：字幕推送 / 音频拉取（版本号2022-2026）

**🖥 界面**

- 中英双语界面切换
- 亮色 / 灰色 / 暗色三主题
- GPU 加速：Vulkan / CUDA / CPU 后端自适应

### 运行环境

- Windows 10/11（64 位）
- 显卡：NVIDIA / AMD / Intel（核显可运行，独显更快）

### 安装

- 下载发布版压缩包解压即用（绿色免安装）
- 模型文件首次使用时按提示下载（或手动放入模型目录）

### 使用流程

```
1. 导入音频 / 拉取音轨
2. 字幕生成，或文稿匹配
3. 输出区右键：智能转换 / 智能分割 / 手动微调
4. 导出 SRT / 推送到达芬奇或 Premiere
```

### 支持

部分高级功能为捐赠用户专享（批量处理、字幕智能转换、智能分割等）——
支持开发请访问 [爱发电](https://afdian.com/a/xfyy_gao)，感谢你的支持！
