# PPT2Video

画个视频 - HTML 格式 PPT 转视频编辑器

## 相关链接

### 官方网址：[ppt.neirongpai.com](https://ppt.neirongpai.com/)

### 文档教程：[feishu.cn](https://gcnmglnmucfp.feishu.cn/wiki/DFc8wRK3eifzdWk6C3Fc6veCnjb)

### SKILL：[ppt2video-skill](https://github.com/dayuanlog/ppt2video-skill)


---

## 功能特性

- **场景编辑** — 导入 HTML 文件作为场景，支持拖拽排序
- **AI 配音** — 支持 MiniMax TTS 语音合成，中文音色
- **动画效果** — GSAP 动画引擎，支持入场动画和转场效果
- **视频导出** — 支持导出 MP4/WebM 格式，分辨率最高 1080P
- **本地渲染** — 无需上传云端，本地完成渲染，保护隐私

## 系统要求

- Windows 10 及以上（64位）
- 需要网络连接（AI 配音功能需要 MiniMax API Key）

## 下载安装包

请前往 [Releases](https://github.com/dayuanlog/ppt2video/releases) 页面下载最新版本。

## AI 配音设置

1. 点击左上角「设置」按钮
2. 选择「AI 配音设置 (MiniMax)」
3. 填写 MiniMax API Key 和音色 ID
4. 保存后即可使用 AI 配音功能

> API Key 申请：https://www.minimaxi.com/

## 技术栈

- Electron + React + TypeScript
- GSAP 动画引擎
- Hono 文件服务
- MiniMax TTS API

