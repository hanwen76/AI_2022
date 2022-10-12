## Basic Paper List
- AlexNet
- ResNet
- Transformer
- *YOLO
## Reflex-based and Stated-based
Reflex-based models are too simple for tasks that require more forethought.
- Reflex Example: NN/linear model
- Stated Example: translation/search problem/Markov
## Share:*PARROT
## Share:Knowledge Distillation
知识蒸馏的最简单形式是在具有软目标分布的传递集上训练蒸馏模型。到目前为止,我们应该知道有两个目标用于训练学生模型。一个是正确的标签(硬目标),另一个是从教师网络生成的软标签(软目标)。因此,目标函数是两个不同目标函数的加权平均值。 第一个目标函数是学生预测和软目标之间的交叉熵损失,第二个目标函数是学生输出和正确标签之间的交叉熵损失。最好的结果通常是通过在第二目标函数上使用较低的权重来获得的。
## Code Homework
- GAN
生成器&对抗器
- Clip
模型的输入是图片和文字的配对，图片输入到图片的encoder得到一些特征，文本输入到文本的encoder得到一些特征，每个traning batch里有n个图片-文本对，就能得到n个图片的特征和n个文本的特征，然后在这些特征上做对比学习，对比学习非常灵活，就需要正样本和负样本的定义，其它都是正常套路，配对的图片-文本对就是正样本，描述的是同一个东西，特征矩阵里对角线上的都是正样本，矩阵中非对角线上的元素都是负样本，n个正样本， 其余负样本，有了正负样本，模型就可以通过对比学习的方式去训练了，不需要任何手工标注。这种无监督的训练方式，是需要大量的训练数据的。
- VIT
ViT是2020年Google团队提出的将Transformer应用在图像分类的模型。
- Diffusion model
纯噪音-逆向扩散-原图片（目标图片）step by step
- MAE
MAE的做法是：随机遮盖输入图片的子块，然后重建丢失像素。其核心设计为：非对称的编码-解码架构；高比例mask情况下的自监督。在下游任务中使用Encoder 部分作为 backbone 取得了非常显著的性能提升。
## Paper reading Homework
- Agent
- Search
- Markov Decision Processes
- Bayesian Network
- Reinforcement Learning
## variable-based models
- constarint satisfaction problems (e.g. Sudoku,scheduling)
- Bayesian networks -- soft dependencies 
## Logit
- Digest heterogenous information & Reason deeply with that information