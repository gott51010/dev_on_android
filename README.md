# paddle-mobile
基于paddle-mobile的安卓部署


## paddle-mobile的预训练模型进行照片分类的应用.


### 主要类说明

``` java
 /**
 * 描述一个模型的 预处理, 加载, 以及预测等特性
 * 封装了与paddle mobile - PML 交互过程 
 */
abstract class Model : IModel, AnkoLogger{}

/**
 * MobileNetModelImpl 描述了一个modelnet分类模型
 * 包含预处理,模型加载,预测过程等
 **/
class MobileNetModelImpl : Model() {}

/**
 * DEMO的界面, 创建与调用Model对象,
 */
class MainActivity : Activity(){}

```

#### 后续更新
不知道TensorFlow lite可不可以用相同方法编译
看起来模型编译完是独立的,我猜不同框架不会打架
and 最近更新了yolov3模型 据说更快 想白嫖

#### 终章
等我的iphone12到货了我可能就不会再玩这个项目了...
安卓太难了...我不配...
