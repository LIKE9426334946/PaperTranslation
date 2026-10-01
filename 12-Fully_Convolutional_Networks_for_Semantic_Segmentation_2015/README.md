# Paper Information

论文名称：Fully Convolutional Networks for Semantic Segmentation（用于语义分割的全卷积网络）

作者：Jonathan Long、Evan Shelhamer、Trevor Darrell

发表年份：2015 年

会议/期刊：Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition（CVPR 2015）

论文链接：[CVF 官方论文页面](https://openaccess.thecvf.com/content_cvpr_2015/html/Long_Fully_Convolutional_Networks_2015_CVPR_paper.html)；[会议版 PDF](https://openaccess.thecvf.com/content_cvpr_2015/papers/Long_Fully_Convolutional_Networks_2015_CVPR_paper.pdf)

中文翻译说明：本译文依据用户提供的 `12-FCN.pdf`，按 `Translation.MD` 的要求翻译，适合科研学习与阅读。上传文件为 CVPR 2015 会议论文的开放获取版本；译文以该文件为准，不混用其他预印本或后续期刊版本的内容、参数及实验结果。文中“最先进”“此前”“公开版本”等表述均沿用原论文的发表语境。

中文译文：[Fully_Convolutional_Networks_for_Semantic_Segmentation_中文翻译.md](./Fully_Convolutional_Networks_for_Semantic_Segmentation_中文翻译.md)

## Translation Scope

本文档仅翻译论文正文部分，即摘要及第 1–6 节：引言、相关工作、全卷积网络、分割架构、结果与结论。保留原文的章节层级、段落、加粗、斜体强调及列表结构。

- 保留原文的行内公式、三组独立公式及四项评估指标公式，不新增公式编号，不修改公式符号，也不补充推导；翻译原文中与公式相关的文字说明。
- 保留九条与计算效率、图像块采样、模型版本、融合方式和数据集评估有关的技术性脚注。
- Figure 1–6 与 Table 1–5 均使用位置标记替代，不包含图表本体、图注、表格内容及图片中的文字。
- 去除数字形式的文献引用标记，保留正文中必要的作者名、模型名和方法名。
- 不包含论文首页的作者单位、邮箱、共同贡献说明、页眉声明、论文编号、DOI、代码链接、资助信息、致谢及参考文献。上传文件没有单列附录。

原文写法说明：第 4.3 节中，FCN-GoogLeNet 的学习率印为 $5^{-5}$，权重衰减印为 $5^{-4}$ 或 $2^{-4}$；第 3 节第一组公式的索引上界印为 $\leq k$。译文均保留上传 PDF 的写法，未将其擅自改为其他数值或索引范围。

## Original Paper

翻译来源：用户上传的 `12-FCN.pdf`，共 10 页。正文翻译范围为第 1 页摘要及第 1–8 页正文；第 8–9 页的致谢和资助说明、第 9–10 页的参考文献不在翻译范围内。

- 会议来源：[CVPR 2015 官方论文页面](https://openaccess.thecvf.com/content_cvpr_2015/html/Long_Fully_Convolutional_Networks_2015_CVPR_paper.html)
- 对应原文：[Fully Convolutional Networks for Semantic Segmentation，会议版 PDF](https://openaccess.thecvf.com/content_cvpr_2015/papers/Long_Fully_Convolutional_Networks_2015_CVPR_paper.pdf)

本目录为中文学习译文。论文的原创内容及相关权利归原作者或相应权利人所有。
