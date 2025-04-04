# 第一次技术培训: pytorch

## 概念介绍

### 深度学习

深度学习是机器学习的一个子领域，基于多层人工神经网络（如卷积神经网络、循环神经网络等）进行特征学习和模式识别。其核心是通过分层结构自动提取数据的多层次抽象表示（从低级到高级特征），利用反向传播算法优化网络参数。典型应用包括图像识别、自然语言处理和语音识别。关键特点为：依赖大数据训练、计算密集型（常需GPU/TPU）、端到端学习能力，以及可处理高维非线性关系。

### 神经网络

神经网络是一种受生物神经元启发的计算模型，由相互连接的人工神经元（节点）组成，通过权重和激活函数处理输入数据并输出预测结果。其核心是通过训练（如反向传播）自动调整参数，以学习输入与输出之间的映射关系。传统神经网络通常较浅（1-2层），而深度学习通过堆叠多个隐藏层提取多层次特征，实现更复杂的模式识别。因此，深度学习是神经网络的扩展，核心区别在于深度（层数）和自动特征学习能力。

### Pytorch

PyTorch 是一个基于 Python 的开源机器学习框架，由 Facebook（现 Meta）开发，主要用于深度学习。其核心特点包括：
  1. 动态计算图（Dynamic Computation Graph）：支持即时执行的自动微分（Autograd），便于调试和灵活建模。
  2. 张量计算（Tensor）：类似 NumPy，但支持 GPU 加速，适合高效数值计算。
  3. 模块化设计：提供 torch.nn 等高级 API，方便构建和训练神经网络。
  4. 生态系统：集成工具链（如 TorchVision、TorchText），支持研究到生产部署。优势：易用性强，适合学术研究，且被工业界广泛采用。对比框架如 TensorFlow，PyTorch 更偏向动态图编程范式。

## 基本信息

- **主讲人**: 黄浩
- **时间**：3月29日14:00-15:30
- **培训内容**：
  1. 神经网络的原理
  2. 基于pytorch的MLP

## 材料

- **回放**： [清华云盘](https://cloud.tsinghua.edu.cn/d/64b19016cf174bfc9830/)
- **讲义与代码**： [清华云盘](https://cloud.tsinghua.edu.cn/d/94860693b3f54dd2b91f/)