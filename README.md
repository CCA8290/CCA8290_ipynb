# ipynb notebook的保存
## 简介
创建于2020年9月17日，用于记录学习过程中编写的或copy的ipynb文件，以供自己复习。
## 文件说明
+ `iris_pytorch_200824`    

用熟悉的鸢尾花(iris)数据集来学习Pytorch，包括简单神经网络的不同搭建方法。利用Pytorch实现神经网络时，要注意：    

	>1. numpy和tensor的互化
	>2. 数据类型的转化，包括numpy的int32、float64等，注意numpy中`astype()`的用法。
	>3. 注意conv接收的数据为4维：`batch, channel, H, W`，维度的增加和减少要记住`squeeze()`和`unsqueeze()`的用法，改变tensor尺寸要熟悉`view()`的用法。
+ `TorchTensor学习+AdderNet_20200814`   

假期对torch的简单回顾，包括CVPR2020上AdderNet论文的尝试。这个notebook中要注意，想要手动定义卷积核，可以使用`torch.nn.functional`中的`conv2d()`，它和`torch.nn`中的`Conv2d`不太一样，注意区别功能和函数名的大小写。
