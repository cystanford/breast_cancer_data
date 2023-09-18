# breast cancer data analysis

## setup-env

```python
conda env create -f environment.yml

# conda active sklearn-env
```

## data description

后缀的代表意义：

* mean：平均值
* se：标准差
* worst：最大值

字段意义

|          字段          |                含义                |
| :--------------------: | :---------------------------------: |
|       diagnosis       |       M/B（M: 恶性，B:良性）       |
|      radius_mean      |  半径（点中心到边缘的距离）平均值  |
|      texture_mean      |    纹理（灰度值的标准差）平均值    |
|     perimeter_mean     |             周长平均值             |
|       area_mean       |             面积平均值             |
|    smoothness_mean    |  平滑度（半径内的局部变化）平均值  |
|    compactness_mean    | 紧密度（=周长*周长/面积-1.0）平均值 |
|     concavity_mean     |  凹度（轮廓凹度的严重程度）平均值  |
|  concave_points_mean  |     凹缝（轮廓的凹部分）平均值     |
|     symmetry_mean     |            对称性平均值            |
| fractal_dimension_mean |   分形维数（=海岸线近似-1）平均值   |

## step

准备阶段

* 数据清洗
* * 数据探索
  * 数据获取
* 特征选择

分类阶段

* 模型训练
* 模型评估
