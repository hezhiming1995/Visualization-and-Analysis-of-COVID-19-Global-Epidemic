# COVID-19全球疫情可视化与分析
 Visualization-and-Analysis-of-COVID-19-Global-Epidemic | 基于Excel、Python、Tableau 工具分析 | 33万条丁香园采集数据）

简体中文 | [English](README.en.md)

#### 日期: 2020年10月27日
#### 作者: 何志明
---

## 数据说明：
1. 数据来源于[BlankerL/DXY-COVID-19-Data](https://github.com/BlankerL/DXY-COVID-19-Data#2019%E6%96%B0%E5%9E%8B%E5%86%A0%E7%8A%B6%E7%97%85%E6%AF%92%E7%96%AB%E6%83%85%E6%97%B6%E9%97%B4%E5%BA%8F%E5%88%97%E6%95%B0%E6%8D%AE%E4%BB%93%E5%BA%93)项目于**11月23日**推送的[Release](https://github.com/BlankerL/DXY-COVID-19-Data/releases/tag/2020.10.23)。
2. 数据仅从丁香园公开的数据中爬虫获取并存储于csv文件中。
3. 疫情统计起始于2020年1月22日，终止于2020年10月22日，共计19个字段，328609条记录，大小约为34.9MB。
4. 原始数据并为进行简单清洗和排查，存在重复统计以及异常值的情况。
5. 感谢[Blanker](https://github.com/BlankerL)提供的公开数据源！

## 内容：
1. 分别基于Excel、Python、Tableau三种分析工具进行 COVID-19 全球疫情的可视化与分析；
2. 争对于基于时间及地区的疫情变化趋势和严重程度进行了可视化分析；
3. 争对于中韩美三国累计确诊人数的一个月（截至到11月22日）的预测分析；
4. 争对于所有国家感染人数和死亡率分析了COVID-19的传播性与致死率；
5. 争对使用每一个分析工具分析过程中所遇到的困难或问题都会记录；
6. ++ 待补充。++

## 研究过程
1. **明确目标**：三个分析工具都有相同和不同的研究目标；
2. **数据采集及存储**：以上已说明来源及存储形式；
3. **数据理解及清洗**：此步骤三个分析过程基本统一；
4. **数据分析**：描述性分析和推论性分析
5. **结论展示**：数据可视化与结论分析


---



### 预测趋势结论较为准确的主要原因：
1. **目前的数据足够准确且庞大全面**，未知的影响因素较少，不管是指数型还是线性型回归曲线贴近于实际变化趋势，R^2^ 值也极度贴近于1。
2. **疫情的持续时间足够**，时间序列连贯，数据充足且真实，趋势变化的程度也足够平稳，有利于指数平滑算法推演。
3. **外界干扰因素少或影响因子小**，不同于疫情刚开始爆发时，特殊应对政策（佩戴口罩、医疗设施调配、交通航班管制和居家隔离等等）对于疫情走势影响极大，目前全球各国的疫情应对措施基本确定，且各国的疫情发展阶段基本进入了发展期或积累期阶段，中国更是已经进入了平稳期阶段。


### 三个分析工具的优势与局限性：
#### Excel 优势：
1. 利于无编程经验的人员，功能及工具；
2. 客户群体庞大；
3. 数据透视表对于数据的筛选分类展示极为方便；
4. 处理30万条记录依旧不在高效（一开始我以为会很慢）。

#### Excel 劣势：
1. 分析过程不可复现；
2. 功能过于庞大；
3. 对于动态可视化较为麻烦，细节把握不足；
4. 不适配机器学习。


#### Python 优势：
1. 更为高效的效率和性能；
2. 处理大数据真的真的毫无压力；
3. 扩展性足够好，科学工具包真的可以免除很多复杂繁琐的过程。

#### Python 劣势：


#### Tableau 优势：

#### Tableau 劣势：