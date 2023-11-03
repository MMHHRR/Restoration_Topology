1. total_feature.csv里面包含
	1.1 浅层视觉数据（颜色、边缘）——OpenCV
	1.2 情感数据（六维度情感）——yaoyao的包
	1.3 语义分割数据——MaskFomer150类（Meta预训练模型）
	1.4 物体检测数据——DETR推理100类（微软预训练模型）
2. poi和房价数据（gis计算）
3. spatial_embedding.csv数据由同一街道的多张街景通过GCN编码完成（5维度）