### 使用 ESRGAN 进行图像超解析


超分辨率是指通过硬件或软件方法，提高原有图像的分辨率。借助一系列低分辨率图像，得到一幅高分辨率图像的过程，就是超分辨率重建。  

本教程演示了借助已有模型，对图像进行超分辨率处理的过程。

#### 版权信息
* Apache License 2.0 协议

#### 安装环境
* Python：3.6
* TensorFlow：2.3.1

#### 使用说明
* 该模型使用 DIV2K 数据集（双三次降采样的图像）中，大小为 128 x 128 的图像快进行训练
* 相关论文：[ESRGAN: Enhanced Super-Resolution
Generative Adversarial Networks](https://arxiv.org/pdf/1809.00219.pdf)

#### 代码目录
* 准备环境
* 定义辅助函数
* 对从路径加载的图像执行超解析
* 并排比较输出大小

#### 注意事项
* 运行教程请使用「超分辨率.ipynb」，按顺序运行 cell 即可
* 目录中 model 文件夹下为模型文件，esrgan-tf2_1.tar.gz 文件为模型压缩包（本教程运行中未使用压缩包）
