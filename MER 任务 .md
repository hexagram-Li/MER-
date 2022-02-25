# MER 任务

任务描述：给定一首歌曲，预测这首歌曲的Arousal和Valence值（0~1）

数据集：PMEmo（1000songs待添加）

数据准备：@毅威 丁 用的是PMEmo官方提供的动态feature，给出了从每0.5s歌曲的特征向量（260维），为了控制输入大小相同，不足20s的歌曲zero-padding到20s，超过20s的歌曲随机截取20s，将V-A值归一化到-1~1（×2 - 1）；@Peilin Li 提取了mp3文件的频谱图

评估指标：每首歌的MSE Loss或RMSE值取平均 （TODO：测试集长度不定问题）

[MER 模型调研](MER%20%E4%BB%BB%E5%8A%A1%20a299d/MER%20%E6%A8%A1%E5%9E%8B%E8%B0%83%E7%A0%94%2026796.csv)

[MER 数据集](MER%20%E4%BB%BB%E5%8A%A1%20a299d/MER%20%E6%95%B0%E6%8D%AE%E9%9B%86%20a1c49.csv)

项目地址：

[GitHub - suncerock/music-emotion-recognition](https://github.com/suncerock/music-emotion-recognition/)

# 实验记录

[对静态标签PMEmo数据集的预测模型超参及实验结果](MER%20%E4%BB%BB%E5%8A%A1%20a299d/%E5%AF%B9%E9%9D%99%E6%80%81%E6%A0%87%E7%AD%BEPMEmo%20b9ecc.csv)