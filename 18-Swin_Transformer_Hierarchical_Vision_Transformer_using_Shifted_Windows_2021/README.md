# Paper Information

- 论文名称　Swin Transformer: Hierarchical Vision Transformer using Shifted Windows
- 中文标题　Swin Transformer：使用移位窗口的层次化视觉 Transformer
- 作者　Ze Liu、Yutong Lin、Yue Cao、Han Hu、Yixuan Wei、Zheng Zhang、Stephen Lin、Baining Guo
- 发表年份　2021
- 会议　IEEE/CVF International Conference on Computer Vision（ICCV），会议论文集第 10012–10022 页
- 论文链接　[ICCV 会议论文页面](https://openaccess.thecvf.com/content/ICCV2021/html/Liu_Swin_Transformer_Hierarchical_Vision_Transformer_Using_Shifted_Windows_ICCV_2021_paper.html)
- 中文翻译说明　依据所附 PDF 翻译，沿用原文章节顺序、公式编号和实验指标。[阅读中文译文](./Swin_Transformer_Hierarchical_Vision_Transformer_using_Shifted_Windows_中文翻译.md)

## Translation Scope

译文包含摘要及第 1 至 5 节，涵盖引言、相关工作、方法、实验和结论。正文中的 4 个编号公式及 4 条技术脚注均予保留。4 幅图和 6 张表以位置标记代替，正文中对图表的讨论照常翻译。

译文略去作者资料、文献引用编号、代码仓库链接、图表及其题注、致谢、附录和参考文献。公式保留原文符号与运算形式，未另加推导。

## Original Paper

翻译底本为所附的 18-Swin Transformer.pdf，共 14 页，对应 2021 年 8 月 17 日的 arXiv v2 版。[该版原文](https://arxiv.org/abs/2103.14030v2)

## 原文核对说明

- 第 4.1 节正文中，在 ImageNet-1K 上按常规方式训练、输入为 $224^2$ 时，Swin-B 的 top-1 准确率写作 83.3%，表 1(a) 的对应条目为 83.5%。译文保留正文的 83.3%。
- 引言有一句用“low latency”描述逐像素滑动窗口的访存劣势。紧接着的比较、第 2 节及表 5 均表明滑动窗口的实际延迟较高。译文按这一上下文处理，并用“移位窗口”与“滑动窗口”区分文中的两种方法。
- 原文脚注 4 的整除关系用词颠倒。译文按紧邻的窗口数公式和右下侧填充操作，表述为将特征图的高和宽补齐至窗口边长的整数倍。
