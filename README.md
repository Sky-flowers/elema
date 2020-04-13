# 代码数据来源阿里云天池-智慧物流：新冠期间饿了么骑士行为预估比赛，比赛链接：
 <!-- https://tianchi.aliyun.com/competition/entrance/231777/introduction -->

# author：@Sky_flowers qq:1220593475
# 参考：@第一次打比赛啊-基于机器学习的 baseline 分享，线上 0.68
 <!-- https://tianchi.aliyun.com/forum/postDetail?spm=5176.12586969.1002.3.1f7f48c84T9Urx&postId=97632 -->

# 总述
<!-- 
 lgb版本2.3.2
 全部代码在main.ipynb中，更新代码也是更新这个
 调参暂时还没做，看情况
 整体框架和建模相关代码基本来源于 @第一次打比赛啊
 数据读取部分依据 @第一次打比赛啊 进行了重写，很多特征直接在数据读取的时候方便就构造了 -->

# 初步数据处理
 ## 数据的读取
 ## 数据处理、清洗、特征工程
 ## 特征工程小结

# 分类任务
 ## 分类任务特征工程
 ## lightGBM建模
 ## 分类任务的输出

# 回归任务
 ## 分类任务输出文件的导入
 ## 回归任务的特征工程
 ## lightGBM建模
 ## 输出最终结果

# 剩余未构造特征
 <!-- 
 grid_distance排序
 last_speed特征提取
 剩余最短距离特征 -->