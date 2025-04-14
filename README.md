# CV-Template

A customized LaTeX resume template based on the [fky2015/resume-ng](https://github.com/fky2015/resume-ng) project, modified to fit personal needs.

## Overleaf 在线平台

直接访问[此链接](https://www.overleaf.com/read/ygxtzycvwyqm)即可。

> [!IMPORTANT]
> Overleaf使用时，需要手动设置XeLaTex编译: 左上角Menu -> Settings -> Compiler -> XeLaTex 

## 宏

常用用法可参考 `main.tex` 中的示例内容。

- `\ResumeName{}` 定义简历标题（一般是姓名）。
- `\ResumeContact{}` 添加一个联系方式。
- `\ResumeContacts{itemA, itemB, itemC}` 添加多个联系方式。
- `\ResumeTitle` 渲染标题和联系方式。
- `\section{}` 节标题。
- `\ResumeItem[]{}[][]`
  1. 可选参数，控制 PDF 书签内容。如果不提供则采用参数 2。
  2. 项标题，左对齐。
  3. 可选参数，补充信息，在参数 2 后显示。
  4. 可选参数，右对齐。
- `\GrayText{}` 改变文字内容为灰色。
- `\ResumeUrl{}{}` 带有下划线的 `\href` 命令，与 `\href` 用法相同。

> `[]` 为可选参数， `{}` 为必需参数。

## 包依赖

**如果你使用 TeXLive/MiKTeX 等主流发行版，可以直接使用本项目，无需手动安装依赖。**

否则，请确保以下依赖安装。

- geometry
- fancyhdr
- fontawesome5
- enumitem
- footmisc
- hyperref
- xeCJKfntef
- xcolor
- ctex

## 致谢

该项目主要受到 [fky2015/resume-ng](https://github.com/fky2015/resume-ng) 的启发，
