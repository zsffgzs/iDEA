# iDEA一款用于数据包络分析SBM模型的新软件


**<font face="华文行楷"  font size=6>软件引用说明</font>**   
 ------------------------------------------------------------ 
```
示例：  
    本文利用iDEA4.1[1]软件采用非导向、规模报酬不变的全局超效率SBM模型对某省农业用水效率进行测算。
参考文献
[1] ZSFFGZS.iDEA一款用于数据包络分析SBM模型的新软件[EB/OL].[2022-xx-xx].https://github.com/zsffgzs/iDEA.
```
```
※※※其中[2022-XX-XX]需要修改为你引用的时间※※※
```

#### &emsp;&emsp;经过淘宝**知识付费工作室【<font color=red>ZSFFGZS</font>**】的持续努力，一款功能齐全、操作简单、计算准确的SBM模型软件终于正式发布！这便是【**<font color=red>iDEA</font>**】，<font color=#FF00FF>**当前版本4.1**</font>。
#### 注意：不建议数据中有负数和0，数据有负数和0时结果可能有错误。

```
更新日志：
【20230202】
新增苹果电脑M系列处理器支持
【20230122】
增加了投入产出指标名称提示
【20220730】
1.增加了MaxDEA软件中前沿代理点方法(FPA)功能，可以处理选择投入/产出导向时部分无解的情况
2.优化了全局效率值的测算，更新后无需手动对时间和DMU进行重新定义
```
#### **iDEA**目前主要用于SBM模型的计算，支持下列模型：


## 【效率模型】
### 【同时支持CRS及VRS,可以计算TE、PTE、SE】

```
1.投入导向SBM模型
2.产出导向SBM模型
3.非导向SBM模型
4.含非期望产出的投入导向SBM模型
5.含非期望产出的产出导向SBM模型
6.含非期望产出的非导向SBM模型
7.投入导向超效率SBM模型
8.产出导向超效率SBM模型
9.非导向超效率SBM模型
10.含非期望产出的投入导向超效率SBM模型
11.含非期望产出的产出导向超效率SBM模型
12.含非期望产出的非导向超效率SBM模型
```
## 【指数模型】
### 【同时支持CRS及VRS,可以计算effch、techch、pech、sech、tfpch】
```
13.投入导向SBM-Malmquist模型
14.产出导向SBM-Malmquist模型
15.非导向SBM-Malmquist模型
16.投入导向SBM-Malmquist-Luenberger模型（相邻参比SBM-ML)
17.产出导向SBM-Malmquist-Luenberger模型（相邻参比SBM-ML)
18.非导向SBM-Malmquist-Luenberger模型（相邻参比SBM-ML)
19.投入导向超效率SBM-Malmquist-Luenberger模型（相邻参比超效率SBM-ML)
20.产出导向超效率SBM-Malmquist-Luenberger模型（相邻参比超效率SBM-ML)
21.非导向超效率SBM-Malmquist-Luenberger模型（相邻参比超效率SBM-ML)
22.投入导向SBM-Global-Malmquist-Luenberger模型（SBM-GML)
23.产出导向SBM-Global-Malmquist-Luenberger模型（SBM-GML)
24.非导向SBM-Global-Malmquist-Luenberger模型（SBM-GML)
25.投入导向超效率SBM-Global-Malmquist-Luenberger模型（超效率SBM-GML)
26.产出导向超效率SBM-Global-Malmquist-Luenberger模型（超效率SBM-GML)
27.非导向超效率SBM-Global-Malmquist-Luenberger模型（超效率SBM-GML) 
```
## 【常用公式】
![当期、标准、投入导向](https://raw.githubusercontents.com/zsffgzs/iDEA/main/%E5%BD%93%E6%9C%9F%E6%A0%87%E5%87%86%E6%8A%95%E5%85%A5.png)
![当期、标准、产出导向](https://raw.githubusercontents.com/zsffgzs/iDEA/main/%E5%BD%93%E6%9C%9F%E6%A0%87%E5%87%86%E4%BA%A7%E5%87%BA.png)
![当期、标准、非导向](https://raw.githubusercontents.com/zsffgzs/iDEA/main/当期标准非.png)
![当期、标准、非导向、非期望产出](https://raw.githubusercontents.com/zsffgzs/iDEA/main/当期标准非非期望.png)
![全局、标准、非导向、非期望产出](https://raw.githubusercontents.com/zsffgzs/iDEA/main/全局标准非非期望.png)
![全局、超效率、非导向、非期望产出](https://raw.githubusercontents.com/zsffgzs/iDEA/main/全局超效率非非期望.png)

<font face="宋体"  font size=3>参考文献：</font><br />
<font face="宋体"  font size=3>[1] 成刚.数据包络分析方法与MaxDEA软件[M].北京:知识产权出版社,2014.</font><br />
<font face="宋体"  font size=3>[2] http://lpsolve.sourceforge.net/5.5/</font><br />
<font face="宋体"  font size=3>[3] https://www.python.org/</font><br />
<font face="宋体"  font size=3>[4] https://www.numpy.org/</font><br />
<font face="宋体"  font size=3>[5] https://pandas.pydata.org/</font><br />

