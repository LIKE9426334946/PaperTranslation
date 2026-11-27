# Paper Information

- 论文名称　EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks
- 中文标题　EfficientNet：重新审视卷积神经网络的模型缩放
- 作者　Mingxing Tan、Quoc V. Le
- 发表年份　2019
- 会议　第 36 届国际机器学习大会（ICML 2019），PMLR 第 97 卷，第 6105–6114 页
- 论文链接　[PMLR 会议论文页面](https://proceedings.mlr.press/v97/tan19a.html)
- 中文翻译说明　依据所附 ICML 会议版 PDF 翻译，保留原文章节顺序、数学符号与公式编号。[阅读中文译文](./EfficientNet_Rethinking_Model_Scaling_for_Convolutional_Neural_Networks_中文翻译.md)

## Translation Scope

译文涵盖摘要及第 1 至 7 节，包括模型缩放问题的形式化描述、复合缩放方法、EfficientNet 架构、ImageNet 和迁移学习实验，以及讨论和结论。保留了 3 个编号公式和 3 条技术脚注。

正文中的 8 幅图与 6 张表以原编号标记位置，对图表的正文讨论保留。译文略去作者资料、文献引用、图表及其题注、致谢和参考文献。公式沿用原文符号，未另加推导。

## Original Paper

底本为所附的 23-EfficientNet.pdf，共 10 页。此版报告 EfficientNet-B7 在 ImageNet 上的 top-1 准确率为 84.4%，top-5 准确率为 97.1%。[会议版原文 PDF](https://proceedings.mlr.press/v97/tan19a/tan19a.pdf)

## 原文核对说明

- 第 3.1 节在式（1）前展开逐层复合时连续写了两次 $\mathcal{F}_1$。译文保留原式，右端仍为按 $j$ 索引的逐层复合。
- 第 3.3 节以图像细节说明增加通道数的必要性时，原文再次写作“深度”。译文依照引言中相同的论述写作“宽度”。式（3）后的文字也颠倒了前两个维度的顺序，译文依照公式，将 $\alpha,\beta,\gamma$ 分别对应深度、宽度和分辨率。
- 引言给出的 ResNet-50 top-1 准确率是 76.3%，表 2、表 3 列为 76.0%。第 3.3 节正文比较网络宽度时写的是 $d=2.0,\ r=2.0$，图 4 中对应的曲线标为 $d=2.0,\ r=1.3$。译文均保留正文数值。
- 第 5.3 节称 EfficientNet 在八个数据集中的五个上超过了此前的最佳准确率。按表 5 列出的精度，其中三个超过、两个持平，因此译为“五个上达到或超过”。
