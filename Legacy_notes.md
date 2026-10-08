#Summer 2026 Legacy Experiment
##what I have tried?
使用ZAugNet的源代码，并让Codex修改以支持CT数据

##what I changed
目前已知
CT数据的性质，包括像素，如何成像以及与显微镜成像的相同与不同。
数据类型：DICOM
研究方向以及研究方法
image size
batch size
epoch
loss


##what happened?
Codex直接给的模型可以训练
单epoch的时间很长
总训练预计时间有10小时左右
不理解代码

##what I do not know
数据读取方式
normalization
training config:
为什么训练慢
不知道对CT数据的处理是否正确
normalization是否合理
数据triplet是否合理
模型是否具有泛化作用
是否真正适用于CT影像
效果差是来自于数据还是模型
神经网络
数据预处理
模型流程
