# 提示词库

94 条提示词、17 个分类，中文为主，直接复制就能用。原版 22 条（写作 / 编程 / 学习 / 翻译 / 分析决策 / 效率 / 角色扮演）全部保留，新增动漫视频、图片生成、考研英语、提示词优化、社交媒体、写作进阶、编程进阶、效率进阶、角色扮演进阶、工具对照。

在线打开：开启 GitHub Pages 后访问 `https://sui2qq.github.io/prompt-library/`（仓库名如有改动，地址随之改动）。

## 文件说明

| 文件 | 用途 | 给谁用 |
|---|---|---|
| `index.html` | 单文件网页版提示词库：搜索、分类筛选、复制、收藏、新建 / 编辑 / 删除、导出 / 导入 JSON、恢复示例，收藏存在浏览器 localStorage，支持深色模式 | 人直接打开用 |
| `prompts.json` | 全部 94 条的结构化数据：`{title, category, prompt}`，`{{变量}}` 为占位符 | 其他 AI / 程序直接读取，`raw.githubusercontent.com/sui2qq/prompt-library/main/prompts.json` |
| `prompts.csv` | 同上，表格版 | 表格、导入其他工具 |
| `README.md` | 本说明 | — |

## 怎么用

1. 人用：打开 `index.html`（或 Pages 地址），搜关键词，点卡片上的复制，把 `{{变量}}` 换成自己的内容再粘贴给 AI。
2. AI 用：直接读 `prompts.json`，按 `category` 筛选；用户描述含糊时，先按 `category` 找最接近的几条，再把主体、镜头、光线、配色、时长、禁令补全，不要照搬后丢掉用户的具体要求。
3. 自己加：网页里点「新建」，或直接往 `prompts.json` / `prompts.csv` 里加一行，再同步到 `index.html` 的内置数据里。

## 重点约定（不要改错）

- 治愈向动漫短视频：竖屏 9:16、5–10 秒、暖黄灯光、安静温柔，不要真人、不要文字水印，小橘猫常出镜。
- 城市夜景：8–15 秒、二次元动漫风，夜晚城市天桥 / 便利店、霓虹映在积水上、撑伞少女走过、镜头缓慢推进、青蓝霓虹 + 暖黄路灯，不要真人、不要文字 / 字幕 / 水印。
- 大肥鱼形象：深蓝长发到腰、发尾渐变浅蓝，头顶小卷毛，头侧尖尖深蓝鳍耳，身后一条大鲸鱼尾巴垂到脚边，蓝眼睛，纯色浅底，不要背景；默认衣服是浅米白无肩带短裙（裙摆到大腿中上部，裙侧深色碎花），原样复制时才用图里的棕色连帽卫衣。

## 来源库

灵感和部分结构来自这些高 star 开源库（2026-11-08 核对）：

- [f/prompts.chat](https://github.com/f/prompts.chat) — 176,262★，2923 条，CC0
- [x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) — 144,546★，仅作参考
- [elder-plinius/CL4R1T4S](https://github.com/elder-plinius/CL4R1T4S) — 51,829★，仅作参考
- [nidhinjs/prompt-master](https://github.com/nidhinjs/prompt-master) — 15,666★，模糊描述改写成精准提示词
- [yihui-dev/awesome-opus5-5-videos](https://github.com/yihui-dev/awesome-opus5-5-videos) — 14,130★
- [LangGPTai/LangGPT](https://github.com/LangGPTai/LangGPT) — 12,679★
- [EmbraceAGI/awesome-chatgpt-zh](https://github.com/EmbraceAGI/awesome-chatgpt-zh) — 11,815★
- [ZeroLu/awesome-nanobanana-pro](https://github.com/ZeroLu/awesome-nanobanana-pro) — 10,383★
- [ai-boost/awesome-prompts](https://github.com/ai-boost/awesome-prompts) — 9,190★
- [rockbenben/ChatGPT-Shortcut](https://github.com/rockbenben/ChatGPT-Shortcut) — 8,923★
- [langgptai/wonderful-prompts](https://github.com/langgptai/wonderful-prompts) — 6,390★
- [langgptai/awesome-claude-prompts](https://github.com/langgptai/awesome-claude-prompts) — 5,571★

## 许可

- 提示词内容（`prompts.json` / `prompts.csv` / 网页内置数据）：CC0-1.0，随便用。
- 网页代码（`index.html`）：MIT。
