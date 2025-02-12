# use-ncnn

  **这里提供关于 ncnn 的安装、使用、源码分析和加速手段的详细教程**   
B站视频：https://www.bilibili.com/video/BV1MV411F7iV/?spm_id_from=333.999.0.0

## ncnn 是什么？

ncnn 是一个为移动端和嵌入式设备优化的高性能神经网络前向计算框架。它具有轻量级、高性能和跨平台等特点，适用于各种资源受限的设备。

## 安装和使用

- [ncnn的使用01：ncnn的编译和安装](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/ncnn01-ncnn%E7%9A%84%E7%BC%96%E8%AF%91%E5%92%8C%E5%AE%89%E8%A3%85.md)
- [ncnn的使用02：onnx转ncnn模型跑resnet18](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/ncnn02-onnx%E8%BD%ACncnn%E6%A8%A1%E5%9E%8B%E8%B7%91resnet18.md)
- [ncnn的使用03：onnx转ncnn模型跑yolov5-6.0](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/ncnn03-onnx%E8%BD%ACncnn%E6%A8%A1%E5%9E%8B%E8%B7%91yolov5-6.0.md)
- [ncnn的使用04：pnnx转ncnn模型跑resnet18](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/ncnn04-pnnx%E8%BD%ACncnn%E6%A8%A1%E5%9E%8B%E8%B7%91resnet18.md)
- [ncnn的使用05：pnnx转ncnn模型跑yolov5-6.0](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/ncnn05--pnnx%E8%BD%ACncnn%E6%A8%A1%E5%9E%8B%E8%B7%91yolov5-6.0.md)
  
未完待续，持续更新！！
## ncnn源码分析
- [ncnn源码分析01：ncnn的内存管理](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%9001-ncnn%E7%9A%84%E5%86%85%E5%AD%98%E7%AE%A1%E7%90%86.md)
- [ncnn源码分析02：ncnn的Mat设计](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%9002-ncnn%E7%9A%84Mat%E8%AE%BE%E8%AE%A1.md)
- [ncnn源码分析03：ncnn里一些重要类的概述](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%9003-ncnn%E9%87%8C%E4%B8%80%E4%BA%9B%E9%87%8D%E8%A6%81%E7%B1%BB%E7%9A%84%E6%A6%82%E8%BF%B0.md)
- [ncnn源码分析04：ncnn的模型加载](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%9004-ncnn%E7%9A%84%E6%A8%A1%E5%9E%8B%E5%8A%A0%E8%BD%BD.md)
- [ncnn源码分析05：ncnn的模型推理过程](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%9005-ncnn%E7%9A%84%E6%A8%A1%E5%9E%8B%E6%8E%A8%E7%90%86%E8%BF%87%E7%A8%8B.md)
- [ncnn源码分析06：ncnn卷积类算子实现](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%9006-ncnn%E5%8D%B7%E7%A7%AF%E7%B1%BB%E7%AE%97%E5%AD%90%E5%AE%9E%E7%8E%B0.md)
- [ncnn源码分析07：ncnn激活函数类算子实现](https://github.com/HuPengsheet/use-ncnn/blob/main/notes/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%9007-ncnn%E6%BF%80%E6%B4%BB%E5%87%BD%E6%95%B0%E7%B1%BB%E7%AE%97%E5%AD%90%E5%AE%9E%E7%8E%B0.md)


这个部分将深入探讨 ncnn 的源码结构和实现细节。通过分析源码，你将对 ncnn 的内部工作原理有更深入的理解。持续更新中！！！

## ncnn加速手段

在这个部分，你将学习如何进一步优化和加速 ncnn 的性能。我们将介绍各种加速手段和技巧，以提高神经网络的前向计算速度。

持续更新中！！！
