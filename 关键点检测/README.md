# 两天搞定关键点检测毕业设计

标注自己的关键点检测数据集，分别基于YOLOV8和MMPose两个算法库，训练关键点检测深度学习算法，并做性能评估、预测推理、应用部署。

代码教程：https://github.com/TommyZihao/Train_Custom_Dataset

代码测试[云GPU环境](https://featurize.cn?s=d7ce99f842414bfcaea5662a97581bd1)：GPU RTX 3060、CUDA v11.6

作者：同济子豪兄 https://space.bilibili.com/1900783

## 标注关键点检测数据集

视频：https://www.bilibili.com/video/BV19g4y1777q

手带你使用业界通用标注工具Labelme，标注框、点、多段线，形成“30度直角三角板关键点检测样例数据集”。进而，解读labelme标注文件，使用OpenCV可视化标注信息，探索挖掘数据集标注特征。

## Labelme格式标注转换为YOLO格式标注

视频：https://www.bilibili.com/video/BV1QX4y1B7eF

## Labelme格式标注转换为MS COCO格式标注

视频：https://www.bilibili.com/video/BV1vc411J7GC

## YOLOV8关键点检测-预训练模型预测

https://www.bilibili.com/video/BV1yg4y177ef

使用YOLOV8预训练关键点检测（人体姿态估计）模型，通过命令行和Python API，分别对图像、视频、摄像头实时画面，进行推理预测，解析17个人体关键点的预测结果，并将预测结果自定义可视化。

## YOLOV8关键点检测-训练自己的关键点检测模型

https://www.bilibili.com/video/BV13a4y157HE

在自己标注的三角板关键点检测数据集上，训练YOLOV8关键点检测深度学习算法，得到模型权重文件。下载样例数据集，介绍训练命令行参数，微调（Fine Tuning）和从头重新训练（From Scratch）两种迁移学习训练方式，并给出训练样例代码，使用wandb对训练过程可视化。分析模型输出结果，可视化标签分布、损失函数、测试集评估指标。

## YOLOV8关键点检测-用训练得到的新模型预测图像、视频、摄像头画面

https://www.bilibili.com/video/BV1Lo4y1t76s

用上一讲训练得到的关键点检测YOLOV8模型，分别对单张图像、视频文件、摄像头实时画面，运行推理预测。通过命令行、Python API两种方式，获得预测结果，并可视化预测结果。

## YOLOV8关键点检测-部署

## RTMPose训练关键点检测算法

## 关键点检测微信答疑交流群

**免费群**：加入开源算法库MMPose/MMHuman3D交流群：添加喵喵小助手微信：OpenMMLabwx，回复“子豪兄三角板”

进群后发暗号“子豪兄关键点检测毕设”，同济子豪兄和众多Pose大佬在群里等你~

**付费群**：公众号 人工智能小技巧 回复 关键点检测毕设：代码bug救急、论文创新点辅导、模型部署软件开发：APP、微信小程序、网页、硬件、服务器部署





