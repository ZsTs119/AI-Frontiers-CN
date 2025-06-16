# Trans-LoRA - Trans-LoRA: towards data-free Transferable Parameter Efficient Finetuning

**模型功能**：
该模型提出了Trans - LoRA方法，能够通过无数据迁移学习来实现参数的高效微调，从而增强模型的泛化能力。

**arXiv 文章链接**：
[arXiv 链接](https://arxiv.org/abs/2405.17258)

**作者/团队**：
文章作者为Haozhe Zhang, Shumin Deng, Hongbin Ye, Chuanqi Tan, Fei Huang, Luo Si。

**发表日期**：
2024年5月29日

**研究进展**：
传统的参数高效微调（PEFT）方法往往需要大量的下游数据来实现良好的迁移效果，而该研究提出的Trans - LoRA方法可以在无数据的情况下进行迁移学习和参数高效微调，为模型微调提供了新的思路。它通过引入新的正则化策略，增强了模型的泛化能力，并且在多个基准数据集上进行了验证，取得了较好的效果。

**应用场景**：
该模型可应用于软件开发、模型训练等场景。在软件开发中，通过高效微调模型参数可以提高代码生成的准确性和效率；在模型训练中，增强模型的泛化能力有助于提高模型在不同数据集上的性能。