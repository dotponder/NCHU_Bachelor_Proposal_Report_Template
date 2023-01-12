# 南昌航空大学本科毕业设计开题报告 LaTeX 模版

本项目为非官方的南昌航空大学**本科生**毕业设计开题报告 LaTeX 模版。

本模版由南昌航空大学毕业论文 LaTeX 模版 [NCHUSC/NCHU_Bachelor_Thesis_Template](https://github.com/NCHUSC/NCHU_Bachelor_Thesis_Template) 修改而成，特此表示衷心的感谢！

## 样例展示

正文样例可以参照[PDF样例文档](main.pdf)

## 项目结构

```
NCHU_Bachelor_Proposal_Report_Template
├─ .gitignore
├─ fonts
│  ├─ simhei.ttf
│  ├─ simsun.ttc
│  └─ TimesNewRoman
│     ├─ times.ttf
│     ├─ timesbd.ttf
│     ├─ timesbi.ttf
│     └─ timesi.ttf
├─ images
│  ├─ header.png
│  └─ nchu_logo.png
├─ LICENSE
├─ main.pdf
├─ main.tex
├─ misc
│  ├─ 0_cover.tex
│  ├─ 1_instruction.tex
│  ├─ 2_reference.tex
│  ├─ 3_tutor_comments.tex
│  └─ ref.bib
├─ README.md
└─ sections
   ├─ 1_rationale_significance.tex
   ├─ 2_overview_trend.tex
   ├─ 3_research_content.tex
   └─ 4_objectives.tex
```

## 下载方式

Download ZIP 或者`git clone`。

## 使用方法

有两种方式进行编辑和编译：

* Overleaf 在线编译
* 本地编译

> 推荐使用 Overleaf 在线编译的方式。

### Overleaf 在线编译
**强烈建议大家使用**  

Overleaf 是一个十分方便的网页版在线 LaTeX 编辑器。如果是 Overleaf 会员用户的话，甚至可以与 Github 同步。

![](https://i.loli.net/2021/01/31/OMbfg7Pza3xdGlR.png)

1. 在本项目界面，选择 Download ZIP
2. 在 Overleaf 页面的 New Project，Upload Project，上传第 1 步下载的 zip 文件
3. 点击左上角的 Menu 按钮，设置 Compiler 类型为 XeLaTeX，然后点击 Recompiler，即可查看编译好的页面

### 本地编译

本地编译需要安装 TeX 发行版软件，例如 TeX Live、MacTeX 和 MikTeX，这些发行版都自带了基本的 LaTeX 编译工具。

**注意**：系统需要安装有宋体（SimSun）和黑体（SimHei）字体以及 Times New Roman 英文字体，并请**不要使用 CTeX**。如果未安装，可以手动安装 `fonts` 文件夹内的所有字体。

#### Windows

可以在系统中安装 TeX Live 或者 MikTeX。

#### Mac

可以在系统中安装 MacTeX 或者 MikTeX 或者是 TeXShop。

#### Linux

可以在系统中安装 TeX Live 或者 MikTeX。

#### 配置 VSCode + LaTeX Workshop

1. 在 VSCode 左侧的插件栏搜索 LaTeX Workshop 并安装

2. 下载或者克隆本模版，用 VSCode 打开项目文件夹

3. 点击打开`main.tex`文件，点击左下角的`√`的符号，选择第一项`Build LaTex Project`

4. 选择`Recipe: latexmk (xelatex)`

    即在 Tex Live 环境下，使用xekatexmk进行编译

5. 如果是使用 MikTeX，中途会提示安装宏包。等左下角再次显示`√`，再点击，选择第二项`View LaTeX PDF`，即可进行预览。

## 问题反馈

本模板仍在维护，如果在使用本模板遇到任何问题，可以[发邮件给我](arnoldchow@outlook.com)，或者在 [Issues](https://github.com/dotponder/NCHU_Bachelor_Proposal_Report_Template) 中留言，亦可前往我的[个人主页](https://dotponder.github.io/)。

## 后续计划

* ~~支持实验报告模版等~~
* **现在是3202年了，恁校还要手写实验报告，我已经不好说什么了。**
* ~~支持研究生论文模版等~~
* **都要毕业了，看到了想起来了就来更一下**
* 欢迎提交 Pull Request
