# GoodGoodBox 隐私政策 / Privacy Policy / プライバシーポリシー

最后更新 / Last updated / 最終更新：2026-10-04  
开发者 / Developer / 開発者：苏承欣

---

## 简体中文

本政策适用于 GoodGoodBox（收纳盒 Good Good Box，简称 GGB）的 Windows 桌面版及 Microsoft Store 版。

### 1. 基本原则

GGB 主要在本机运行，不要求注册 GGB 账号，不内置广告或行为分析服务，不自动向开发者上传使用统计、错误报告或用户文件。开发者不会通过 GGB 收集、出售用户的小说、图片、参考音频或生成的听书音频。

### 2. 本地处理的数据与用途

- **窗口收纳：**读取窗口标题、程序路径、进程和窗口标识、窗口位置、显示器信息，并检测鼠标位置和快捷键，用于识别面板、贴边、展开和恢复。保存必要的面板记录与设置。
- **参考画布：**处理用户导入的图片及其位置、缩放和画布设置；选择保存画布时，可能保存图片副本及布局。
- **电子书与听书：**读取用户打开的 TXT 文件，保存文件路径、文件哈希、书名、章节、阅读／听书位置、音色及播放设置。语音合成在本机执行，不使用在线语音合成 API；小说正文和参考音频不因本地听书而上传。
- **缓存与诊断：**在本机保存生成音频、预加载缓存及必要的运行记录。诊断记录可能包含文件路径、窗口标题或错误信息，不会自动提交给开发者。

GGB 的窗口与快捷键功能不用于记录其他软件中的输入内容，也不用于持续录制屏幕或麦克风。

### 3. 网络连接与第三方服务

下列功能可能联网：

- EXE 版检查更新时访问 GitHub；若启用启动时检查，该访问会自动发生。商店版由 Microsoft Store 管理更新。
- 用户下载或修复听书模块时，访问模型、运行环境和依赖的提供方，例如 GitHub、ModelScope、Python.org、PyPI 和 PyTorch 下载服务。
- 用户打开网页／视频时，通过 WebView2 访问所选网站。网站可能设置 Cookie、保存登录状态或收集浏览信息；相关资料由网站及 WebView2 的服务提供方按其政策处理。

这些服务可能接收 IP 地址、请求时间、请求内容及客户端信息。GGB 不向模型下载服务附带发送小说正文或用户参考音频。第三方网站、GitHub 和 Microsoft Store 的数据处理适用各自的隐私政策。

### 4. 保存、安全与删除

设置、画布和阅读记录保存在本机用户数据目录；模型保存在用户选择的目录，音频缓存位置可在听书设置中查看。EXE 版与商店版的具体位置可能不同。

这些数据一般保留至用户删除或系统清理。GGB 使用操作系统的访问控制，本地设置和缓存未额外加密。用户可以清空临时／预加载缓存、删除模型、关闭启动检查更新及自动启动。需要完整清除时，请退出软件后删除对应的用户数据、模型和缓存目录；这会清除保存的进度与设置。

卸载不一定删除所有个人文件、模型、备份或缓存，具体取决于安装方式和 Windows 行为。

### 5. 用户主动提交的信息

如用户通过 GitHub Issues 提交问题，开发者会使用其主动提供的说明、截图或日志处理反馈。公开 Issue 可被其他人查看，请勿提交密码、私人小说全文、个人参考音频或其他敏感内容。需要处理已提交的信息时，可通过同一渠道联系开发者；GitHub 平台上的删除与保留也受其规则约束。

### 6. 政策更新与联系

数据处理方式变化时，本政策会更新并标注日期。GGB 不专门面向儿童，也不主动向儿童收集个人信息。

隐私问题请通过[项目 GitHub Issues](https://github.com/suchengxing/AE-WindowSnap/issues)联系开发者。

---

## English

This policy applies to the Windows desktop and Microsoft Store editions of GoodGoodBox, also known as Good Good Box or GGB.

### 1. General principles

GGB primarily runs locally and does not require a GGB account. It includes no advertising or behavioral analytics service and does not automatically send usage statistics, crash reports or user files to the developer. The developer does not collect or sell your novels, images, voice references or generated narration through GGB.

### 2. Local data and its purposes

- **Window docking:** GGB reads window titles, executable paths, process and window identifiers, window positions and monitor information, and detects pointer positions and shortcut keys to identify, dock, reveal and restore panels. Necessary panel records and settings are saved locally.
- **Reference canvases:** GGB processes imported images, their positions and scaling, and canvas settings. Saving a canvas may save image copies and layouts.
- **Reading and narration:** GGB reads TXT files you open and saves file paths, file hashes, book titles, chapters, reading/listening positions, voice choices and playback settings. Speech synthesis runs on your computer without an online synthesis API. Local narration does not upload your novel text or voice references.
- **Caches and diagnostics:** Generated audio, chapter caches and necessary operational records are stored locally. Diagnostic records may contain file paths, window titles or error details; they are not automatically submitted to the developer.

Window and shortcut features are not used to record text typed into other applications or to continuously record your screen or microphone.

### 3. Network connections and third parties

The following features may connect to the internet:

- The EXE edition contacts GitHub to check for updates, automatically at startup if that option is enabled. The Store edition uses Microsoft Store for updates.
- Downloading or repairing the speech module contacts model, runtime and dependency providers, such as GitHub, ModelScope, Python.org, PyPI and PyTorch download services.
- Opening websites or videos uses WebView2 to access your chosen websites. Websites may use cookies, retain login sessions or collect browsing information. Their operators and the WebView2 service provider handle that information under their own policies.

These services may receive your IP address, request time, requested resources and client information. GGB does not attach novel text or your voice references to model download requests. Third-party websites, GitHub and Microsoft Store have their own privacy policies.

### 4. Storage, security and deletion

Settings, canvases and reading records are stored in local user-data folders. Models are stored in your selected folder; audio cache locations are shown in the narration settings. Locations may differ between the EXE and Store editions.

Data generally remains until you delete it or the operating system removes it. GGB relies on operating-system access controls and does not additionally encrypt local settings or caches. You can clear temporary and chapter caches, delete models, and disable startup update checks and automatic startup. To remove all saved data, exit GGB and delete the relevant user-data, model and cache folders; this also removes saved progress and settings.

Uninstalling may leave personal files, models, backups or caches, depending on the installation method and Windows behavior.

### 5. Information you submit

If you report an issue through GitHub Issues, the developer uses the descriptions, screenshots or logs you voluntarily provide to address it. Public issues are visible to others. Do not submit passwords, complete private novels, personal voice recordings or other sensitive material. Contact the developer through the same channel concerning information you submitted. Retention and deletion on GitHub are also subject to GitHub's rules.

### 6. Changes and contact

This policy will be updated, with a revised date, when data practices change. GGB is not specifically directed at children and does not actively collect personal information from children.

For privacy questions, contact the developer through the [project's GitHub Issues](https://github.com/suchengxing/AE-WindowSnap/issues).

---

## 日本語

本ポリシーは、GoodGoodBox（Good Good Box、以下「GGB」）の Windows デスクトップ版および Microsoft Store 版に適用されます。

### 1. 基本方針

GGB は主に端末上で動作し、GGB アカウントの登録は必要ありません。広告や行動分析サービスは組み込まれておらず、利用統計、エラー報告、ユーザーファイルを開発者へ自動送信しません。開発者は、GGB を通じて小説、画像、参照音声、生成された読み上げ音声を収集・販売しません。

### 2. 端末上で処理する情報と目的

- **ウィンドウ収納：**ウィンドウ名、実行ファイルのパス、プロセス・ウィンドウ識別子、位置、モニター情報を読み取り、マウス位置やショートカットキーを検出します。パネルの識別、画面端への収納、表示、復元に使用し、必要な設定と記録を保存します。
- **参考キャンバス：**取り込んだ画像、配置、拡大率、キャンバス設定を処理します。キャンバスを保存すると、画像のコピーや配置が保存される場合があります。
- **電子書籍・読み上げ：**ユーザーが開いた TXT ファイルを読み取り、パス、ファイルのハッシュ、書名、章、読書・再生位置、音声と再生設定を保存します。音声合成は端末上で行い、オンライン音声合成 API は使用しません。ローカル読み上げによって小説本文や参照音声をアップロードすることはありません。
- **キャッシュ・診断：**生成音声、章のキャッシュ、必要な動作記録を端末上に保存します。診断記録にはパス、ウィンドウ名、エラー情報が含まれる場合がありますが、開発者へ自動送信しません。

ウィンドウ・ショートカット機能を、他のアプリに入力した文章の記録や、画面・マイクの継続的な録音・録画には使用しません。

### 3. 通信と外部サービス

次の機能ではインターネット通信が発生する場合があります。

- EXE 版の更新確認は GitHub に接続します。起動時の更新確認を有効にすると、自動的に接続します。Store 版の更新は Microsoft Store が管理します。
- 読み上げモジュールのダウンロード・修復は、GitHub、ModelScope、Python.org、PyPI、PyTorch などのモデル・実行環境・依存ライブラリの提供元に接続します。
- Web ページ・動画の表示は、WebView2 を通じて選択したサイトに接続します。サイトが Cookie、ログイン状態、閲覧情報を扱う場合があり、サイト運営者および WebView2 の提供元のポリシーが適用されます。

接続先は IP アドレス、リクエスト時刻、要求したリソース、クライアント情報を受け取る場合があります。GGB はモデルのダウンロード要求に小説本文やユーザーの参照音声を添付しません。外部サイト、GitHub、Microsoft Store の情報処理には、それぞれのプライバシーポリシーが適用されます。

### 4. 保存・安全性・削除

設定、キャンバス、読書記録は端末上のユーザーデータフォルダーに保存します。モデルは選択したフォルダーに保存し、音声キャッシュの場所は読み上げ設定で確認できます。EXE 版と Store 版では保存場所が異なる場合があります。

通常、データはユーザーが削除するか、OS が削除するまで保存されます。GGB は OS のアクセス制御を使用し、設定やキャッシュを独自に暗号化しません。一時・章キャッシュの消去、モデルの削除、起動時の更新確認と自動起動の無効化が可能です。すべての保存データを削除する場合は GGB を終了し、該当するユーザーデータ、モデル、キャッシュのフォルダーを削除してください。保存した進捗と設定も失われます。

アンインストール後も、個人ファイル、モデル、バックアップ、キャッシュが残る場合があります。動作はインストール方法と Windows によって異なります。

### 5. ユーザーが提供する情報

GitHub Issues に問題を報告した場合、開発者は対応のため、ユーザーが提供した説明、画像、ログを利用します。公開 Issue は他の人も閲覧できます。パスワード、非公開の小説全文、個人の参照音声など、機密情報を投稿しないでください。提供済みの情報については、同じ窓口から開発者へご連絡ください。GitHub 上の保存・削除には GitHub の規則も適用されます。

### 6. 改定・お問い合わせ

情報の扱いが変わる場合、本ポリシーを改定し、更新日を記載します。GGB は子どもを主な対象としておらず、子どもから個人情報を積極的に収集しません。

プライバシーに関するお問い合わせは、[プロジェクトの GitHub Issues](https://github.com/suchengxing/AE-WindowSnap/issues)から開発者へご連絡ください。
