# 更新日志

本项目使用此文件按照时间倒序记录每一个 Commit 的更新内容，以避免分割 Commit。

## Commit v2025-11-07

### 视觉改进

- 更新字体设置。
  - 英文主字体由 EB Garamond 改为 Cormorant Garamond。
  - 无衬线字体由 Sarasa Gothic SC 改为 Noto Sans CJK SC。
  - 衬线字体由 Source Han Serif SC 改为 Noto Serif CJK SC。

## Commit v2025-10-22

### 功能改进

- 配置 `.latexmkrc` 以在编译成功后自动清理临时文件。

### 视觉改进

- 更新字体设置。
  - 英文无衬线字体使用 Noto Sans CJK SC，其英文部分使用 Inter 为基底。
  - 英文等宽字体增加后备 Cormorant Garamond，考虑到字符覆盖这一设置可能没有实际意义。

## Commit v2025-07-04a

### 视觉改进

- 修改了字体设置，取消中文优先使用英文字体；显著变化体现在全角引号现在会使用中文字体的引号。

## Commit v2025-07-04

### 功能改进

- 增加字体下载链接。

## Commit v2025-07-02

### 视觉改进

- 修改字体设置以确保商用免费：将“PingFang”改为“方正黑体”，“SF Pro Display”改为“Open Sans”，“SF Mono”改为“Maple Mono”。

## Commit v2025-06-03

### 功能改进

- 调整了段落间距。

## Commit v2025-05-28

### 功能改进

- 伪代码改用 `algorithm` `algorithmicx` 和 `algpseudocode`。

### 视觉改进

- 伪代码标题不再使用中文 `算法`。

## Commit v2025-05-27b

### 视觉改进

- 调整了标题的顶部空白。

## Commit v2025-05-27a

### 问题修复

- 修复英文字号不会随中文字号一起设置的问题。
- 为修复上述问题，标题的字号由 28pt 改为一号（26pt）；副标题的字号由 LARGE（17.28pt）改为小二（18pt）；学生信息的字号由 20pt 改为小二号（18pt）。
- 为适应上述修改，学生信息的行距由 2 改为 1.5。

## Commit v2025-05-27

### 功能改进

- 在 `.latexmkrc` 中设置 `clean_ext` 以在编译后自动清理临时文件。

## Commit v2025-05-23

### 功能改进

- 新增 `\simpletitle` 命令，用于生成简洁的不分页标题。

## Commit v2025-05-20a

### 问题修复

- 修复了 `README.md` 中的几处错误。

## Commit v2025-05-20

### 项目结构

- 新增 `.gitignore` 和 `.latexmkrc` 文件。
- 将字体设置移动至 `RucTextFont.sty` 宏包。
- 重命名 `ructhesis.sty` 为 `RucTextStyle.sty`，宏包名相应修改。
- 重新组织素材文件，主题素材存放至 `RucTextAssets` 文件夹，删除了 `figs`。
- 使用 `CHANGELOG.md` 记录 Commit 更新内容。
- 移除自定义 `gbt7714-numerical.bst` 样式，使用 `gbt7714` 宏包提供的样式。

### 功能改进

- 移除论文编号。
- 移除标题页“分数”项。
- 调整了若干文本。
- 移除原创声明，图表目录和致谢。
- 移除手动字体，以确保后备字体设置生效：如需使用黑体，请使用 `\textbf{}` 或 `\bfseries`；如需使用楷体，请使用 `\textit{}` 或 `\itshape`；如需使用宋体，请使用 `\normalfont`。
- 略微修改了 `main.tex` 中的若干文本。

### 视觉改进

- 使用上标参考文献编号。
- 更新字体设置，新的字体设置为：
  - 英文主字体：Cormorant Garamond, FZShuSong-Z01, Noto Serif CJK SC, Symbols Nerd Font
  - 英文无衬线字体：SF Pro Display, PingFang SC, PingFang TC, Noto Sans CJK SC, Symbols Nerd Font
  - 英文等宽字体：SF Mono, PingFang SC, PingFang TC, Noto Sans CJK SC, Symbols Nerd Font Mono
  - 英文数学字体：STIX Two Math, FZShuSong-Z01, Noto Serif CJK SC, Symbols Nerd Font
  - 中文主字体：Cormorant Garamond, FZShuSong-Z01, Noto Serif CJK SC, Symbols Nerd Font
  - 中文粗体主字体：Cormorant Garamond, PingFang SC, PingFang TC, Noto Sans CJK SC, Symbols Nerd Font
  - 中文斜体主字体：Cormorant Garamond, FZKai-Z03, Noto Serif CJK SC, Symbols Nerd Font
  - 中文无衬线字体：SF Pro Display, PingFang SC, PingFang TC, Noto Sans CJK SC, Symbols Nerd Font
  - 中文等宽字体：SF Mono, PingFang SC, PingFang TC, Noto Sans CJK SC, Symbols Nerd Font Mono
- 使用 `tex-fmt` 重新格式化文件。
