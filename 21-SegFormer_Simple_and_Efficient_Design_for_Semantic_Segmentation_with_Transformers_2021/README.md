# Paper Information

- 论文名称　SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers
- 中文标题　SegFormer：面向语义分割的简洁高效 Transformer 设计
- 作者　Enze Xie、Wenhai Wang、Zhiding Yu、Anima Anandkumar、Jose M. Alvarez、Ping Luo
- 发表年份　2021
- 会议　NeurIPS 2021，收录于 Advances in Neural Information Processing Systems 第 34 卷
- 论文链接　[NeurIPS 会议论文页面](https://proceedings.neurips.cc/paper/2021/hash/64f1f27bf1b4ec22924fd0acb550c235-Abstract.html)
- 中文翻译说明　译文以所附 PDF 为底本，保留正文的章节、实验条件、数值和数学记号。[阅读中文译文](./SegFormer_Simple_and_Efficient_Design_for_Semantic_Segmentation_with_Transformers_中文翻译.md)

## Translation Scope

译文涵盖摘要及第 1 至 5 节，包括引言、相关工作、方法、实验和结论。式（1）至式（4）保留原编号。正文中的 4 幅图和 5 张表在相关段落留有位置标记，表 1 的各子表共用一个标记。

正文略去作者资料、文献引用编号、代码仓库链接、图片、图表题注及表格内容。致谢、附录 A 至 D 和参考文献不在翻译范围内。

## Original Paper

底本为所附的 21-Segformer.pdf，共 18 页，对应 2021 年 10 月 28 日的 arXiv v3 版。[该版原文](https://arxiv.org/abs/2105.15203v3)

## 原文中的几处表述

- 式（4）第二行的上采样尺寸在 PDF 中写作 $\frac{W}{4}\times\frac{W}{4}$，同段文字给出的输出空间尺寸为 $\frac{H}{4}\times\frac{W}{4}$。译文保留两处各自的写法。
- 引言将高、低分辨率特征分别描述为“精细”和“粗略”。第 3 节开头、第 3.1 节和第 3.3 节对这两个形容词的使用顺序相反。译文按各处原文处理。
- 引言按原文报告与 ICNet 相比的延迟改善幅度。第 4.3 节给出的是帧率差。该节与 DeepLabv3+ 比较的“7.4 FPS”按表 2 读作帧率差值。
- 第 4.3 节给出的最小模型参数量为 380 万，结论写作 370 万。结论中边缘设备的内存写作“100k”，原文未注明单位。
