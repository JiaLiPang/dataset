# 数据集共享
## citeseer数据集
### 链接
https://www.kaggle.com/shichenyang/citeseer
### 描述
citeseer记录了论文之间引用或被引用信息。  
该数据集包括两个文件：edges.csv和nodes.csv。edges.csv存储网络的边信息，包括字段souce，target，分别代表源节点id和目标节点id。nodes.csv存储网络的节点信息，包括字段nodeID和label，分别代表节点id和对应的节点标签。
### 属性
|属性|值|
|----|-----|
|类型|有向|
|节点数|2110|
|边数|3720|
|标签数|6|
|平均度|3.52|
  
# 数据集共享
## Epinions, Slashdot, Wikipedia数据集（节点ID处理过）
### 链接
https://www.kaggle.com/joricvansprings/jorics-signed-networks
### 描述
有正负符号的社会网络数据集。  
每个网络有source,target,weight属性，分别代表起点，终点，正负性（1代表正，-1代表负）
### 属性
|属性|值|
|----|-----|
|网络|Epinions|Slashdot|Wikipedia|
|类型|有向|有向|有向|
|节点数|131828|82140|7118|
|总边数|841372|549202|103747|
|负边数|123705|124130|22497|
|平均度|6.38|6.69|14.58|
