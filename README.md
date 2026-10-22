# XR Physiology Informed Agents — Overleaf project

## 上传 Overleaf
1. 在 Overleaf 选择 New Project → Upload Project。
2. 上传整个 XR_Physiology_IMWUT_Overleaf.zip，Overleaf 会自动解压。
3. Main document 选 main.tex；Compiler 选 pdfLaTeX。使用可用的最新 TeX Live。
4. 点击 Recompile。文献使用 BibTeX 和 ACM-Reference-Format，数字引文与 DOI/URL 自动链接。

## 正文与待补内容
- sections/ 按文章章节拆分，可分别修改。
- references.bib 包含 63 个真实来源条目；正式论文、录用作者版本及 arXiv 预印本作了区分。
- 红色内容由 \missing{...} 标记；系统图、实验数据和结果仍待补充。未编造结果。
- notes/literature_and_evidence.md 是十篇论文的写作分析与证据边界笔记，不会出现在正文 PDF。

## 两种排版模式
main.tex 中的 \reviewversionfalse 是默认的正式 IMWUT acmlarge 单栏文章预览。它没有虚构 DOI、卷期、文章号或录用日期。
改成 \reviewversiontrue 则切换到 ACM manuscript,review,anonymous 单栏审稿模式，并加入行号。
这是可编辑研究草稿；红色空缺补齐后，需按实际投稿时 IMWUT 的最新要求核对匿名、页数、CCS、披露和元数据。
不要将主技术论文改成 sigconf 双栏；2026 会议官网的双栏规则明确排除了 IMWUT Papers。

## 模板来源
- UbiComp 2026 主技术论文路线：https://ubicomp.hosting.acm.org/ubicompiswc2026_wp/imwut-papers/
- UbiComp 2026 其他 track 格式及 IMWUT 例外：https://ubicomp.org/ubicomp-iswc-2026/formatting/
- ACM 官方 Overleaf journal 模板：https://www.overleaf.com/latex/templates/association-for-computing-machinery-acm-generic-journal-manuscript-template/yffvrvzbhhpt
- ACM 生产版 acmart 2.20，2026-08-16：https://ctan.org/pkg/acmart

acmart.cls 从该生产发行版的 class 选项生成；ACM-Reference-Format.bst 来自同一发行版。原始 DTX/INS 和许可说明保存在 template_sources/。未修改模板字号、边距或行距。

## 本地编译
如已安装 LaTeX，可以使用 latexmk -pdf main.tex，或依次运行 pdflatex main、bibtex main、pdflatex main、pdflatex main。
