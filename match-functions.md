# nb for all match fns

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
