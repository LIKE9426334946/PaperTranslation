# Paper Information

- **论文名称：** Pyramid Scene Parsing Network
- **中文标题：** 金字塔场景解析网络
- **模型简称：** PSPNet
- **作者：** Hengshuang Zhao、Jianping Shi、Xiaojuan Qi、Xiaogang Wang、Jiaya Jia
- **发表年份：** 2017 年
- **会议/期刊：** IEEE Conference on Computer Vision and Pattern Recognition（CVPR 2017）
- **论文链接：** [CVF 官方论文页面](https://openaccess.thecvf.com/content_cvpr_2017/html/Zhao_Pyramid_Scene_Parsing_CVPR_2017_paper.html)
- **中文翻译：** [Pyramid_Scene_Parsing_Network_中文翻译.md](./Pyramid_Scene_Parsing_Network_中文翻译.md)

## Translation Scope

本文档依据用户提供的 `16-PSPNet.pdf`，按照 `Translation.MD` 的要求翻译论文正文，包括摘要和以下章节：

1. 引言。
2. 相关工作。
3. 金字塔场景解析网络，包括重要观察、金字塔池化模块和网络架构。
4. 基于 ResNet 的 FCN 的深监督。
5. 实验，包括实现细节、2016 年 ImageNet 场景解析挑战赛、PASCAL VOC 2012 和 Cityscapes。
6. 结语。

保留原有章节编号和标题层级、加粗与斜体、列表，以及正文中的数学符号和公式。数学表达式使用 Markdown 行内数学格式保留原有内容，不补充推导或解释。正文中的实验数值与分析均予保留。

未包含：

- 正文中的作者信息、作者单位、邮箱、论文编号、DOI 和 GitHub 链接。
- 图片、图注、图片内文字和表格内容；Figure 1–9 与 Table 1–8 均在相关正文附近保留省略位置标记。
- 文献引用编号、参考文献列表及脚注中的外部结果链接。
- 致谢、资助信息、附录或补充材料。
- 额外的公式解释、推导、模型实现或研究笔记。

作者信息与论文来源仅在本 README 中列出。正文中的图表编号及章节交叉引用保留，便于对照原论文阅读。原文部分实验段落以 accuracy 泛称成绩，译文根据对应指标将 PASCAL VOC 和 Cityscapes 的相关总体成绩明确为 mIoU，避免与像素准确率混淆。论文中的性能排名和实验结论均对应原文发表时的情况。

## Original Paper

翻译来源为用户上传的 11 页 PDF 文件 `16-PSPNet.pdf`，其首页标注版本为 **arXiv:1612.01105v2，2017 年 4 月 27 日**。

- [与上传文件对应的 arXiv 版本](https://arxiv.org/abs/1612.01105v2)
- [CVPR 2017 / CVF 官方论文页面](https://openaccess.thecvf.com/content_cvpr_2017/html/Zhao_Pyramid_Scene_Parsing_CVPR_2017_paper.html)

正文翻译以上传 PDF 为准；作者、会议与正式发表年份已通过 CVF 官方页面核对。上传文件第 9 页仅含图表，第 10–11 页为参考文献；图表按要求省略并标记位置，参考文献不翻译。

本目录按要求添加 `16-` 前缀，命名为 `16-Pyramid_Scene_Parsing_Network_2017`。
