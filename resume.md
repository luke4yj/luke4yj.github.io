
# 个人信息

 - 本科/xxx大学计算机系
 - 工作年限：满2年

 - 期望职位：图像识别，深度学习
 - 期望薪资：税前月薪20k~30k，特别喜欢的公司可例外
 - 期望城市：广州，深圳


# 工作经历
## xxxxx公司 （ 2018年 ~ 至今 ）

- 负责自动驾驶场景图像数据采集、数据筛选；
- 负责公司xx(产品)上算法模块的研发，如目标检测、语义分割等算法的设计、训练、测试；
- 负责模型算法在嵌入式平台上集成、性能优化；
- 追踪最新的处理技术，关注业界前沿，优化平台算法

# 项目经历
### 深度学习模型集成

* 将已有的目标检测模型和车道线检测模型集成到嵌入式平台上，保证性能的高效性
* 职责：

  1、对前处理resize部分进行加速，依次运行两个算法模型；
  
  2、多线程处理车道线拟合和跟踪部分；
  
  3、对车道线检测结果和目标检测结果进行数据融合
  

### 多目标夜间检测算法
* 该模块通过深度学习算法来进行夜间的车辆、行人和地面标识识别，主要用于ADAS辅助驾驶
* 职责：

  1、收集产品需求，制定训练样本采集标准和标注标准；
  
  2、使用深度学习算法进行检测，主要采用YoloV3、Multi-Scale Training、Data augmentation等tricks来获取较高的检测精度；
  
  3、保证相同精度情况下压缩算力，主要参考Inception、MobileNet、residual block、降维等方法，在xx平台上的帧率达到20 fps；
  
  4、跟踪算法实测效果及反馈，并进行优化


### 基于深度学习的交通标牌识别

* 识别道路上各种交通标识的含义，如限速50、禁止驶入等
* 职责：

  1、收集有关交通标识的数据集；
  
  2、设计网络结构，主要参考ResNet，并用Tensorflow来实现；
  
  3、测试
  
  
# 技能清单
- 熟悉SSD、Yolo等目标检测算法；熟悉caffe、TensorFlow、darknet框架，能进行相关项目研发；
- 熟悉C/C++/Python编程，有扎实的代码功底和实战能力；
      