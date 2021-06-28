# Multi-gateSSM
Basic code of SSM method based on multi-gate

主要依赖库版本:
====
###     tensorflow==2.1.0
###     keras==2.3.1
###     h5py==2.10.0

文件说明：
====
###     1_ROI2Patches 基于样本点生成的roi影像采集样本集patches。 
###     2_divideDataset 数据集划分
###     3_Training 模型训练（包括全监督和多门控SSM）
###     4_getMap 大图切分为子图预测与预测结果拼接为大图并保存结果。
