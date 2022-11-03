# ebook-publication-research
> This repo is in incubator stage currently.

In-depth research on e-book publishing technology.

## tech research
- [typora-theme-essay_cn](https://github.com/du33169/typora-theme-essay_cn)

原理：typora + markdown + custom css template + pandoc 。 基于markdown的写作方案，配合typora编辑器，优点是学习成本极低，容易上手。

局限性：需要持续维护css 主题模版，很难完全覆盖latex的功能，例如：TOC无法标注渲染后的页码，图片标题和图注标号，交叉引用变量等等。

---

- [PanBook](https://github.com/annProg/PanBook)

PanBook基于Pandoc的lua filter功能，适配各种书籍，论文，幻灯片及简历的LaTeX或EPUB模板。 目标是使用Pandoc's Markdown作为写作语言，实现一次编写，多次生成。
 
原理：提前准备好对应领域的Latex或者EPUB模版，使用 Pandoc 将 markdown 和模版结合，导出渲染后的结果文档。

局限性：关键依旧在于模版的维护和更新。

---
