# Gemini CLI Portable for Windows

WindowsでGemini CLIを、**インストール不要・管理者権限なし**でポータブル実行するためのバッチファイルです。

A portable batch file for Windows that automatically downloads and runs Gemini CLI without installation or admin rights.

---

## ✨ 特徴 (Features)

*   **インストール不要:** PCのレジストリやシステムフォルダを一切汚しません。
*   **管理者権限不要:** ファイルをダウンロードして実行するだけです。
*   **完全ポータブル:** USBメモリやネットワークドライブに置くだけで、どのWindows PCでも同じ環境を即座に再現できます。
*   **常に最新版:** 実行するたびに、常に公式サイトから最新版の`node.exe`と`gemini.js`をダウンロードします。
*   **堅牢な設計:** ダウンロード失敗時の自動リトライ機能や、サーバーからのアクセス拒否を回避する工夫が施されています。

## 💻 使い方 (Usage)

1.  **リリースページから最新版をダウンロード:**
    *   **[➡️ 最新のリリースをダウンロードする](https://github.com/KM170/Gemini_CLI_Portable/releases/latest)**
    *   `Gemini_CLI_Portable.zip` をダウンロードし、好きな場所に解凍してください。

2.  **バッチファイルを実行:**
    *   解凍したフォルダの中にある `Gemini_CLI_Portable.bat` をダブルクリックします。

3.  **初回認証:**
    *   初回のみ、ブラウザが自動で起動し、Googleアカウントでの認証が求められます。画面の指示に従ってログインしてください。

これだけで、セットアップは完了です。次回以降は、自動で作成される `Gemini CLI.lnk` ショートカットから起動するのが簡単です。

## 🤔 なぜこれが必要なのか？ (Motivation)

従来のGemini CLIの導入方法は、`Node.js`の事前インストールや、管理者権限が必要な`npm`コマンドの実行など、特に非開発者にとっては多くの障壁がありました。

このツールは、2025年7月頃にGoogleが`gemini.js`の単独配布を開始したことを受け、「`node.exe`と`gemini.js`の2ファイルさえあれば動く」という特性を最大限に活かし、**誰でも・どこでも・安全に** Gemini CLIを試せるようにすることを目的に開発されました。
