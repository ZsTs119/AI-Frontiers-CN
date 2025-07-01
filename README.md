# AI-Frontiers-CN

## 📌 项目简介

这是一个用于整理和展示大模型研究的开源知识库，涵盖以下内容：

- 最新模型研究
- 模型功能介绍
- arXiv 论文链接
- 按日期分类的模型记录
- 按功能分类的模型记录

## 📁 目录结构

```
├── 2025-06-09/  # 按日期分类
│   ├── text-generation/  # 文本生成
│   ├── audio-generation/  # 音频生成
│   ├── image-generation/  # 图像生成
│   ├── video-generation/  # 视频生成
│   ├── multimodal-generation/  # 多模态生成
│   ├── 3d-generation/  # 3D生成
│   ├── game-strategy-generation/  # 游戏与策略生成
│   ├── scientific-data-generation/  # 科学计算与数据生成
│   ├── code-generation/  # 代码生成与数据增强
│   └── cross-modal-generation/  # 跨模态生成
├── 2025-06-10/  # 按日期分类
│   └── ...
└── README.md
```

## 📚 模型分类说明

| 分类                   | 说明                                     |
| ---------------------- | ---------------------------------------- |
| **文本生成**           | 生成文本内容，如文章、对话、摘要等       |
| **音频生成**           | 生成语音、音乐、音效等                   |
| **图像生成**           | 生成图像、风格迁移、图像补全等           |
| **视频生成**           | 生成视频、动态内容、视频剪辑等           |
| **多模态生成**         | 同时处理文本、图像、音频、视频等         |
| **3D 生成**            | 生成 3D 模型、3D 图像、3D 视频等         |
| **游戏与策略生成**     | 生成游戏场景、角色、物品、策略等         |
| **科学计算与数据生成** | 生成科学数据、模拟数据、合成数据等       |
| **代码生成与数据增强** | 生成代码、增强数据集、模型训练等         |
| **跨模态生成**         | 跨模态检索、跨模态生成、多模态推荐系统等 |

## 📦 安装与使用

1. **克隆仓库**：

   ```bash
   git clone https://github.com/yourusername/model-knowledge-base.git
   ```

2. **部署为网站**：

   - 使用 [GitSite](https://git-site.io/) 或 [Gitee Pages](https://gitee.com/) 部署为静态网站。
   - 仓库中所有 `.md` 文件将自动渲染为 HTML 页面。

3. **添加新模型**：

   - 按日期和分类创建新文件夹，例如：

     ```
     model-knowledge-base/2025-06-10/text-generation/
     ```

   - 在该文件夹中创建 `.md` 文件，格式如下：

```markdown
# [模型名称] - [arXiv 标题]

**模型功能**：

- 生成文本内容
- 支持多语言
- 可用于对话系统

**arXiv 文章链接**：
[arXiv 链接](https://arxiv.org/abs/XXXX)

**作者/团队**：

- 作者姓名或团队名称

**发表日期**：

- 2025-06-10

**研究进展**：

- 该模型在文本生成方面表现出色
- 支持跨模态生成
- 适用于自然语言处理、计算机视觉等多领域

**应用场景**：

- 自动写作
- 对话系统
- 多模态推荐系统
```

## 📌 贡献指南

- 请将新模型按日期和分类添加到相应文件夹中。
- 每个模型的 `.md` 文件应包含以下信息：
  - 模型名称
  - arXiv 文章链接
  - 模型功能
  - 作者/团队
  - 发表日期
  - 研究进展
  - 应用场景

## 📄 许可证

本项目采用 [MIT License](https://choosealicense.com/licenses/mit)。

## 📞 联系方式

如果你有任何问题或需要帮助，请联系我：

- GitHub: [https://github.com/ZsTs119](https://github.com/ZsTs119)
- E-mail：[zsts@foxmail.com](zsts@foxmail.com)

## 📚 示例

### 示例 1：文本生成模型

**模型名称**：GPT-4  
**arXiv 文章链接**：[GPT-4](https://arxiv.org/abs/XXXX)  
**模型功能**：

- 生成高质量文本
- 支持多语言
- 可用于对话系统、摘要生成、翻译等

**作者/团队**：OpenAI  
**发表日期**：2023-06-15  
**研究进展**：

- 在多个 NLP 任务中表现出色
- 无需微调即可完成多种任务
- 适用于自然语言处理、计算机视觉等多领域

**应用场景**：

- 自动写作
- 对话系统
- 多模态推荐系统

---

## ✅ 项目目标

- 提供一个结构清晰、易于维护的模型知识库。
- 支持按日期和功能分类，便于用户快速查找和浏览。
- 鼓励社区贡献，共同完善模型信息。

---

## ✅ 未来扩展

- 添加搜索功能，支持按关键词、日期、分类等条件搜索。
- 支持多语言界面，方便全球用户使用。
- 提供 API 接口，支持开发者集成到自己的应用中。

---

## 📌 感谢

- 感谢 [DataWhale](https://datawhale.cn/) 提供的开发资源和教程支持。
- 感谢 [Awesome-Open-Foundation-Models](https://github.com/wgwang/awesome-open-foundation-models) 提供的开源模型列表和资源。
- 感谢 [GitHub](https://github.com/) 和 [Gitee](https://gitee.com/) 提供的平台支持。
