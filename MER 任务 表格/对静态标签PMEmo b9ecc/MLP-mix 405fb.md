# MLP-mix

备注: 对随机抽取的20s频谱使用整首歌的标签进行预测,划分：train_percent=0.8, valid_percent=0.1，
test_percent=0.1
复现人: Peilin Li
结果: RMSE(A/V) = 
0.2452/0.3002
超参数: "BATCH_SIZE": 64,
"EMBEDDING_DIM": 256,
"CHANNEL_DIM": 256,
"TOKEN_DIM": 128,
"PATCH_SIZE": 16,
"RESNET_DEPTH": 48,
"LEARNING_RATE": 1E-5,
"EPOCH_NUM": 100,//
"BATCH_SIZE": 64,
"EMBEDDING_DIM": 128,
"CHANNEL_DIM": 128,
"TOKEN_DIM": 128,
"PATCH_SIZE": 16,
"RESNET_DEPTH": 64,
"LEARNING_RATE": 1E-5,
"EPOCH_NUM": 100,