# 📘 深度学习读书笔记 | Deep Learning: Foundations and Concepts

## 📖 章节信息

*   **书名**：Deep Learning: Foundations and Concepts
*   **章节**：第 1 章 - 《深度学习革命》
*   **阅读日期**：2025/06/16
*   **阅读页码**：1–19（书本页码）

***

## 🧠 核心概念总结 | Core Concepts Summary

1.  深度学习的“革命”源于大数据、计算能力、算法三者的交汇。

2.  与传统机器学习相比，深度学习强调端到端的特征学习，不依赖人工特征提取。

3.  神经网络虽早已有之，但由于深度网络的训练困难，一度沉寂，直到新技术（如<span class="highlight" data-annotation="%7B%22attachmentURI%22%3A%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2F8QNC5PHV%22%2C%22pageLabel%22%3A%2249%22%2C%22position%22%3A%7B%22pageIndex%22%3A48%2C%22rects%22%3A%5B%5B148.12830000000002%2C401.93225937500046%2C180.61530000000005%2C411.94040000000047%5D%5D%7D%2C%22citationItem%22%3A%7B%22uris%22%3A%5B%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2FI5PGJQ68%22%5D%2C%22locator%22%3A%2249%22%7D%7D" ztype="zhighlight"><a href="zotero://open/library/items/8QNC5PHV?page=49">“规模化”</a></span>、<span class="highlight" data-annotation="%7B%22attachmentURI%22%3A%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2F8QNC5PHV%22%2C%22pageLabel%22%3A%2249%22%2C%22position%22%3A%7B%22pageIndex%22%3A48%2C%22rects%22%3A%5B%5B412.0563000000001%2C369.92825937500044%2C498.9017999999999%2C379.93640000000045%5D%2C%5B104.87880000000001%2C353.9262593750004%2C161.44230000000002%2C363.93440000000044%5D%5D%7D%2C%22citationItem%22%3A%7B%22uris%22%3A%5B%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2FI5PGJQ68%22%5D%2C%22locator%22%3A%2249%22%7D%7D" ztype="zhighlight"><a href="zotero://open/library/items/8QNC5PHV?page=49">“残差连接(residual connection)”</a></span>、<span class="highlight" data-annotation="%7B%22attachmentURI%22%3A%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2F8QNC5PHV%22%2C%22pageLabel%22%3A%2249%22%2C%22position%22%3A%7B%22pageIndex%22%3A48%2C%22rects%22%3A%5B%5B402.0183000000002%2C337.9242593750004%2C498.8912999999999%2C347.9324000000004%5D%2C%5B104.86830000000003%2C321.9222593750004%2C175.23930000000004%2C331.9304000000004%5D%5D%7D%2C%22citationItem%22%3A%7B%22uris%22%3A%5B%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2FI5PGJQ68%22%5D%2C%22locator%22%3A%2249%22%7D%7D" ztype="zhighlight"><a href="zotero://open/library/items/8QNC5PHV?page=49">“自 动 微 分(automatic differentiation)”</a></span>）才真正引发复兴。

***

## 🧪 关键公式与推导 | Key Equations & Derivations

本章以概念性介绍为主，无具体数学推导，强调历史背景与应用场景。

***

## 💡 关键图示解读 | Diagram Interpretation

![\<img alt="" data-attachment-key="GR2LR87A" width="952" height="687" src="attachments/GR2LR87A.png" ztype="zimage"> | 952](attachments/GR2LR87A.png)

*   **图名或编号**：图 1.17 <span class="highlight" data-annotation="%7B%22attachmentURI%22%3A%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2F8QNC5PHV%22%2C%22pageLabel%22%3A%2248%22%2C%22position%22%3A%7B%22pageIndex%22%3A47%2C%22rects%22%3A%5B%5B139.3932%2C114.004%2C276.6732000000002%2C121.5365%5D%5D%7D%2C%22citationItem%22%3A%7B%22uris%22%3A%5B%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2FI5PGJQ68%22%5D%2C%22locator%22%3A%2248%22%7D%7D" ztype="zhighlight"><a href="zotero://open/library/items/8QNC5PHV?page=48">“练最先进的神经网络所需的计算周期数”</a></span><span class="citation" data-citation="%7B%22citationItems%22%3A%5B%7B%22uris%22%3A%5B%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2FI5PGJQ68%22%5D%2C%22locator%22%3A%2248%22%7D%5D%2C%22properties%22%3A%7B%7D%7D" ztype="zcitation">(<span class="citation-item"><a href="zotero://select/library/items/I5PGJQ68">“Deep Learning: Foundations and Concepts”, p. 48</a></span>)</span>

*   **解读**：

    *   <span class="highlight" data-annotation="%7B%22attachmentURI%22%3A%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2F8QNC5PHV%22%2C%22pageLabel%22%3A%2248%22%2C%22position%22%3A%7B%22pageIndex%22%3A47%2C%22rects%22%3A%5B%5B482.72399999999976%2C465.966259375%2C493.22399999999976%2C475.9744%5D%2C%5B99.2121%2C449.966259375%2C493.23509999999976%2C459.9744%5D%2C%5B99.2121%2C433.966259375%2C493.24559999999974%2C443.9744%5D%2C%5B99.2121%2C417.966259375%2C493.24559999999997%2C427.9744%5D%2C%5B99.2121%2C401.966259375%2C261.9621%2C411.9744%5D%5D%7D%2C%22citationItem%22%3A%7B%22uris%22%3A%5B%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2FI5PGJQ68%22%5D%2C%22locator%22%3A%2248%22%7D%7D" ztype="zhighlight"><a href="zotero://open/library/items/8QNC5PHV?page=48">“从 感知机时代直至 2012 年前后,计算需求的翻倍周期约为 2 年,这与摩尔定律所预测的 计算性能增长的总体趋势基本吻合。然而,自 2012 年步入深度学习时代以来,计算需 求再次呈现出指数级的增长态势,但这一次的翻倍周期锐减至仅 3.4 个月,这意味着 计算能力每年增长高达 10 倍之多!”</a></span><span class="citation" data-citation="%7B%22citationItems%22%3A%5B%7B%22uris%22%3A%5B%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2FI5PGJQ68%22%5D%2C%22locator%22%3A%2248%22%7D%5D%2C%22properties%22%3A%7B%7D%7D" ztype="zcitation">(<span class="citation-item"><a href="zotero://select/library/items/I5PGJQ68">“Deep Learning: Foundations and Concepts”, p. 48</a></span>)</span>

***

## 🔍 难点与疑问 | Difficult Points & Questions

1.  如何评估“可解释性”与“准确率”的权衡？

***

## 📎 与现实应用的联系 | Connection to Real-World Applications

*   可用于医疗图像识别、人脸识别、NLP等任务；

***

## 🛠️ 实验/代码实践记录 | Code or Experiment Reflection

本章为概述性章节，暂未涉及具体实验内容。

***

## 🧭 知识图谱更新 | Update to Knowledge Graph

*   “深度学习历史”节点新增：

    *   感知机 ➝ BP ➝ 深层网络 ➝ GPU ➝ ImageNet ➝ Transformer

*   “神经网络优势”节点新增：

    *   特征自动提取、表达能力强、可微优化路径

*   “技术细节”节点新增：

    *   <span class="highlight" data-annotation="%7B%22attachmentURI%22%3A%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2F8QNC5PHV%22%2C%22pageLabel%22%3A%2249%22%2C%22position%22%3A%7B%22pageIndex%22%3A48%2C%22rects%22%3A%5B%5B412.0563000000001%2C369.92825937500044%2C498.9017999999999%2C379.93640000000045%5D%2C%5B104.87880000000001%2C353.9262593750004%2C161.44230000000002%2C363.93440000000044%5D%5D%7D%2C%22citationItem%22%3A%7B%22uris%22%3A%5B%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2FI5PGJQ68%22%5D%2C%22locator%22%3A%2249%22%7D%7D" ztype="zhighlight"><a href="zotero://open/library/items/8QNC5PHV?page=49">“残差连接(residual connection)”</a></span><span class="citation" data-citation="%7B%22citationItems%22%3A%5B%7B%22uris%22%3A%5B%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2FI5PGJQ68%22%5D%2C%22locator%22%3A%2249%22%7D%5D%2C%22properties%22%3A%7B%7D%7D" ztype="zcitation">(<span class="citation-item"><a href="zotero://select/library/items/I5PGJQ68">“Deep Learning: Foundations and Concepts”, p. 49</a></span>)</span>

    *   残差连接是深度神经网络中的一种结构设计，最早用于 ResNet（Residual Network） 网络中。它的核心思想是：让神经网络学习残差（residual），而不是直接学习目标映射。

    *   <span class="highlight" data-annotation="%7B%22attachmentURI%22%3A%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2F8QNC5PHV%22%2C%22pageLabel%22%3A%2249%22%2C%22position%22%3A%7B%22pageIndex%22%3A48%2C%22rects%22%3A%5B%5B402.0183000000002%2C337.9242593750004%2C498.8912999999999%2C347.9324000000004%5D%2C%5B104.86830000000003%2C321.9222593750004%2C196.84830000000002%2C331.9304000000004%5D%5D%7D%2C%22citationItem%22%3A%7B%22uris%22%3A%5B%22http%3A%2F%2Fzotero.org%2Fusers%2F16187297%2Fitems%2FI5PGJQ68%22%5D%2C%22locator%22%3A%2249%22%7D%7D" ztype="zhighlight"><a href="zotero://open/library/items/8QNC5PHV?page=49">“自 动 微 分(automatic differentiation)方法”</a></span>

***

## 📚 延伸阅读 & 参考资料 | Further Reading

*   残差连接：https\://medium.com/data-science/what-is-residual-connection-efb07cab0d55
*   论文：《Deep Residual Learning for Image Recognition》 (ResNets)

<!---->

*   自 动 微 分：<https://lotabout.me/2023/Auto-Differentiation-Part-1-Algorithm/>

![\<img alt="" data-attachment-key="TRFJCURA" width="962" height="347" src="attachments/TRFJCURA.png" ztype="zimage"> | 962](attachments/TRFJCURA.png)

*   论文：《Automatic differentiation in machine learning: a survey》

***

## 🧘 本章小结 & 反思 | Personal Reflection

***

## 📌 To-Do 列表 | Tasks to Follow Up

1.  阅读Resnet 论文和源代码
2.  阅读自动微分的相关论文
3.  了解深度学习规模化的底层原理，包括CUDA
4.  了解深度学习规模化的各种技巧，比如DDP等等
