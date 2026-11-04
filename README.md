# Universal RenPy Translator

**Read this in other languages:** [Русский](README.ru.md) | [简体中文](README.zh.md) | [Español](README.es.md) | [Français](README.fr.md) | [日本語](README.ja.md) | [العربية](README.ar.md)

Universal RenPy Translator is a powerful, cross-platform desktop application designed for offline translation of Ren'Py visual novels. It uses local AI models via **Ollama** to deliver high-quality, uncensored translations without sending your text to third-party servers.

This repository is for the compiled releases. The source code is closed.

---

## ✨ Features

- **100% Offline & Unlimited:** No API keys required, no character limits. Your texts never leave your computer, and translation will never be interrupted by server errors.
- **Uncensored 18+ Translation:** Uses powerful local AI models (HY-MT1.5 & Hy-MT2) and a built-in profanity glossary to preserve the original tone, slang, and mature content without artificial softening.
- **In-Game Overlay Injection:** Injects a floating language switcher directly into the game, allowing seamless switching between original and translated text.
- **All-in-One & 2-Click Setup:** Auto-unpacks RPA archives, decompiles `.rpyc` files, and lets you launch the translated game directly from the app.
- **Broad Ren'Py Support:** Works flawlessly with Ren'Py 6, 7, and 8+ engines.
- **Source Language Detection:** Automatically detects the language of the original game files to prevent translation errors.
- **In-Game Font Size Control:** Dynamically adjust the text size in-game to fit any UI layout.
- **Smart Context (CTX):** Passes previous dialogue lines to the AI to maintain narrative consistency and correct pronoun usage.
- **Incremental Translation (Diff):** Updates translations for new game chapters without re-translating the entire game from scratch.
- **Character Gender Detection:** Automatically detects the speaker's gender to apply correct grammatical forms (crucial for Russian and other gendered languages).
- **Built-in QA Checker:** Automatically scans the translated file for lost tags, unbalanced brackets, and overlong strings.
- **CAT Editor:** A visual table-based editor to manually tweak translations and fix QA issues directly inside the app.
- **7 UI Languages:** English, Russian, Spanish, French, Japanese, Chinese, and Arabic.

---

## 📸 Screenshots

![Main Window](https://github.com/user-attachments/assets/6cbebbd5-1b3b-44a4-8ded-03889dcf9656)
*Main interface with support block and settings*

![Translation in progress](https://github.com/user-attachments/assets/1544fad3-0075-4700-b6b5-05fb586e702e)
*Translation process with real-time logs*

![QA Checker](https://github.com/user-attachments/assets/a67467ae-a2b8-4a99-a3ab-0468ad37c36d)
*Built-in QA Inspector*

![CAT Editor](https://github.com/user-attachments/assets/20d6533a-0f11-4b37-8a06-3dfb6757fe48)
*CAT Editor for manual translation adjustments*

![In-game Overlay Button](https://github.com/user-attachments/assets/a47c7d35-5ca1-4805-874e-3feb9904cd6d)
*In-game language switcher button*

![In-game Overlay Menu](https://github.com/user-attachments/assets/b7ea0dfc-aa03-4189-a478-e9060331866c)
*In-game language and font size selection menu*

---

## 📥 Download & Installation

1. Go to the **[Releases](../../releases/latest)** section on the right side of this page.
2. Download the latest `Universal-RenPy-Translator.zip` file.
3. Extract the archive to any folder on your PC (do not run the `.exe` directly from the archive).
4. Run `Universal RenPy Translator.exe`.

### Prerequisites
You must have **Ollama** installed and running on your computer.
1. Download and install Ollama from [ollama.com](https://ollama.com).
2. The program will prompt you to download the required AI model (`huihui_ai/hy-mt1.5-abliterated:7b`) on the first run.

---

## ⚠️ Important: Antivirus False Positives

Because this application is compiled using PyInstaller and **does not have a paid digital signature**, Windows Defender and some antivirus programs may show a false positive (e.g., "Trojan:Win32/Wacatac" or "Wacapew").

**This is a known issue for all Python-based executables.** The application is completely safe and contains no malicious code.

**How to fix:**
1. Allow the file in your antivirus (add the folder to Exclusions).
2. If you are using Windows Defender, you can submit the file to Microsoft as a false positive. Usually, they fix it within 24 hours.

---

## 💖 Support the Project

Universal RenPy Translator is completely free and open for everyone. If you find it useful and want to support further development, you can do so here:

- **[Boosty](https://boosty.to/universal_renpy_translator)**
- **[DonationAlerts](https://www.donationalerts.com/r/urtranslator)**
- **Crypto (USDT TRC-20):** [TTL4jWvaS21qEKur1i92Tv7G3h1LWbARTQ](https://link.trustwallet.com/send?asset=c195_tTR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t&address=TTL4jWvaS21qEKur1i92Tv7G3h1LWbARTQ)

Thank you for your support! ❤️

---

## 📄 License & Credits

- **HY-MT1.5 7B Abliterated** translation model is developed by Tencent Hunyuan Team under the Hunyuan Open Source License v1.0. 
- This product includes models developed by Tencent Hunyuan Team. 
- License: [https://hunyuan.tencent.com/license](https://hunyuan.tencent.com/license)
- Ren'Py is a trademark of Tom Rothamel. This application is not affiliated with the official Ren'Py team.
