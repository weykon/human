https://scikit-learn.org/stable/getting_started.html

细说此处，这里是最基本的过程，而看着文字，不去感受数据的情况，每次都是同样的代码去解析数据的话，根本没有味道。

相当于一盘菜永远的的放在那里，从来不去尝，舌头天天干放在嘴里，永远不知道什么美食。


Fitting and predicting: estimator basics （ 拟合和预测：估计器基础知识 ）

Transformers and pre-processors ( 变压器和预处理器 )

Pipelines: chaining pre-processors and estimators ( 管道：链接预处理器和估计器 )

Model evaluation ( 模型评估 ) 

Automatic parameter searches ( 自动参数搜索 )


--- 

基本: 

MSE （通常处理于回归问题）  
```latex
\text{MSE}(y, \hat{y}) = \frac{\sum_{i=0}^{N - 1} (y_i - \hat{y}_i)^2}{N}
```

$$ \text{MSE}(y, \hat{y}) = \frac{\sum_{i=0}^{N - 1} (y_i - \hat{y}_i)^2}{N} $$

Cross-Entropy Loss （通常处理于分类问题）  
```latex
\text{CE}(y, \hat{y}) = -\frac{1}{n}\sum_{i=1}^{n} \left[y_i\log(\hat{y}_i) + (1-y_i)\log(1-\hat{y}_i)\right]
```   
 
$$ \text{CE}(y, \hat{y}) = -\frac{1}{n}\sum_{i=1}^{n} \left[y_i\log(\hat{y}_i) + (1-y_i)\log(1-\hat{y}_i)\right]
 $$
