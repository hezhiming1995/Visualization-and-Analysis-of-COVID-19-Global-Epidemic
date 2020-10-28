# 基于Excel的 COVID-19 全球疫情可视化与分析

简体中文 | [English](README.en.md)

#### 日期: 2020年10月24日
#### 作者: 何志明
---

## 一、明确目标：
1. 中韩美三国的每日确诊、治愈、死亡人数变化趋势是如何？
2. 能否基于**中国和世界地图**绘制疫情累计确诊人数严重程度？
3. 能否基于目前的数据对中韩美三国**未来**一个月的疫情发展进行**预测**分析（采用95%的置信区间）？
4. 能否分析七大洲的**死亡率**和**治愈率**情况？
5. 能否对于七大洲**确诊人数占比**进行分析？
6. 能否根据**时间序列**，争对每一个时间段的全球**TOP10国家**疫情情况进行展示？
7. 能否基于现有数据，分析COVID-19的**传播性和致死率**？

## 二、数据采集和存储：
1. 数据来源于[BlankerL/DXY-COVID-19-Data](https://github.com/BlankerL/DXY-COVID-19-Data#2019%E6%96%B0%E5%9E%8B%E5%86%A0%E7%8A%B6%E7%97%85%E6%AF%92%E7%96%AB%E6%83%85%E6%97%B6%E9%97%B4%E5%BA%8F%E5%88%97%E6%95%B0%E6%8D%AE%E4%BB%93%E5%BA%93)项目于**11月23日**推送的[Release](https://github.com/BlankerL/DXY-COVID-19-Data/releases/tag/2020.10.23)；
2. 数据仅从丁香园公开的数据中爬虫获取并存储于csv文件中；
3. 疫情统计起始于2020年1月22日，终止于2020年10月22日，共19个字段，328609条记录，大小约为34.9MB。

## 三、数据理解和清洗：
1. 采用数据透视表进行简单的处理和分析；
2. 自行补全缺漏数据。

## 四、数据分析：
1. 中韩美新冠病毒每日确诊、治愈及死亡人数变化趋势：

 ![image](./Visualization%20of%20Results/1.1%20中国新冠病毒每日确诊、治愈及死亡人数变化趋势.png)

  ![image](./Visualization%20of%20Results/1.2%20韩国新冠病毒每日确诊、治愈及死亡人数变化趋势.png)

 ![image](./Visualization%20of%20Results/1.3%20美国新冠病毒每日确诊、治愈及死亡人数变化趋势.png)

2. 全国及全球新冠肺炎疫情地图（累计确诊人数）：

![image](./Visualization%20of%20Results/2.1%20全球新冠肺炎疫情地图（累计确诊人数）.png)

![image](./Visualization%20of%20Results/2.2%20中国新冠肺炎疫情地图（累计确诊人数）.png)


3. 中韩美三国疫情确诊人数的预测分析（95%置信区间）：

![image](./Visualization%20of%20Results/3.1%20韩国疫情确诊人数的预测分析（95%25置信区间）.png)

![image](./Visualization%20of%20Results/3.2%20美国疫情确诊人数的预测分析（95%25置信区间）.png)

![image](./Visualization%20of%20Results/3.3%20中国疫情确诊人数的预测分析（95%25置信区间）.png)


4. 六大洲的死亡率、治愈率及确诊人数占比分析：

![image](./Visualization%20of%20Results/4.1%20六大洲的死亡率和治愈率分析.png)

![image](./Visualization%20of%20Results/4.2%20六大洲确诊人数分析.png)

5. 1月至10月全球TOP10疫情国家变化图：

![image](./Visualization%20of%20Results/5.1%201月至10月全球TOP10疫情国家变化图.png)

![image](./Visualization%20of%20Results/5.2%20月至10月全球TOP10疫情国家变化图2.png)

6. 2020新型冠状肺炎传播性与致死率分析：

![image](./Visualization%20of%20Results/6.%202020新型冠状肺炎传播性与致死率分析.png)


