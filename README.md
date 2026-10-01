# AE-WindowSnap-English-
一款专为 After Effects 设计的窗口管理工具，可快速收纳与呼出浮动脚本窗口，释放工作区空间。支持简体中文、English、日本語。
A window management tool designed for After Effects. Quickly hide and recall floating script panels to free up workspace. Supports Simplified Chinese, English, and Japanese.
After Effects向けに設計されたウィンドウ管理ツールです。フローティングスクリプトパネルをすばやく収納・呼び出しでき、作業スペースをより広く快適に使えます。簡体字中国語・英語・日本語に対応しています。
# 收纳盒 Good Good Box（GGB）

**让 AE 浮动面板有处可放，让创作空间更从容。**  
**Keep your AE panels within reach and your workspace clear.**  
**AE のフローティングパネルをすっきり収納し、快適な制作環境へ。**

当前版本 / Current version / 現在のバージョン：**V1.1.0**  
平台 / Platform / 対応 OS：**Windows**  
作者 / Creator / 作者：**@苏承欣**

---

简体中文
收纳盒 Good Good Box（简称 GGB）是一款面向 Adobe After Effects 的 Windows 浮动窗口管理工具。它可以将脚本和插件的独立浮动面板收至屏幕边缘，仅保留指定宽度，需要时通过鼠标或快捷键展开，减少面板对预览区和时间线的遮挡。

### 主要功能

- **四方向贴边收纳**：支持左、右、上、下四个方向，可自定义边缘保留像素。
- **鼠标自动展开与收回**：鼠标靠近时展开，离开后收回，两种等待时间均可设置。
- **全局快捷键**：自定义隐藏与恢复组合键，支持录制快捷键及部分符号按键。
- **滑动动画**：可开启或关闭动画，调整动画时长与目标帧率。
- **紧急恢复**：通过“恢复全部”或 `Ctrl + Alt + F12`，将受控窗口恢复到屏幕中间。
- **系统托盘**：支持隐藏到托盘，通过托盘菜单打开软件、控制面板或退出并恢复窗口。
- **开机启动**：可在工具页设置随 Windows 启动。
- **AE 渲染后操作**：配合 AE 渲染助手脚本，在全部监测任务成功完成后，可执行关机、睡眠或退出 AE；支持 30 秒、1 分钟、5 分钟延迟及倒计时取消。
- **外观与语言**：支持浅色、深色外观和自定义主题色；内置简体中文、繁體中文、日本語、English。
- **学习页面**：提供四卷 PDF 阅读入口、对应有声内容链接，以及带悬停和点击反馈的插画入口。

### V1.1.0 新增

- **面板记忆**：新增“记住此面板”和“取消记忆”。保存选定面板的识别信息、贴边方向及保留像素；AE 重开后，当同一面板重新出现时，自动识别并贴边。
- **30–240 FPS 动画设置**：支持自定义动画目标帧率，默认 120 FPS；高刷新率显示器用户可设置为 240 FPS。
- **高精度动画计时**：动画刷新与鼠标检测分开处理，高精度计时仅在面板滑动期间运行。

### 使用说明

1. 在 AE 中打开一个独立浮动面板。
2. 在 GGB 中通过窗口列表或鼠标选取该面板。
3. 设置贴边方向、保留像素和鼠标展开等待时间。
4. 点击“隐藏 / 恢复”开始使用；需要自动重新识别时，点击“记住此面板”。

面板记忆需要保持 GGB 运行，不会替 AE 打开尚未打开的脚本面板。目前支持记忆一个面板；出现多个匹配窗口时不会自动选择。执行“恢复全部”后，本次自动贴边会暂停，可重新点击“记住此面板”启用。

不同 AE 版本和插件面板的窗口行为可能不同，建议先使用“验证移动”。动画设置为目标帧率，实际流畅度取决于显示器、系统负载及目标面板的响应速度。

---

## English

### About

Good Good Box (GGB) is a Windows utility for managing floating script and plug-in panels in Adobe After Effects. It moves standalone panels to a screen edge, leaving a configurable strip visible. Bring them back with your mouse or a global shortcut to keep your composition viewer and timeline clear.

### Features

- **Dock to any edge:** Choose left, right, top or bottom, with an adjustable visible strip.
- **Reveal and retract on hover:** Set separate delays for revealing and retracting panels.
- **Global shortcuts:** Customize and record shortcuts for hiding and restoring panels, including supported punctuation keys.
- **Slide animations:** Enable or disable animations and adjust their duration and target frame rate.
- **Emergency restore:** Use Restore All or `Ctrl + Alt + F12` to bring controlled windows back to the center of the screen.
- **System tray:** Keep GGB in the tray and access window controls, restore actions and safe exit.
- **Launch at startup:** Optionally start GGB with Windows.
- **After-render actions:** With the AE render helper script, shut down, sleep or quit AE after all monitored tasks finish successfully. Choose a 30-second, 1-minute or 5-minute delay, with a cancellable countdown.
- **Appearance and languages:** Light and dark themes, custom accent colors, and Simplified Chinese, Traditional Chinese, Japanese and English interfaces.
- **Learning library:** Access four PDF volumes, their audio-content links and an interactive illustration with hover and click feedback.

### New in V1.1.0

- **Remember a panel:** Save the selected panel’s identity, docking edge and visible-strip width. When AE restarts and the matching panel reappears, GGB can recognize and dock it automatically.
- **30–240 FPS animation settings:** Choose a target frame rate, with 120 FPS as the default and up to 240 FPS for high-refresh-rate displays.
- **High-resolution animation timing:** Animation updates run separately from hover detection, with high-resolution timing active only while a panel is moving.

### Getting Started

1. Open a standalone floating panel in AE.
2. Select it in GGB using the window list or mouse picker.
3. Set the docking edge, visible-strip width and hover delays.
4. Click Hide / Restore. To enable automatic recognition later, click Remember panel.

Keep GGB running for automatic docking. GGB does not open AE script panels for you. One remembered panel is currently supported; ambiguous matches are not docked automatically. Restore All pauses automatic docking for the current session. Click Remember panel again to re-enable it.

Compatibility varies between AE versions and plug-in panels. Try the movement check first. The FPS setting is a target; actual smoothness depends on your display, system load and the target panel’s responsiveness.

---

## 日本語

### 概要

Good Good Box（GGB）は、Adobe After Effects のスクリプトやプラグインのフローティングパネルを管理する Windows 用ツールです。独立したパネルを画面の端に収納し、指定した幅だけを表示します。マウスやグローバルショートカットで呼び出せるため、コンポジションビューやタイムラインを広く使えます。

### 主な機能

- **上下左右への収納**：収納する方向と、画面端に残すピクセル数を設定できます。
- **マウスによる自動展開・収納**：マウスを近づけたときと離したときの待ち時間を個別に設定できます。
- **グローバルショートカット**：非表示・復元のキー操作をカスタマイズできます。キー入力の記録と、一部の記号キーにも対応しています。
- **スライドアニメーション**：アニメーションの有効・無効、再生時間、目標フレームレートを設定できます。
- **緊急復元**：「すべて復元」または `Ctrl + Alt + F12` で、管理中のウィンドウを画面中央に戻せます。
- **システムトレイ**：トレイに常駐し、パネル操作や復元、ウィンドウを復元してからの終了ができます。
- **自動起動**：Windows 起動時に GGB を起動するよう設定できます。
- **レンダリング完了後の操作**：AE レンダリング補助スクリプトと連携し、監視対象の全タスクが正常に完了した後に、シャットダウン、スリープ、AE の終了を実行できます。待ち時間は 30 秒・1 分・5 分から選択でき、カウントダウン中にキャンセルできます。
- **外観と言語**：ライト・ダークテーマ、アクセントカラーの変更、簡体字中国語・繁体字中国語・日本語・英語に対応しています。
- **学習ページ**：全4巻の PDF、対応する音声コンテンツへのリンク、ホバー・クリック時に反応するイラストを利用できます。

### V1.1.0 の新機能

- **パネルの記憶**：選択したパネルの識別情報、収納方向、表示幅を保存できます。AE を再起動し、同じパネルが再び表示されると、自動で認識して収納します。
- **30～240 FPS の設定**：アニメーションの目標フレームレートを指定できます。標準は 120 FPS、高リフレッシュレートのディスプレイでは最大 240 FPS に設定できます。
- **高精度なアニメーション制御**：マウス検出とアニメーション更新を分離し、パネルが移動している間だけ高精度タイマーを使用します。

### 使い方

1. AE で独立したフローティングパネルを開きます。
2. GGB のウィンドウ一覧、またはマウス選択で対象を指定します。
3. 収納方向、表示幅、マウス操作の待ち時間を設定します。
4. 非表示・復元ボタンで操作します。次回も自動認識させる場合は「このパネルを記憶」をクリックします。

自動収納には GGB の起動が必要です。GGB が AE のスクリプトパネルを開くことはありません。現在、記憶できるパネルは1つです。一致するウィンドウが複数ある場合は自動選択しません。「すべて復元」を実行すると、そのセッションの自動収納は一時停止します。再開するには、もう一度「このパネルを記憶」をクリックしてください。

AE のバージョンやプラグインによって動作が異なる場合があります。最初に移動確認をお試しください。FPS は目標値であり、実際の滑らかさはディスプレイ、システム負荷、対象パネルの応答速度に左右されます。
