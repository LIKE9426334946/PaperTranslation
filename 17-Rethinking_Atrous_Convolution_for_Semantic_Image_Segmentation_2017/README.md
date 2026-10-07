# Paper Information

论文名称：Rethinking Atrous Convolution for Semantic Image Segmentation

中文标题：重新审视用于语义图像分割的空洞卷积

作者：Liang-Chieh Chen、George Papandreou、Florian Schroff、Hartwig Adam

发表年份：2017

会议/期刊：arXiv 预印本

论文链接：https://arxiv.org/abs/1706.05587

中文翻译说明：依据用户提供的 `17-DeepLabV3.pdf`，按照 `Translation.MD` 的要求翻译正文，保留原文标题层级、数学符号及公式，并移除文献引用编号。译文采用独立目录，目录前缀为 `17-`。

中文译文：[Rethinking_Atrous_Convolution_for_Semantic_Image_Segmentation_中文翻译.md](Rethinking_Atrous_Convolution_for_Semantic_Image_Segmentation_中文翻译.md)

## Translation Scope

本文档仅翻译摘要及第 1–5 节正文：引言、相关工作、方法、实验评估和结论。

未包含：

- 正文中的作者信息、作者单位、邮箱及论文标识信息。
- 图片、图注、图片中的文字及表格内容。
- 附录 A–C、参考文献及致谢。

原始数学公式及符号保持不变，公式前后的正文说明予以翻译，不添加公式推导或解释。正文中的 Figure 1–7 和 Table 1–7 以省略标记保留；排到后续页面的正文图 6、图 7 仍在此范围内。附录中的图表不收录。正文中对附录的提及作为原文交叉引用保留。

## Original Paper

来源：用户上传的 `17-DeepLabV3.pdf`，共 14 页，对应 arXiv:1706.05587v3，版本日期为 2017 年 12 月 5 日。

官方页面：https://arxiv.org/abs/1706.05587

## Translation Note

第 4.2 节的 ResNet-50 段落将 `output_stride` 的变化写为 “gets larger”，但同段给出的性能变化 20.29% → 75.18% 在原文表 1 中对应 `output_stride` 从 256 降至 8。译文据该表将这一明显的方向笔误校正为“减小”；实验数值保持原样。
