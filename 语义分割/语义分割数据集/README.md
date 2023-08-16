# 同济子豪兄开源的语义分割数据集

同济子豪兄 2023-6-9

## 数据集使用说明

下列数据集仅可免费用于非盈利用途，使用时需注明出处“B站同济子豪兄”。

因华为云OBS存储、上传、下载皆有成本，每次下载和使用数据集，请自觉转5元至支付宝407431120@qq.com

如需商业用途（例如商业机构课程），请B站私信同济子豪兄，获得书面授权。

## 西瓜瓤-西瓜籽语义分割数据集

标注：张子豪（同济子豪兄）

共87张图像

![西瓜语义分割Labelme标注](https://zihao-openmmlab.obs.cn-east-3.myhuaweicloud.com/20230130-mmseg/dataset/watermelon/meta/watermelon_labelme1.jpg)

![西瓜语义分割Mask标注](https://zihao-openmmlab.obs.cn-east-3.myhuaweicloud.com/20230130-mmseg/dataset/watermelon/meta/watermelon2.jpg)

| 类别名称   | 类别语义 | 标注类别          | 灰度图像素值 |
| ---------- | -------- | ----------------- | ------------ |
| /          | 背景     | /                 | 0            |
| red        | 西瓜红瓤 | 多段线（polygon） | 1            |
| green      | 西瓜外壳 | 多段线（polygon） | 2            |
| white      | 西瓜白皮 | 多段线（polygon） | 3            |
| seed-black | 西瓜黑籽 | 多段线（polygon） | 4            |
| seed-white | 西瓜白籽 | 多段线（polygon） | 5            |

Labelme标注格式（没有划分训练集和测试集）：https://zihao-openmmlab.obs.cn-east-3.myhuaweicloud.com/20230130-mmseg/dataset/watermelon/Watermelon87_Semantic_Seg_Labelme.zip

Mask标注格式（已划分训练集和测试集）：https://zihao-openmmlab.obs.cn-east-3.myhuaweicloud.com/20230130-mmseg/dataset/watermelon/Watermelon87_Semantic_Seg_Mask.zip

## 手部、耳朵、足部、躯干、背部语义分割数据集

请联系子豪兄助理小田，微信号：T20220117
