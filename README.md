## 基于Mask R-CNN的致密油储层岩石薄片图像鉴定方法研究
---

### 目录
1. [所需环境 Environment](#所需环境)
2. [文件说明 Explain](#文件说明)
3. [训练步骤 How2train](#训练步骤)
4. [识别结果 Result](#识别结果)

### 所需环境
PyTorch >= 1.1

Python >= 3.6

onnxruntime-gpu == 1.6.0 for CUDA 10.2

TensorRT == 7.2.3.4

tensorboardX

为保证实验对比的可靠性，和SMRS使用相同的骨干网络(ResNet101)与学习率。