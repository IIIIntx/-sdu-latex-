# 山东大学本科毕业论文模板

本论文模板在 CTeX 2.9.2 环境下编译通过。在编写论文的过程中对于本科论文需要的部分进行了大量修改和查找，受益于[Delbert](https://github.com/cnDelbert)同学的模板帮助，我也希望能将自己整理的结果简单进行发表以供其他人使用。

由于时间和能力所限，很多地方都参照[Delbert](https://github.com/cnDelbert)同学的模板内容，对[Delbert](https://github.com/cnDelbert)同学再次表达感谢。

开源精神希望一直延续下去。

## 模板参照

- [关于印发《山东大学学位论文规范（试行）》的通知](http://www.grad.sdu.edu.cn/getNewsDetail.site?newsId=36c1b735-e0a2-4018-9fb6-7dfb8fb10a39)，2007-09-19，查阅日期：2016年10月2日。
- [关于使用新版博士、硕士学位论文封面的通知及封面填写要求](http://www.grad.sdu.edu.cn/getNewsDetail.site?newsId=a3b4f913-db00-449e-b61e-d48524ded89e)， 2012-04-13，查阅日期：2016年10月2日。
- 封面按照2023年发布的论文封面进行修改

特别感谢[ChenMeng0518](https://github.com/ChenMeng0518/sduthesis)同学提供学士学位论文模板，特别感谢[Delbert](https://github.com/cnDelbert)同学提供的研究生/博士论文模板

## 编译环境

请使用 CTeX 套装进行编译，需要 `xelatex` 和 `pdflatex` 命令支持。

你可以参照使用[VScode编写LaTeX]()来便携配置自己的vscode环境

- `sduthesis-front-cover.def`： 封面。
- `SDUthesistemplate.tex`： 主文件，你的论文结构在此文件当中。
- `sduthesis.cls`： 论文样式文件。
- `fonts-file/`： 字体文件路径(目前没用)。
- `figures/`： 图片存放路径，你也可以创建 `figure`/`pictures`/`picture`/`pic`/`image`等路径。
- `contents/`： 论文所在路径。其中 `usersettings.tex` 为整个项目的设置。

将编译生成的 pdf 文件直接打印即可，注意要求打印社使用双面打印。

### LICENSE

使用署名-非商业性使用 3.0协议，如果你使用了本论文模板，请务必提及。

该项许可协议允许他人基于非商业目的对您的作品重新编排、节选或者以您的作品为基础进行创作。尽管他们的新作品必须注明您的姓名并不得进行商业性使用，但是他们无需在以您的原作为基础创作的演绎作品上适用相同类型的许可条款。

- 这是一份普通人可以理解的许可协议概要：[https://creativecommons.org/licenses/by-nc/3.0/cn/deed.zh](https://creativecommons.org/licenses/by-nc/3.0/cn/deed.zh)。
- 这是对应的法律文本：[https://creativecommons.org/licenses/by-nc/3.0/cn/legalcode](https://creativecommons.org/licenses/by-nc/3.0/cn/legalcode)。
