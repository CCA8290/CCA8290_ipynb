# ipynb notebook的保存
## 简介
创建于2020年9月17日，用于记录学习过程中编写的或copy的ipynb文件，以供自己复习。
## 文件说明
+ `iris_pytorch_200824`    

用熟悉的鸢尾花(iris)数据集来学习Pytorch，包括简单神经网络的不同搭建方法。利用Pytorch实现神经网络时，要注意：    

	 1. numpy和tensor的互化
	 2. 数据类型的转化，包括numpy的int32、float64等，注意numpy中astype()的用法。
	 3. 注意conv接收的数据为4维：batch, channel, H, W，维度的增加和减少要记住squeeze()和unsqueeze()的用法，改变tensor尺寸要熟悉view()的用法。
+ `TorchTensor学习+AdderNet_20200814`   

假期对torch的简单回顾，包括CVPR2020上AdderNet论文的尝试。这个notebook中要注意，想要手动定义卷积核，可以使用torch.nn.functional中的conv2d()，它和torch.nn中的Conv2d不太一样，注意区别功能和函数名的大小写。

+ `GD_iris_20200918.ipynb`    
借助iris数据集对几种常见的梯度学习进行对比。

+ `mnist.ipynb`
这个notebook主要用来：   
	- 学习pytorch训练模型
	- 学习dataloader方法和ImageFolder方法，后者主要用于从图片加载数据集
	- 学习如何迭代读取数据训练模型
	- 学习tensorboard的使用
	- 学习常见的transforms图像增强方法


