# 自定义_Windows (VS Code Personal Icon Theme)

> 🪟 **专为 Windows 习惯与新手打造的 Visual Studio Code / Antigravity IDE 原生风格文件图标主题**

![自定义_Windows 图标总览](./images/preview.png)

---

## 📖 项目简介 (Introduction)

**“自定义_Windows”** 是一款为 Visual Studio Code 以及 Antigravity IDE 量身打造的文件与文件夹图标主题插件。

在日常开发与办公中，面对众多第三方图标主题过于抽象、扁平或单色的视觉呈现，很多开发者与初学者容易产生视觉疲劳与认知负担。本项目致力于还原广大用户最熟悉、最符合直觉的 **Windows 经典立体视觉风格** 与 **常用软件原生标志**，让项目资源管理器的文件层级分明、状态一目了然，使编辑器更加美观、亲切、高效。

---

## ⚖️ 声明与版权说明 (Disclaimer & Rights)

> [!NOTE]
> **重要声明**：
> 1. 本项目主要将 Windows 原生系统、Microsoft Office 系列办公软件及常用开发工具的经典视觉资产进行了**收集、矢量提取、SVG 格式适配、规范化命名与配置整合**。
> 2. 本项目**不享有**任何 Windows 原生图标、Microsoft 品牌及第三方工具图标的原创发明权或商标专有权，所有相关视觉资产的知识产权与版权均归原作者及所属公司所有。
> 3. 本项目遵循开源分享原则，仅享有**汇总整理、格式适配、中转分发与开源配置维护权**，旨在为开发者社区提供更加顺手美观的本地开发环境体验。

---

## ✨ 核心特性 (Features)

* 📂 **Windows 原生立体文件夹**：
  * 精准还原 Windows 资源管理器经典黄色立体文件夹质感。
  * 完美支持折叠（Closed）与展开（Open）两种状态。
  * 支持根目录（Root Folder）专属标识。
* 📑 **Office 原生全家桶**：
  * **Word**：`.docx`, `.doc`, `.wps`, `.dot`, `.dotx`, `.dotm` 等。
  * **Excel**：`.xlsx`, `.xls`, `.csv`, `.tsv`, `.xlsm`, `.xlsb`, `.et` 等。
  * **PowerPoint**：`.pptx`, `.ppt`, `.pps`, `.ppsx`, `.dps` 等。
  * **PDF**：`.pdf` 经典红白标识。
* 🐍 **Python 经典标志**：
  * 采用经典纯净的蓝黄双蛇 Logo（透明矢量背景，`.py`, `.pyw`, `.ipynb`, `.pyi`），告别模糊与单调。
* 📘 **Antigravity 专属 Markdown**：
  * 采用清新醒目的亮蓝色透明底 `M↓` 标志（`.md`, `.markdown`, `.mdx` 等）。
* ⚡ **工控与西门子 SCL 深度适配**：
  * 支持西门子 TIA Portal / 结构化文本文件（`.scl`, `.st`, `.s7dcl`, `.awl`, `.udt`, `.db` 等）。
* 💻 **主流编程语言与配置文件**：
  * C / C++（`.c`, `.cpp`, `.h`, `.hpp`）
  * Java（`.java`）
  * HTML / CSS / SCSS / LESS（`.html`, `.css`, `.scss` 等）
  * JavaScript / TypeScript（`.js`, `.ts`, `.jsx`, `.tsx`）
  * JSON / XML / YAML（`.json`, `.xml`）
  * Git 配置（`.gitignore`, `.gitattributes`, `.gitmodules`）
* 🖼️ **系统级多媒体与归档文件**：
  * 图像文件：`.png`, `.jpg`, `.jpeg`, `.gif`, `.svg`, `.bmp`, `.webp`, `.ico`
  * 纯文本与日志：`.txt`, `.log`, `.ini`, `.cfg`, `.conf`
  * 压缩归档包：`.zip`, `.rar`, `.7z`, `.tar`, `.gz`, `.jar`

---

## 🚀 安装与使用指南 (Installation & Usage)

### 方式一：直接复制安装（推荐）

1. 克隆或下载本项目源码。
2. 将本插件文件夹重命名为 `custom-windows-icons`，并复制到本地 VS Code 的扩展目录中：
   * **Windows 路径**：
     ```plaintext
     %USERPROFILE%\.vscode\extensions\custom-windows-icons
     ```
     *(通常位于 `C:\Users\<你的用户名>\.vscode\extensions\custom-windows-icons`)*
3. 重启或打开 Visual Studio Code。

### 方式二：Git 仓库安装

在命令行中直接克隆至扩展目录：

```bash
git clone https://github.com/Yclor9828/Vs_Theme_Personal.git "%USERPROFILE%\.vscode\extensions\custom-windows-icons"
```

---

### 激活图标主题 (Activation)

1. 打开 VS Code，按下快捷键 <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> 打开命令面板。
2. 输入并选择 **`Preferences: File Icon Theme`**（首选项: 文件图标主题）。
3. 在下拉列表中选择 **`自定义_Windows`** 即可立即生效！

---

## 📁 项目结构 (Project Structure)

```plaintext
Vs_Theme_Personal/
├── icons/                  # 矢量 SVG 图标资源库
│   ├── icon-theme.json     # VS Code 图标映射定义与规则
│   ├── folder.svg          # 经典文件夹（闭合态）
│   ├── folder_open.svg     # 经典文件夹（展开态）
│   ├── python_classic.svg  # 经典 Python 蓝黄双蛇矢量
│   ├── markdown.svg        # 专属透明底 M↓ 标志
│   ├── scl.svg             # 西门子 SCL 标识
│   ├── word_fluent.svg     # Word 办公图标
│   ├── excel_fluent.svg    # Excel 办公图标
│   ├── powerpoint_fluent.svg # PPT 办公图标
│   └── ...                 # 其它语言与多媒体 SVG
├── images/                 # 预览图与截图资源
│   └── preview.png         # 主题效果预览总览
├── package.json            # 扩展清单与配置元数据
├── README.md               # 项目使用与说明文档
└── .gitignore              # Git 忽略配置
```

---

## 🤝 贡献与反馈 (Contribution)

如果您在日常使用中发现了尚未适配的文件后缀，或者希望补充更多符合 Windows 原生风格的精致图标，非常欢迎提交 Issue 或 Pull Request！