# ShiftAddLLM - ShiftAddLLM: Accelerating Pretrained LLMs via Post-Training Multiplication-Less Reparameterization

**模型功能**：
ShiftAddLLM是一种通过训练后无乘法重新参数化方法，旨在减少浮点运算，从而提升预训练语言模型的效率。该方法通过重新参数化模型中的矩阵乘法操作，将其转化为加法和移位操作，显著降低了计算复杂度，使得模型在保持性能的同时，运行速度更快，能耗更低。

**arXiv 文章链接**：
[ShiftAddLLM: Accelerating Pretrained LLMs via Post-Training Multiplication-Less Reparameterization](https://arxiv.org/abs/2406.05981)

**作者/团队**：
Yuhang Li, Yonggan Fu, Shijie Lin, Jiawei Ren, Shuhan Yuan, Yingyan Lin

**发表日期**：
2024年6月8日

**研究进展**：
该研究提出了ShiftAddLLM方法，通过训练后无乘法重新参数化技术，有效减少了预训练语言模型中的浮点运算。具体而言，该方法将模型中的矩阵乘法操作转化为加法和移位操作，从而显著降低了计算复杂度。实验结果表明，ShiftAddLLM在多种基准测试中表现优异，不仅保持了模型的性能，还大幅提升了运算速度和能效。这一创新为大规模语言模型的部署和应用提供了新的解决方案。

**应用场景**：
ShiftAddLLM主要应用于需要高效运行预训练语言模型的场景，如自然语言处理任务（文本生成、翻译、问答等）、智能客服、语音助手等。通过减少计算资源的需求，该方法使得大规模语言模型能够在资源受限的设备上高效运行，拓展了其应用范围。
```