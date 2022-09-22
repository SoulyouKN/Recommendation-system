## 推荐系统实例
#### 目录
* 基于协同过滤(UserCF)的模型
* 基于隐语义(LFM)的模型
* 基于图(PersonalRank)的模型

#### 快速开始
数据集:http://grouplens.org/datasets/movielens/1m
解压到data/目录中

* 数据预处理

    python manage.py preprocess

* 模型运行

    python manage.py [cf/lfm/prank]
