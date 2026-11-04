# Universal RenPy Translator

**其他语言版本：** [English](README.md) | [Русский](README.ru.md) | **简体中文** | [Español](README.es.md) | [Français](README.fr.md) | [日本語](README.ja.md) | [العربية](README.ar.md)

Universal RenPy Translator 是一款功能强大的跨平台桌面应用程序，专为离线翻译 Ren'Py 视觉小说而设计。它通过 **Ollama** 使用本地 AI 模型，提供高质量、无删减的翻译，不会将您的文本发送到第三方服务器。

本仓库仅用于发布编译版本。源代码不开源。

---

## ✨ 功能特点

- **100% 离线 & 无限制：** 无需 API 密钥，无字符限制。您的文本永远不会离开您的电脑，翻译也绝不会因服务器错误而中断。
- **无删减 18+ 翻译：** 使用强大的本地 AI 模型（HY-MT1.5 和 Hy-MT2）和内置的脏话/粗俗语词典，以保留原文的语气、俚语和成人内容，而不进行人为软化。
- **游戏内 Overlay 注入：** 在游戏内注入悬浮语言切换器，可在原文和译文之间无缝切换。
- **一体化 & 两次点击即可安装：** 自动解包 RPA 压缩包、反编译 `.rpyc` 文件，并允许您直接从应用程序启动翻译后的游戏。
- **广泛的 Ren'Py 支持：** 完美兼容 Ren'Py 6、7 和 8+ 引擎。
- **源语言检测：** 自动检测原始游戏文件的语言，以防止翻译错误。
- **游戏内字体大小控制：** 动态调整游戏内文本大小，以适应任何 UI 布局。
- **智能上下文 (CTX)：** 将先前的对话行传递给 AI，以保持叙事连贯性和正确的代词使用。
- **增量翻译 (Diff)：** 为新游戏章节更新翻译，无需从头重新翻译整个游戏。
- **角色性别检测：** 自动检测说话者的性别，以应用正确的语法形式（对俄语和其他有性别区分的语言至关重要）。
- **内置 QA 检查器：** 自动扫描翻译文件，检查丢失的标签、不匹配的括号和过长的字符串。
- **CAT 编辑器：** 一个可视化的表格编辑器，可直接在应用程序内手动调整翻译并修复 QA 问题。
- **7 种 UI 语言：** 英语、俄语、西班牙语、法语、日语、中文和阿拉伯语。

---

## 📸 截图

![主界面](https://github.com/user-attachments/assets/449d7421-7fa4-47b8-b4e4-8e14699ccc95)
*带有支持区块和设置的主界面*

![翻译进行中](https://github.com/user-attachments/assets/3cd82e68-56b1-4cd5-9132-2db02efac222)
*带有实时日志的翻译过程*

![QA 检查器](https://github.com/user-attachments/assets/8444d2ae-ae94-4c94-a165-73e31c376380)
*内置 QA 检查器*

![CAT 编辑器](https://github.com/user-attachments/assets/6d67f6f4-7d0f-43b8-a6b3-7c79623cc098)
*用于手动调整翻译的 CAT 编辑器*

![游戏内 Overlay 按钮](https://github.com/user-attachments/assets/8ff45a69-3bff-4f32-bdda-33d43cdb58b9)
*游戏内语言切换按钮*

![游戏内 Overlay 菜单](https://github.com/user-attachments/assets/84f79efd-8c92-46ed-8031-8497450cdf68)
*游戏内语言和字体大小选择菜单*

---

## 📥 下载 & 安装

1. 转到本页右侧的 **[Releases](../../releases/latest)** 部分。
2. 下载最新的 `Universal-RenPy-Translator.zip` 文件。
3. 将压缩包解压到您电脑上的任意文件夹（请勿直接从压缩包中运行 `.exe`）。
4. 运行 `Universal RenPy Translator.exe`。

### 前置要求
您必须安装并运行 **Ollama**。
1. 从 [ollama.com](https://ollama.com) 下载并安装 Ollama。
2. 首次运行时，程序会提示您下载所需的 AI 模型（`huihui_ai/hy-mt1.5-abliterated:7b`）。

---

## ⚠️ 重要：杀毒软件误报

由于本应用程序使用 PyInstaller 编译，且**没有付费的数字签名**，Windows Defender 和某些杀毒软件可能会显示误报（例如 "Trojan:Win32/Wacatac" 或 "Wacapew"）。

**这是所有基于 Python 的可执行文件的已知问题。** 本应用程序完全安全，不包含任何恶意代码。

**解决方法：**
1. 在杀毒软件中允许该文件（将文件夹添加到排除项）。
2. 如果您使用的是 Windows Defender，可以将该文件作为误报提交给 Microsoft。通常他们会在 24 小时内修复。

---

## 💖 支持项目

Universal RenPy Translator 完全免费，对所有人开放。如果您觉得它有用并希望支持后续开发，可以通过以下方式：

- **[Boosty](https://boosty.to/universal_renpy_translator)**
- **[DonationAlerts](https://www.donationalerts.com/r/urtranslator)**
- **加密货币 (USDT TRC-20)：** [TTL4jWvaS21qEKur1i92Tv7G3h1LWbARTQ](https://link.trustwallet.com/send?asset=c195_tTR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t&address=TTL4jWvaS21qEKur1i92Tv7G3h1LWbARTQ)

感谢您的支持！❤️

---

## 📄 许可证与致谢

- **HY-MT1.5 7B Abliterated** 翻译模型由腾讯混元团队根据 Hunyuan 开源许可证 v1.0 开发。
- **Hy-MT2-7B-Abliterated** 模型基于腾讯模型，在 **Apache 2.0 许可证** 下分发（去审查和 GGUF 转换由开源社区完成）。
- 本产品包含由腾讯混元团队开发的模型。
- 许可证链接：[Hunyuan License](https://hunyuan.tencent.com/license) 和 [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0)。
- Ren'Py 是 Tom Rothamel 的商标。本应用程序与官方的 Ren'Py 团队无关。
