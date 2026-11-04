# Universal RenPy Translator

**他の言語で読む:** [English](README.md) | [Русский](README.ru.md) | [简体中文](README.zh.md) | [Español](README.es.md) | [Français](README.fr.md) | **日本語** | [العربية](README.ar.md)

Universal RenPy Translatorは、Ren'Pyビジュアルノベルのオフライン翻訳向けに設計された、強力なクロスプラットフォームデスクトップアプリケーションです。**Ollama**を介してローカルAIモデルを使用し、テキストをサードパーティのサーバーに送信することなく、高品質で無検閲の翻訳を提供します。

このリポジトリはコンパイル済みリリース用です。ソースコードは非公開です。

---

## ✨ 機能

- **100%オフライン＆無制限:** APIキーは不要で、文字数制限もありません。テキストがコンピューターから外部に送信されることはなく、サーバーエラーで翻訳が中断されることもありません。
- **無検閲の18+翻訳：** 強力なローカルAIモデル（HY-MT1.5 および Hy-MT2）と、下品な表現の専用用語集を使用して、元のトーン、スラング、成人向けコンテンツをマイルドにせずに保持します。
- **ゲーム内オーバーレイ注入:** ゲーム内にフローティング言語切り替え機能を直接注入し、原文と翻訳文をシームレスに切り替えられます。
- **オールインワン＆2クリックでセットアップ:** RPAアーカイブの自動解凍、`.rpyc`ファイルのデコンパイルを行い、アプリから直接翻訳済みゲームを起動できます。
- **幅広いRen'Pyサポート:** Ren'Py 6、7、8+エンジンで完璧に動作します。
- **ソース言語の自動検出:** 翻訳エラーを防ぐため、元のゲームファイルの言語を自動的に検出します。
- **ゲーム内フォントサイズ調整:** ゲーム内のテキストサイズを動的に調整し、あらゆるUIレイアウトに適合させます。
- **スマートコンテキスト (CTX):** 以前の対話行をAIに渡し、物語の一貫性と正しい代名詞の使用を維持します。
- **差分翻訳 (Diff):** ゲーム全体を最初から再翻訳することなく、ゲームの新しい章の翻訳を更新します。
- **キャラクターの性別検出:** 話者の性別を自動的に検出し、正しい文法形式を適用します（ロシア語など、性別の区別がある言語にとって極めて重要です）。
- **内蔵QAチェッカー:** 翻訳ファイルを自動スキャンし、失われたタグ、不一致の括弧、長すぎる文字列をチェックします。
- **CATエディタ:** アプリ内で直接翻訳を手動で微調整し、QAの問題を修正するための視覚的なテーブルベースのエディタです。
- **7つのUI言語:** 英語、ロシア語、スペイン語、フランス語、日本語、中国語、アラビア語。

---

## 📸 スクリーンショット

![メイン画面](https://github.com/user-attachments/assets/f1e5d0f8-98a1-46de-b5bc-50bb6977b903)
*サポートブロックと設定を含むメインインターフェース*

![翻訳進行中](https://github.com/user-attachments/assets/8a8749b6-cd4c-4227-80af-5c8d6ad8ff60)
*リアルタイムログ付きの翻訳プロセス*

![QAチェッカー](https://github.com/user-attachments/assets/7e462960-8a0d-430c-9315-ce868009e8e8)
*内蔵QAインスペクター*

![CATエディタ](https://github.com/user-attachments/assets/e1354ffd-f24b-4fdc-a6e5-7522f122c1fe)
*翻訳の手動調整用CATエディタ*

![ゲーム内オーバーレイボタン](https://github.com/user-attachments/assets/82ec760c-32b7-4f31-b037-2a4909c397d2)
*ゲーム内言語切り替えボタン*

![ゲーム内オーバーレイメニュー](https://github.com/user-attachments/assets/2eae9d52-56d4-423b-8b47-d977b5dc87b4)
*ゲーム内言語とフォントサイズの選択メニュー*

---

## 📥 ダウンロードとインストール

1. このページの右側にある**[Releases](../../releases/latest)**セクションに移動します。
2. 最新の`Universal-RenPy-Translator.zip`ファイルをダウンロードします。
3. アーカイブをPCの任意のフォルダに解凍します（アーカイブから直接`.exe`を実行しないでください）。
4. `Universal RenPy Translator.exe`を実行します。

### 前提条件
コンピューターに**Ollama**がインストールされ、実行されている必要があります。
1. [ollama.com](https://ollama.com)からOllamaをダウンロードしてインストールします。
2. 初回実行時に、必要なAIモデル（`huihui_ai/hy-mt1.5-abliterated:7b`）をダウンロードするよう促されます。

---

## ⚠️ 重要：アンチウイルスの誤検知について

このアプリケーションはPyInstallerを使用してコンパイルされており、**有料のデジタル署名がない**ため、Windows Defenderや一部のアンチウイルスソフトが誤検知（例：「Trojan:Win32/Wacatac」や「Wacapew」）を表示する場合があります。

**これはPythonベースのすべての実行可能ファイルにおける既知の問題です。** このアプリケーションは完全に安全であり、悪意のあるコードは含まれていません。

**解決方法：**
1. アンチウイルスソフトでこのファイルを許可します（フォルダを除外リストに追加します）。
2. Windows Defenderを使用している場合は、ファイルを誤検知としてMicrosoftに報告できます。通常、24時間以内に修正されます。

---

## 💖 プロジェクトのサポート

Universal RenPy Translatorは完全に無料で、誰にでも公開されています。役に立ったと感じ、今後の開発を支援したい場合は、以下から行うことができます：

- **[Boosty](https://boosty.to/universal_renpy_translator)**
- **[DonationAlerts](https://www.donationalerts.com/r/urtranslator)**
- **暗号通貨 (USDT TRC-20)：** [TTL4jWvaS21qEKur1i92Tv7G3h1LWbARTQ](https://link.trustwallet.com/send?asset=c195_tTR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t&address=TTL4jWvaS21qEKur1i92Tv7G3h1LWbARTQ)

ご支援ありがとうございます！❤️

---

## 📄 ライセンスとクレジット

- **HY-MT1.5 7B Abliterated** 翻訳モデルは、Hunyuan Open Source License v1.0に基づきTencent Hunyuanチームによって開発されました。
- **Hy-MT2-7B-Abliterated** モデルはTencentのモデルに基づいており、**Apache 2.0ライセンス**の下で配布されています（アブリテレーションとGGUFへの変換はオープンソースコミュニティによって行われました）。
- 本製品には、Tencent Hunyuanチームによって開発されたモデルが含まれています。
- ライセンスリンク：[Hunyuan License](https://hunyuan.tencent.com/license) および [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0)。
- Ren'PyはTom Rothamelの商標です。このアプリケーションは、公式のRen'Pyチームとは提携していません。
