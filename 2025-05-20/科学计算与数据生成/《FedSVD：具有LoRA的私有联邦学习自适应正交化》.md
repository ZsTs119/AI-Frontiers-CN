# FedSVD - 《FedSVD: Adaptive Orthogonalization for Private Federated Learning with LoRA》

**模型功能**：
FedSVD方法通过自适应正交化增强了低秩自适应（LoRA）在联邦学习中的隐私保护能力，同时提高了模型的训练效率。

**arXiv 文章链接**：
[https://arxiv.org/abs/2505.12805](https://arxiv.org/abs/2505.12805)

**作者/团队**：
论文作者包括Haozhe Si、Shuai Wang、Jie Gao等。

**发表日期**：
2025年5月24日。

**研究进展**：
该研究提出了一种创新的自适应正交化方法（FedSVD）来增强联邦学习中LoRA的隐私保护。通过在训练过程中使用奇异值分解（SVD），模型能够有效地减少参数共享时的信息泄露风险。与传统方法相比，FedSVD显著提高了训练效率，特别是在处理大规模数据集时表现出色。这一方法为解决联邦学习中的隐私和效率问题提供了新的思路。

**应用场景**：
在需要保护数据隐私的分布式计算场景中，如医疗数据、金融数据的联合分析和模型训练。通过使用FedSVD，可以在不泄露敏感数据的前提下，实现多个参与方之间的高效协作学习。