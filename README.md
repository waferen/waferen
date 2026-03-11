# Shibo Li (李世博) 🎓

> 人工智能 × 教育学 | 高效机器学习研究者

[![Email](https://img.shields.io/badge/Email-2835817201@qq.com-blue?style=flat-square&logo=gmail)](mailto:2835817201@qq.com)
[![Blog](https://img.shields.io/badge/Blog-waferen.github.io-orange?style=flat-square&logo=github)](https://waferen.github.io/)
[![Location](https://img.shields.io/badge/Location-Nanjing-green?style=flat-square)](https://)

---

## 🔬 Research Interests

- **Continual Learning**: Mitigating catastrophic forgetting in neural networks
- **Graph Neural Networks**: Hierarchical GNN for structured data
- **Trajectory Prediction**: Autonomous driving scene understanding
- **Efficient ML**: Edge AI and model compression

---

## 📚 Selected Projects

### 1. View-Batch Replay for Continual Learning
**毕业设计 | Python + PyTorch | CVPR 2025 复现**

复现CVPR 2025论文《Replay Compression for Class-Incremental Learning》(arXiv:2503.18371v1)，受认知心理学间隔效应启发，实现View-Batch Replay机制缓解神经网络灾难性遗忘。

- **论文复现**: 完整实现View-Batch Replay采样机制、渐进式数据增强、KL散度一致性损失
- **改进探索**: 测试不同aug_repeat参数和多种渐进式增强策略，发现高斯噪声效果最佳
- **实验结果**: CIFAR-10类增量学习，准确率从71.67%提升至72.97%，遗忘率降低50.8%
- **关键词**: Continual Learning, Catastrophic Forgetting, Self-supervised Learning

[![ViewBatchModel](https://img.shields.io/badge/Repo-ViewBatchModel-181717?style=flat-square&logo=github)](https://github.com/waferen/ViewBatchModel)
[![Paper](https://img.shields.io/badge/Paper-arXiv:2503.18371v1-B31B1B?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2503.18371v1)

---

### 2. AlphaZero Chinese Chess
**强化学习 | Python + C++ + PyTorch**

基于AlphaZero范式构建中国象棋博弈AI。

- 系统架构：多进程生产者-消费者架构，自我对弈数据收集与网络训练并行
- 网络设计：ResNet双头网络，7层残差块，策略头输出2086维走法概率
- MCTS：PUCT算法，2000次playout，Dirichlet Noise增强探索

[![AlphaChess](https://img.shields.io/badge/Repo-AlphaChess-181717?style=flat-square&logo=github)](https://github.com/waferen/aichess)

---

### 3. GNN-Transformer Trajectory Prediction ⭐ *NEW*
**自动驾驶 | Python + PyTorch Geometric**

复现Waymo VectorNet论文，层次化图神经网络+Transformer实现轨迹预测。

- GNN编码器：SubGraph消息传递网络聚合折线特征，3层GraphLayerProp
- Transformer：Multi-Head Self-Attention建模代理间交互，Masked Softmax处理变长序列
- 实验结果：Argoverse数据集，20帧历史→30帧预测，minADE=2.637, minFDE=6.992

[![VectorNet](https://img.shields.io/badge/Repo-VectorNet-181717?style=flat-square&logo=github)](https://github.com/waferen/GNN-Transformer-Trajectory-Prediction)

---

## 📊 GitHub Stats

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=waferen&layout=compact&theme=default)

---

## 📫 Contact Me

- 📧 Email: [2835817201@qq.com](mailto:2835817201@qq.com)
- 📝 Blog: [waferen.github.io](https://waferen.github.io/)
- 🏫 Location: 南京师范大学仙林校区

---

*"Education is not the filling of a pail, but the lighting of a fire." —— William Butler Yeats*

*致力于让机器学习像人类学习一样高效*
