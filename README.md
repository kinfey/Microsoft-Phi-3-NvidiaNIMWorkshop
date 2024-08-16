# 欢迎来到 Microsoft Phi-3 NVIDIA NIM Workshop

欢迎，各位学习 Microsoft Phi-3 和 NVIDIA NIM , 本次学习结合例子，让大家体验 NIM 的使用方式，在实验开始前，我们需要做如下准备

    A. 注册 NIM 通过该网站注册使用 https://build.nvidia.com/explore/discover

    B. 在您的电脑配置如下环境：

        1. 安装 Python 3.10.x+ (建议使用 miniforge 方式创建)
        2. 安装 .NET 8 (下载地址 [https://dotnet.microsoft.com/](https://dotnet.microsoft.com/))
        3. 安装 Visual Studio Code
        4. 安装 Visual Studio Code 插件 （.NET Extension Pack 和 Python, Jupyter ）
        5. 安装 Python 库 - Jupyter Notebook

    ```bash

    pip install jupyter

    ```

    C. 所有例子请在 Visual Studio Code 上打开，在使用时请基于编程语言选择好 Kernel (Python or .NET)

完环境配置后，大家可以安心进入 Workshop. 

### **📖📖 课程 PPT** [Phi-3 with NVIDIA NIM](./ppt/nvidia-summer-bootcamp-kinfey.pdf)

## **🧪 实验一： 体验多环境下的 Phi-3-mini 引用方式**

Phi-3-mini 可以在不同端侧模型上使用，大家可以通过 Ollama, LM Studio, LlamaEdge 等工具进行引用，而且可以在 CPU, NPU, GPU 的运算加速下完成，各位建议大家尝试一下不同的本地部署方式(边缘设备推荐使用 LLamaEdge)

- [结合 LlamaEdge 的 Jetson NX 推理方式](https://github.com/microsoft/Phi-3CookBook/blob/main/md/03.Inference/translations/zh-cn/Jetson_Inference.md)

- [在 Ollama 上使用 Phi-3](https://github.com/microsoft/Phi-3CookBook/blob/main/md/02.QuickStart/translations/zh-cn/Ollama_QuickStart.md)

- [在 LM Studio 上使用 Phi-3](https://github.com/microsoft/Phi-3CookBook/blob/main/md/02.QuickStart/translations/zh-cn/LMStudio_QuickStart.md)

### **🍔 巩固练习**

您能用 Python 访问 Ollama 或者 LlamaEdge 或者 LM Studio 发布的 API 吗？ 请用 Notebook 完成该练习


## **🧪 实验二： 在 NVIDIA NIM 上使用 Phi-3**

或者用 API 的方式更直接，那我们玩玩 NIM

- [NVIDIA NIM with Phi-3-instruct](./Phi-3-Instruct.ipynb)

- [NVIDIA NIM with Phi-3-vision](./Phi-3-Vision.ipynb)

您可以通过 NVIDIA NIM 快速完成文本生成，对话补全的工作，也可以完成图像分析的工作。

### **🍔 巩固练习**

您能用 NVIDIA NIM 提供的 Phi-3 API，完成一个看图作文吗？找一张您生活中的图片，用 Phi-3 简单描述一下。


## **🧪 实验三： 通过 Semantic Kernel 调用 NVIDIA NIM 上的 Phi-3**

学习结合  Semantic Kernel 创建 Phi-3 的 Copilot 应用

 - [Semantic Kernel with NVIDIA NIM Phi-3](./Phi-3-SK.ipynb) 

### **🍔 巩固练习** 

学习 Semantic Kernel, 访问 [Phi-3 Cookbook](https://github.com/microsoft/semantickernelcookbook)


## **🧪 实验四： 使用 NVIDIA NIM 上的 Phi-3 构建一个语音机器人原型**

你有用过小米音箱吗？我们一起用 Phi-3 创造属于自己的智能语音应答系统

  - [Phi-3 语音机器人](./Phi-3-Voice.ipynb)


### **🍔 巩固练习**

如果您学有余力，请把该原型优化，构建一个语音机器人


🎉🎉🎉 谢谢您的参与，通过一小时的学习，您成功开启了 Phi-3 的入门，希望您能通过 NVIDIA NIM 以及 Phi-3 构建更好的应用

## **🚀🚀🚀🚀 学习建议 - 了解更多 Phi-3**

建议您通过 Cookbook 学习更多 Phi-3 的知识 https://aka.ms/phi-3cookbook

###💕💕注意：### 大家别忘记给本次实验和 Phi-3 Cookbook 点个🌟🌟🌟🌟

