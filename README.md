### 1.设计要求

1. 尺寸，这个东西的尺寸的样子(30.50mm孔距)
   ![](image/README/1698769233077.png)
2. 电源输入: 4S-6S
3. 电源输出:
   1. 直出/45A 四路
   2. 12V/5A 一路
   3. 5V/5A 一路
4. 将PMU相关的东西进行集成
5. PMU本身应该是既有I2C通讯的，又有模拟量通讯的，只需要模拟量就可以

### 2.验证方法和测试代码




### 3.可能发生的最坏的事情，

1. 12V转压故障，导致12V直出电源电压烧坏后级电脑、无人机炸机
