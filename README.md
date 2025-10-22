# RucText

自用中国人民大学 LaTeX 文本模板。
本模板不适合用于毕业论文，可用于课程论文，或删除若干项目后用于课程作业。

## 项目结构

```
RucText/
├── RucTextAssets/
│   ├── head.png
│   └── title.jpg
├── .gitignore
├── .latexmkrc
├── CHANGELOG.md
├── LICENSE
├── main.tex
├── README.md
├── references.bib
├── RucTextFont.sty
└── RucTextStyle.sty
```

其中，`main.tex` 和 `references.bib` 为范例文件。

## 注意事项

- 不要将要使用的 PDF 素材放到项目根目录，根目录下的所有 PDF 文件都将视为编译后文件，并被 Git 忽略。
- 使用的所有字体包括 EB Garamond、FZShuSong-Z01（方正书宋 GBK）、Source Han Serif SC（思源宋体）、Symbols Nerd Font、Open Sans、FZHei-B01（方正黑体 GBK）、Sarasa Gothic SC（更莎黑体）、Maple Mono、STIX Two Math、FZKai-Z03（方正楷体 GBK）。所有字体的许可证均允许免费商用，可以在[此处](https://www.dropbox.com/scl/fo/muhm4rddf4tlytqdph189/AEwl6rNMu6HShBzQTIyFTqI?rlkey=4lhpvzfiiclh5sakodie3dz7l&st=yq04y59k&dl=0)下载，字体一切权利归原作者所有。

## 更新日志

Commit 信息仅记录版本代号，具体更新内容参见 [CHANGELOG.md](CHANGELOG.md)。

## 版权与许可

该模板 fork 自 [liuqi6777 的 ructhesis](https://github.com/liuqi6777/ructhesis)。

本模板使用与原模板相同的 [MIT](LICENSE) 许可证。
