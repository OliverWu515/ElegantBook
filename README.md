<!-- Author : Dongsheng Deng & Liam Huang-->
<!-- Program Email: elegantlatex2e@gmail.com -->

[Homepage](https://elegantlatex.org/) | [Github](https://github.com/ElegantLaTeX/ElegantBook) | [CTAN](https://ctan.org/pkg/elegantbook) | [Download](https://github.com/ElegantLaTeX/ElegantBook/releases) | 

![License](https://img.shields.io/ctan/l/elegantbook.svg) ![CTAN Version](https://img.shields.io/ctan/v/elegantbook.svg) ![Github Version](https://img.shields.io/github/release/ElegantLaTeX/ElegantBook.svg) ![Repo Size](https://img.shields.io/github/repo-size/ElegantLaTeX/ElegantBook.svg)

-------

该模板基于 [ElegantBook-4.5](https://github.com/ElegantLaTeX/ElegantBook) 修改而来，用于[《线性代数应该这样学》（第四版）中文译本](https://github.com/OliverWu515/LADR4e-PDF) 的排版。

This template is adapted from [ElegantBook-4.5](https://github.com/ElegantLaTeX/ElegantBook) and is used for typesetting the [Chinese translation of *Linear Algebra Done Right* (4th edition)](https://github.com/OliverWu515/LADR4e-PDF).

其中主要的修改在 `ElegantBook.cls` 中使用注释 `% NEW:` 进行了标记，主要包括：

The main changes are marked with `%NEW:` comments in `ElegantBook.cls`, mainly including:

- 适配 *Linear Algebra Done Right* (4th edition) 原书（下称 LADR4e）不区分定理、引理和命题的写作习惯，统一使用 `theorem` 环境进行排版。
- 适配 LADR4e 原书的示例（`example`）、章首图片（`artworkfigure`）和边注框（`commentbox`）等。
- 样式调整：包括目录、页眉、页脚、图题、表题和页码等。
- 新增样式：添加了 `tcolorbox` 中的“转下页”标记等。
- 修复了原模板的一些 bug。

- To match the writing convention in LADR4e (where theorems, lemmas, and propositions are not distinguished), everything is typeset using a unified `theorem` environment.
- Adaptations for LADR4e-specific elements such as examples (`example`), chapter-opening artwork (`artworkfigure`), and margin note boxes (`commentbox`).
- Style adjustments, including the table of contents, headers, footers, figure/table captions, and page numbers.
- New styles, such as a “continued on next page” marker for `tcolorbox`.
- Fixes for some bugs in the original template.

以下为原模板信息。

Below is the original template information.

# ElegantBook: 优美的 LaTeX 书籍模板 An Elegant LaTeX Template for Books 

ElegantBook 是为 LaTeX 书籍写作而设计的模板，由 [Ethan Deng](https://github.com/EthanDeng) 和 [Liam Huang](https://github.com/Liam0205) 创立，现在主要由 [Ethan Deng](https://github.com/EthanDeng)、[乙醇](https://github.com/syvshc)和[死抠](https://github.com/sikouhjw)维护。如果你有其他问题、建议或者报告 bug，可以提交 issues 或者加入我们的 QQ 用户交流群：692108391。

ElegantBook is designed for writing books, created by [Ethan Deng](https://github.com/EthanDeng) and [Liam Huang](https://github.com/Liam0205), and maintained by [Ethan Deng](https://github.com/EthanDeng), [syvshc](https://github.com/syvshc) and [sikouhjw](https://github.com/sikouhjw). Just enjoy it! If you have any questions, suggestions or bug reports, you can create issues or contact us at elegantlatex2e@gmail.com.


**本模板自 2023 年 1 月 1 日开始，不再维护，不建议使用本系列模板！为了保证之前版本的用户仍然能查到说明文档，本说明文档仍然保留过去的信息。**

**Caution: This template will no longer be maintained since January 1st, 2023.**

## 致谢 Acknowledgement


特别感谢 [sikouhjw](https://github.com/sikouhjw) 和 [syvshc](https://github.com/syvshc) 长期以来对于 Github 上 issue 的快速回应，以及各个社区论坛对于 ElegantLaTeX 相关问题的回复。特别感谢 ChinaTeX 以及 [LaTeX 工作室](http://www.latexstudio.net/)对于本系列模板的大力宣传与推广。

Thank [sikouhjw](https://github.com/sikouhjw) and [syvshc](https://github.com/syvshc) for their quick response to Github issues and continuously support work for ElegantLaTeX community. Thank ChinaTeX and [LaTeX Studio](http://www.latexstudio.net/) for their promotion. 


## 协议 License

本模板发布遵循 LaTeX 项目公共许可证 1.3 c 或更高版本。
如果是衍生作品，请务必加入协议声明和模板信息（github、CTAN 地址）。

This work is released under the LaTeX Project Public License, v1.3c or later.


## 衍生品 Derivative Works

+ [ElegantBookdown](https://github.com/XiangyunHuang/ElegantBookdown)：[XiangyunHuang](https://github.com/XiangyunHuang) 开发并维护的基于 ElegantBook 的 Bookdown 模板。
+ [bookdownplus](https://github.com/pzhaonet/bookdownplus)：应网友要求，[pzhaonet](https://github.com/pzhaonet) 在 bookdownplus 收录了 ElegantPaper 模板，并为 Mac 做了字体适配。
+ [PanBook](https://github.com/annProg/PanBook)：[annProg](https://github.com/annProg) 开发并维护的基于 Markdown 写作的工作流，收录了 ElegantBook 和 ElegantPaper 模板。
