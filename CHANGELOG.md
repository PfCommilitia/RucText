# 更新日志

本项目使用此文件按照时间倒序记录每一个 Commit 的更新内容，以避免分割 Commit。

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
  - 英文主字体：EB Garamond, FZShuSong-Z01, Source Han Serif SC, Symbols Nerd Font
  - 英文无衬线字体：SF Pro Display, PingFang SC, PingFang TC, Sarasa Gothic SC, Symbols Nerd Font
  - 英文等宽字体：SF Mono, PingFang SC, PingFang TC, Sarasa Gothic SC, Symbols Nerd Font Mono
  - 英文数学字体：STIX Two Math, FZShuSong-Z01, Source Han Serif SC, Symbols Nerd Font
  - 中文主字体：EB Garamond, FZShuSong-Z01, Source Han Serif SC, Symbols Nerd Font
  - 中文粗体主字体：EB Garamond, PingFang SC, PingFang TC, Sarasa Gothic SC, Symbols Nerd Font
  - 中文斜体主字体：EB Garamond, FZKai-Z03, Source Han Serif SC, Symbols Nerd Font
  - 中文无衬线字体：SF Pro Display, PingFang SC, PingFang TC, Sarasa Gothic SC, Symbols Nerd Font
  - 中文等宽字体：SF Mono, PingFang SC, PingFang TC, Sarasa Gothic SC, Symbols Nerd Font Mono
- 使用 `tex-fmt` 重新格式化文件。
