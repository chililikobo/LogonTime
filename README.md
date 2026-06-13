# LogonTime

![Latest Release](https://img.shields.io/github/v/release/chililikobo/LogonTime?color=blue)
![Downloads](https://img.shields.io/github/downloads/chililikobo/LogonTime/total?color=228b22)
![License](https://img.shields.io/badge/license-Freeware-blueviolet.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)

[English](#english) | [日本語](#日本語)

---

## English

LogonTime is an ultra-fast, lightweight command-line tool that analyzes Windows event logs to calculate and display user logon/logoff durations. Running as a single binary with zero external runtime dependencies, it can be efficiently utilized to assist with timecard data entry or serve as evidence of working hours.

🌐 **For detailed specifications and support, please visit the [Official Website](https://chililikobo.github.io/en/).**

### 🚀 Installation

No installation or special configuration is required. Simply place `LogonTime.exe` in any folder and run it. To uninstall, just delete the file.

* **Supported OS**: Windows 10 (1607+) / Windows 11 / Windows Server 2012+

### 🛠 Usage

#### 1. Simple Run (Double-Click)
Double-click `LogonTime.exe` to display logs for the default period (past 30 days) in the console. It will wait for a keypress before closing.

#### 2. Command-Line Execution
Run from Command Prompt or PowerShell with optional arguments:

```cmd
LogonTime.exe [days] [options]
```

* `[days]` : Number of past days to retrieve (Default: 30)
* `--csv` : Output results in CSV format (for script integration)
* `--json` : Output results in JSON format
* `-h`, `--help` : Show the help message

> ⚠️ **Note**: Depending on your environment, Administrator privileges may be required to read the system event log. If you encounter an "Access denied" error, please run your terminal as Administrator.

### 📄 License & Disclaimer

* This software is freeware and can be used freely for both personal and commercial purposes.
* This software is provided "as-is" without any warranty. Use it at your own risk.
* For more detailed terms, please check the [Official Website](https://chililikobo.github.io/en/).

---

## 日本語

Windowsのイベントログからユーザーのログオン・ログオフ時間を解析し、滞在時間を自動計算して一覧表示する超高速・軽量なコマンドラインツールです。ランタイム不要で単一ファイルのみで動作し、勤怠アプリの入力支援や稼働のエビデンス（証跡）としてもお使いいただけます。

🌐 **詳細な仕様やサポート情報については、[公式ホームページ](https://chililikobo.github.io/) をご覧ください。**

### 🚀 インストール

インストール・特別な設定は不要です。ダウンロードした `LogonTime.exe` を任意のフォルダに配置するだけで使用できます（アンインストールはファイルを削除するだけです）。

* **対応OS**: Windows 10 (1607以降) / Windows 11 / Windows Server 2012 以降

### 🛠 使い方

#### 1. ダブルクリックで簡易実行

`LogonTime.exe` をダブルクリックすると、デフォルト設定（過去30日分）のログをコンソールに表示し、終了前にキー入力を待ちます。

#### 2. コマンドライン（ターミナル）から実行

コマンドプロンプトやPowerShell等から、引数やオプションを指定して実行できます。

```cmd
LogonTime.exe [days] [options]
```

* `[days]` : 取得する過去の日数を数値で指定（デフォルト: 30）
* `--csv` : CSVフォーマットで出力（他スクリプト連携用）
* `--json` : JSONフォーマットで出力
* `-h`, `--help` : ヘルプメッセージを表示

> ⚠️ **注意**: 環境によってはイベントログの読み取りに「管理者権限」が必要です。アクセス拒否エラーが出た場合は、ターミナルを「管理者として実行」してお試しください。

### 📄 ライセンス・免責事項

* 本ソフトウェアはフリーウェアです。個人・法人を問わず無料で自由にご利用いただけます。
* 本ソフトウェアは「現状有姿」で提供され、動作保証や損害に対する補償は一切いたしかねます。自己責任でご利用ください。
* 二次配布等の詳しい利用規約については、[公式サイト](https://chililikobo.github.io/)をご確認ください。

