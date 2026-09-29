# Paper Information

论文名称：Attention Is All You Need（注意力就是一切）

作者：Ashish Vaswani、Noam Shazeer、Niki Parmar、Jakob Uszkoreit、Llion Jones、Aidan N. Gomez、Łukasz Kaiser、Illia Polosukhin

发表年份：2017 年

会议/期刊：Advances in Neural Information Processing Systems 30（NIPS 2017）

论文链接：[arXiv v7](https://arxiv.org/abs/1706.03762v7)；[会议论文页面](https://papers.nips.cc/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html)

中文翻译说明：本译文依据用户提供的 `11-Transformer.pdf`，按 `Translation.MD` 的要求翻译，适合科研学习与阅读。上传文件标注为 arXiv:1706.03762v7，版本日期为 2023 年 8 月 2 日；译文以该文件为准，不混用其他版本的正文或实验数值。文中“最佳”“此前”等表述均沿用原论文的发表语境。

中文译文：[Attention_Is_All_You_Need_中文翻译.md](./Attention_Is_All_You_Need_中文翻译.md)

## Translation Scope

本文档仅翻译论文正文部分，即摘要及第 1–7 节：引言、背景、模型架构、采用自注意力的原因、训练、结果与结论。保留原论文的章节层级、段落内容、列表与加粗格式。

- 保留正文中的行内公式和独立公式、原始符号及公式编号，不增加公式推导；翻译原文中与公式相关的文字说明。
- 保留与正文有关的两条技术性脚注，分别说明点积的方差和训练计算量估算时采用的 GPU 算力。
- 正文中的 Figure 1–2 和 Table 1–4 使用位置标记替代，不包含图表本体、图注、表格内容及图片中的文字。
- 去除数字形式的文献引用标记；对以引用编号代指模型或方法的语句，保留必要的模型名或作者名，以保证语义完整。
- 不包含作者单位、邮箱、作者贡献说明、论文编号、DOI、GitHub 链接、资助信息、致谢、参考文献，以及正文之后的注意力可视化附录。

原文一致性说明：摘要中的英法翻译成绩为 41.8 BLEU，而第 6.1 节正文写为 41.0 BLEU；第 5.4 节称采用“三类”正则化，但随后仅列出残差 Dropout 和标签平滑两项。译文均照录上传原文，未擅自统一数值或补写内容。

## Original Paper

翻译来源：用户上传的 `11-Transformer.pdf`，共 15 页。翻译范围为第 1 页摘要和第 2–10 页正文；第 10 页起的致谢及参考文献，以及第 13–15 页的注意力可视化内容不在翻译范围内。

- 对应版本：[Attention Is All You Need，arXiv v7](https://arxiv.org/abs/1706.03762v7)
- 对应 PDF：[arXiv:1706.03762v7](https://arxiv.org/pdf/1706.03762v7)
- 会议来源：[NIPS 2017 官方论文页面](https://papers.nips.cc/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html)

本目录为中文学习译文。论文的原创内容及相关权利归原作者或相应权利人所有。
