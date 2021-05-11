# NKU-biyelunwen-2021

目前版本：v1.2
### 使用方式
- 下载所有文件（Code --> Download Zip），使用本地编译器编译
- 使用 Overleaf 的模板：[NKU-毕业论文-2021](https://www.overleaf.com/latex/templates/nku-bi-ye-lun-wen-2021/svxybkzxyycp) 在线编程

### 注意事项
- 本模板在 TeX Live 2020 环境下可以运行，但不保证更低版本或其它环境下的运行。
- 若您在本地环境无法编译该模板，可以在 [Overleaf](https://www.overleaf.com/latex/templates/nku-bi-ye-lun-wen-2021/svxybkzxyycp) 上在线编程。
- 由于 Overleaf 的模板审核时间较长，若 GitHub 上的模板版本更加新，则推荐使用 GitHub 上的代码（将 GitHub 上的 main.tex 与 preamble.tex 替换 Overleaf 上的同名文件即可）

请下载并阅读《2021 南开大学本科毕业论文模板示例》文件，在摘要页有更详细的使用说明，在该文件中提供了更多示例。

### 对从 [NKU-thesis-template-2020](https://github.com/Tr0py/NKU-thesis-template-2020) 迁移过来的用户须知：
- 原模板基于 book 类制作，最高级标题为“章（Chapter）”。本模板基于 ctexart 类制作，最高级标题为“节（Section）”，因此你需要将所有标题都降一级。
- 原模板使用 biblatex 管理文献，需要使用 bib 文件，但提供了复杂的引用功能。本模板的文献管理使用起来较简单，但也只提供了引用序号（如 \[1\]）的功能。
- 原模板在 LaTeX 中制作封面，本模板需要你自己制作封面（cover1.pdf）。推荐使用本模板的 cover1.docx 文件制作封面，与教务处提供的反人类的[南开大学本科毕业论文（设计）相关表格](http://jwc.nankai.edu.cn/bylwwsjw/list.htm)相比，它使用表格重新制作了该封面，因此具有以下优点：
  - 你不再会因为输入文字而导致下划线加长，也不必担心下划线无法对其的问题。
  - 根据你的标题长度，你可以很轻松的增加一行标题，或减少一行标题。
  - 无论你使用 word，还是 LaTeX，都可以使用该文件制作封面。
- 如你的学院要求制作简历，你可以使用其它软件将其导出为 PDF，像插入封面那样将它插入论文中。
