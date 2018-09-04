### 中国LEED认证项目统计  
---
author: "Askka"
date: "2018年8月31日"

---
#### 概要    
　　由美国绿色建筑协会(USGBC：U.S. Green Building Council)建立并推行的《绿色建筑评估体系》**LEED**(Leadership in Energy and Environmental Design)认证，被认为是是目前在世界各国的各类建筑环保评估、绿色建筑评估以及建筑可持续性评估标准中最为完善也最有影响力的评估标准。自1998年推出LEED 1.0版本的试验性计划（Pilot Program）至今，全世界范围内已有167个国家和地区的近7万个项目取得LEED认证。    
　　自2005年7月国内首个项目获LEED认证至今，中国已成为了LEED项目认证数量全球排名第二的国家，仅次于美国。由于LEED认证现阶段仍以项目开发单位经济性激励及鼓励性申报，而非强制性申报；加之作为绿色建筑认证势必带来项目一次投资的增加，因此希望通过逐年汇总中国各省（包括港澳台）的LEED认证数量，考察国内绿色建筑的热度以及LEED认证申报与区域经济发展之间的联系等。  

#### 设计    
　　从[USGBC网站](https://www.usgbc.org/sites/default/files/data/PublicLEEDProjectDirectory.xls)下载LEED认证项目数据库，利用R进行数据清洗整理后得到了所有中国的LEED认证项目信息。主要的数据整理分析的工作在《数据分析（进阶）》"项目二：项目准备”中完成的，此次主要完成数据可视化部分工作。  
    设计之初本拟采用D3绘制GeoJson/TopoJson地图并实现按LEED逐年认证数量填充色阶，但由于GeoJson格式文件中大陆、香港澳门与台湾都有差别，以致于要绘制准确的GeoJson中国地图，更多的精力花在了地图文件的清理上，有悖于此次数据可视化设计任务的初衷。因此后期利用Echart调用加之数据文件实现。  
#### 反馈    
　　对JavaScript并不熟悉，更多的图形化经验来自于前期利用R、ggplot的经历；设计更多等参考了Echart官方实例。总之就是新学后进，希望各位多提宝贵意见。    
#### 资源    
    1. [Echart教程](http://echarts.baidu.com/tutorial.html#5%20%E5%88%86%E9%92%9F%E4%B8%8A%E6%89%8B%20ECharts)    
    1. ["Life Expectancy and GDP"实例](http://echarts.baidu.com/examples/editor.html?c=scatter-life-expectancy-timeline)
    1. ["Air Quality - Baidu Map"实例](http://echarts.baidu.com/examples/editor.html?c=effectScatter-bmap) 
    1. [USGBC: Top 10 Countries for LEED(2014)](http://plus.usgbc.org/top-10-countries/)
    1. 项目2学习报告：LEED Projects Analysysa