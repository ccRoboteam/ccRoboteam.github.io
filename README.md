# ccRoboteam.github.io
### **『------课题组简介------』**

<table border="0">
  <tr>
    <td width="100%" align="center">
     <img src="/APET2022.png" width="70%">                   #这地方是照片，照片上传到同一目录
    </td>
  </tr>
</table>

➤ 课题组主要从事机器人控制技术的研究，原主要研究多自由度柔性关节机器人奇异摄动控制若干问题。后续又在原来的动力学框架下，围绕柔性关节机器人未知状态的滤波观测、反步和滑模控制、神经网络非线性拟合以及柔性和刚性关节混合联动机器人的虚拟分解控制进行了较深入的研究。
➤ 现主要研究方向为基于深度强化学习的冗余自由度机器人运动规划及优化若干问题。从冗余自由度机器人对象出发，聚焦于其面向一般连续多工步作业的深度强化学习范式、运动规划及优化框架、虚实系统的容差训练机制，成果应用可望扩展至任意几何结构的机器人对象，并对其它类似复杂作业极具借鉴意义。

--------
### **『------课题组指导老师------』**
 [**刘华山老师个人主页**](https://web.dhu.edu.cn/cist/39/1a/c20589a145690/page.htm)

<table border="0">
  <tr>
    <td width="65%">
      <h1>刘华山</h1>
      <p><b>副教授、副院长、硕士生导师</b></p>
      <p><b>信息科学与技术学院</b></p>
      <p><b>东华大学 (211, 双一流)</b></p>
      <p><b>中国上海松江区</b></p>
      <p><b>邮箱：hsliu@dhu.edu.cn</b></p>
    </td>
    <td width="35%">
      <img src="/me.jpg" width="100%">                      #放老师照片
    </td>
  </tr>
</table>

### **『------课题组近期研究成果------』**

➤ ** 融合熵自调整的深度强化学习无模型运动规划及双重优化框架**: 

该泛化框架适用于包括冗余自由度机器人在内的任意几何结构的机器人运动规划及优化。其包含两个模块：深度强化学习与传统路径规划方法相结合的融合式长度最优路径规划模块；深度强化学习与深度人工神经网络相结合的三层式能量最优逆运动学求解模块。后者的上层和中层分别由融合熵自调整的深度强化学习完成机器人在给定路径下的姿态自调整和探索能量最优逆运动学解，下层基于深度人工神经网络高效执行无模型逆运动学求解计算。<table border="0">
  <tr>
    <td width="50%">
      <img src="/Microgrid.png" width="100%"> 
    </td>
    <td width="50%">
      <img src="/ParallelDGs.png" width="100%"> 
    </td>
  </tr>
</table>

➤ **位姿自主协同的分层嵌套式多策略智能体连续多过程学习范式**: 

该面向连续多工步任务的创新性学习范式分为两层：可根据环境状态学习最优任务规划的决策层；位姿自主协同机制和嵌套式多策略智能体结构相融合的任务层。前者采用离散输出的深度强化学习制定多工步作业流程，通过适时改变环境和遴选工步间过渡点或区域等优化任务；后者引入可有效避免“万向节锁死”的泰特—布莱恩角设计复合式/模糊反馈位姿学习奖励机制。其中，模糊反馈中采用深度人工神经网络逐渐替代模糊规则，可显著提升奖励计算的实时性。<table border="0">
  <tr>
    <td width="50%">
      <img src="/Microgrid.png" width="100%"> 
    </td>
    <td width="50%">
      <img src="/ParallelDGs.png" width="100%"> 
    </td>
  </tr>
</table>

➤ **基于渐进无偏采样和混合高斯分布误差拟合的虚实策略转移架构**: 

该深度强化学习策略转移架构基于现实物理系统建立从运动学角度1:1还原的虚拟孪生系统。在后者中通过专家记忆库和探索记忆库构成的双记忆库结构和一种渐进无偏式采样方法提升策略学习的效率。其中专家记忆库中的数据来自有限的专家示教样本采用生成式对抗网络扩充后并通过模仿学习进行样本增生，其在训练初期占主导可加快算法收敛，后来逐渐减小权重过渡到以探索记忆库中随机无偏探索产生的样本数据为主导。考虑虚实差异，设计的经验回访池共享机制和基于混合高斯分布的误差拟合损失函数，可帮助实现虚实策略的高效转移。<table border="0">
  <tr>
    <td width="50%">
      <img src="/Microgrid.png" width="100%"> 
    </td>
    <td width="50%">
      <img src="/ParallelDGs.png" width="100%"> 
    </td>
  </tr>
</table>

➤ **蔡师兄论文**: 

简单介绍
<table border="0">
  <tr>
    <td width="50%">
      <img src="/Microgrid.png" width="100%"> 
    </td>
    <td width="50%">
      <img src="/ParallelDGs.png" width="100%"> 
    </td>
  </tr>
</table>

### **『------课题组指导老师发表论文------』**

➤ **Y. Shan**, J. Hu, and H. Liu, "[**A Holistic Power Management Strategy of Microgrids Based on Model Predictive Control and Particle Swarm Optimization**](https://ieeexplore.ieee.org/document/9591449)," in **IEEE Transactions on Industrial Informatics**. Online, 2021. **(Q1, IF:10.215)**

➤ **Y. Shan**, J. Hu, K. W. Chan and S. Islam, "[**A Unified Model Predictive Voltage and Current Control for Microgrids with Distributed Fuzzy Cooperative Secondary Control**](https://ieeexplore.ieee.org/document/9369108)," in **IEEE Transactions on Industrial Informatics**. Published, vol. 17, no. 12, pp. 8024-8034, Dec. 2021. **(Q1, IF:10.215)**

➤ **Y. Shan**, J. Hu and J. M. Guerrero, "[**A Model Predictive Power Control Method for PV and Energy Storage Systems with Voltage Support Capability**](https://ieeexplore.ieee.org/document/8766341)," in **IEEE Transactions on Smart Grid**. Published, vol. 11, no. 2, pp. 1018-1029, Mar. 2020. **(Q1, IF:8.96)**

➤ **Y. Shan**, J. Hu, M. Liu, J. Zhu and J. M. Guerrero, "[**Model Predictive Voltage and Power Control of Islanded PV-Battery Microgrids with Washout Filter Based Power Sharing Strategy**](https://ieeexplore.ieee.org/document/8768012)," in **IEEE Transactions on Power Electronics**. Published, vol. 35, no. 2, pp. 1227-1238, Feb. 2020. **(Q1, IF:6.153)**

➤ **Y. Shan**, J. Hu, K. W. Chan, Q. Fu and J. M. Guerrero, "[**Model Predictive Control of Bidirectional DC-DC Converters and AC/DC Interlinking Converters - A New Control Method for PV-Wind-Battery Microgrids**](https://ieeexplore.ieee.org/document/8478371)," in **IEEE Transactions on Sustainable Energy**. Published, vol. 10, no. 4, pp. 1823-1833, Oct. 2019. **(Q1, IF:7.917)**

➤ **Y. Shan**, J. Hu, Z. Li and J. M. Guerrero, "[**A Model Predictive Control for Renewable Energy Based AC Microgrids Without Any PID Regulators**](https://ieeexplore.ieee.org/document/8329538)," in **IEEE Transactions on Power Electronics**, Published, vol. 33, no. 11, pp. 9122-9126, Nov. 2018. **(Q1, IF:6.153)**

➤ J. Hu^, **Y. Shan^**, J. M. Guerrero, A. Ioinovici, K. W. Chan, J. Rodriguez, "[**Model predictive control of microgrids – An overview**](https://www.sciencedirect.com/science/article/abs/pii/S1364032120307097)," in **Renewable and Sustainable Energy Reviews**, Online, vol. 136, 2021. **(Q1, IF:14.982)** *^ corresponding author*

➤ J. Hu, **Y. Shan**, Y. Xu and J. M. Guerrero, "[**A coordinated control of hybrid ac/dc microgrids with PV-wind-battery under variable generation and load conditions**](https://www.sciencedirect.com/science/article/abs/pii/S0142061518310676), " in **International Journal of Electrical Power & Energy Systems**, Published, vol. 104, pp. 583-592, Jan. 2019. **(Q2, IF:4.63)**

➤ **单英浩**, 付青, 耿炫, 朱昌亚. [**基于改进BP-SVM-ELM与粒子化SOM-LSF的微电网光伏发电组合预测方法**](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDLAST2016&filename=ZGDC201612024&v=8%25mmd2BqyAWanNZni8pcqwdTmEy12cA55TTGvcSCGm2Osh3BcNG31xMe77SocMdQ4tEtG)[J]. **中国电机工程学报**, 2016, 36(12): 3334-3343. (In **Chinese**, **EI** indexed, **Top** Chinese Journals in electrical engineering)

...
### **『------课题组学生发表论文------』**

➤ **Y. Shan**, J. Hu, and H. Liu, "[**A Holistic Power Management Strategy of Microgrids Based on Model Predictive Control and Particle Swarm Optimization**](https://ieeexplore.ieee.org/document/9591449)," in **IEEE Transactions on Industrial Informatics**. Online, 2021. **(Q1, IF:10.215)**

➤ **Y. Shan**, J. Hu, K. W. Chan and S. Islam, "[**A Unified Model Predictive Voltage and Current Control for Microgrids with Distributed Fuzzy Cooperative Secondary Control**](https://ieeexplore.ieee.org/document/9369108)," in **IEEE Transactions on Industrial Informatics**. Published, vol. 17, no. 12, pp. 8024-8034, Dec. 2021. **(Q1, IF:10.215)**

➤ **Y. Shan**, J. Hu and J. M. Guerrero, "[**A Model Predictive Power Control Method for PV and Energy Storage Systems with Voltage Support Capability**](https://ieeexplore.ieee.org/document/8766341)," in **IEEE Transactions on Smart Grid**. Published, vol. 11, no. 2, pp. 1018-1029, Mar. 2020. **(Q1, IF:8.96)**

➤ **Y. Shan**, J. Hu, M. Liu, J. Zhu and J. M. Guerrero, "[**Model Predictive Voltage and Power Control of Islanded PV-Battery Microgrids with Washout Filter Based Power Sharing Strategy**](https://ieeexplore.ieee.org/document/8768012)," in **IEEE Transactions on Power Electronics**. Published, vol. 35, no. 2, pp. 1227-1238, Feb. 2020. **(Q1, IF:6.153)**

➤ **Y. Shan**, J. Hu, K. W. Chan, Q. Fu and J. M. Guerrero, "[**Model Predictive Control of Bidirectional DC-DC Converters and AC/DC Interlinking Converters - A New Control Method for PV-Wind-Battery Microgrids**](https://ieeexplore.ieee.org/document/8478371)," in **IEEE Transactions on Sustainable Energy**. Published, vol. 10, no. 4, pp. 1823-1833, Oct. 2019. **(Q1, IF:7.917)**

➤ **Y. Shan**, J. Hu, Z. Li and J. M. Guerrero, "[**A Model Predictive Control for Renewable Energy Based AC Microgrids Without Any PID Regulators**](https://ieeexplore.ieee.org/document/8329538)," in **IEEE Transactions on Power Electronics**, Published, vol. 33, no. 11, pp. 9122-9126, Nov. 2018. **(Q1, IF:6.153)**

➤ J. Hu^, **Y. Shan^**, J. M. Guerrero, A. Ioinovici, K. W. Chan, J. Rodriguez, "[**Model predictive control of microgrids – An overview**](https://www.sciencedirect.com/science/article/abs/pii/S1364032120307097)," in **Renewable and Sustainable Energy Reviews**, Online, vol. 136, 2021. **(Q1, IF:14.982)** *^ corresponding author*

➤ J. Hu, **Y. Shan**, Y. Xu and J. M. Guerrero, "[**A coordinated control of hybrid ac/dc microgrids with PV-wind-battery under variable generation and load conditions**](https://www.sciencedirect.com/science/article/abs/pii/S0142061518310676), " in **International Journal of Electrical Power & Energy Systems**, Published, vol. 104, pp. 583-592, Jan. 2019. **(Q2, IF:4.63)**

➤ **单英浩**, 付青, 耿炫, 朱昌亚. [**基于改进BP-SVM-ELM与粒子化SOM-LSF的微电网光伏发电组合预测方法**](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDLAST2016&filename=ZGDC201612024&v=8%25mmd2BqyAWanNZni8pcqwdTmEy12cA55TTGvcSCGm2Osh3BcNG31xMe77SocMdQ4tEtG)[J]. **中国电机工程学报**, 2016, 36(12): 3334-3343. (In **Chinese**, **EI** indexed, **Top** Chinese Journals in electrical engineering)

...


### **『------课题组发表专利------』**

➤ **Sustainable Energy Systems & Power Electronics**: 

Solar photovoltaic (PV), Wind turbine systems, MPPT, Grid integration, Power generation / load consumption forecast

➤ **Microgrids & Smart Grid Technologies**: 

Parallel systems control, Model predictive control (MPC) for microgrids, Operation modes (islanded, grid-connected and their transitions), Primary & secondary control

➤ **Intelligent algorithms**: 

Fuzzy logic control, Artificial neural network, Particle swarm optimization, Distributed control

<table border="0">
  <tr>
    <td width="50%">
      <img src="/Microgrid.png" width="100%"> 
    </td>
    <td width="50%">
      <img src="/ParallelDGs.png" width="100%"> 
    </td>
  </tr>
</table>

### **『------课题组指导老师获奖------』**

➤ **Y. Shan**, J. Hu and H. Liu, "[**Economic Dispatch of Model Predictive Controlled Distributed Power Generation**](https://ieeexplore.ieee.org/document/9680878)," 2021 IEEE International Conference on Predictive Control of Electrical Drives and Power Electronics (**PRECEDE 2021**), Jinan, China, 2021, pp. 836-839.

➤ **Y. Shan**, J. Hu and K. W. Chan, "[**Power sharing and V/f restoration of standalone AC microgrids using model predictive control**](https://ieeexplore.ieee.org/document/9038069)," The 11th IET International Conference on Advances in Power System Control, Operation and Management (**APSCOM 2018**), Hong Kong, China, 2018, pp. 1-5.

➤ **Y. Shan**, J. Hu, K. Wai Cheng and M. Liu, "[**A Universal Model Predictive Control for Practical AC Microgrids with PVs and Battery Energy Storage Systems**](https://ieeexplore.ieee.org/document/8557588)," 2018 IEEE Energy Conversion Congress and Exposition (**ECCE 2018**), Portland, OR, 2018, pp. 6257-6262.

...

### **『------课题组学生获奖------』**

➤ **Full scholarship for PhD**, HK-PolyU Funding, 2018-2020.

➤ **Best Paper Award**, "IET International Conference on Advanced Power System Control, Operation and Management (APSCOM)", Hong Kong, Dec. 2018.

➤ **National scholarship for Postgraduates**, Dec. 2016.

### **『------Communication and cooperation------』**

I am looking for **outstanding Research / Exchange Students (UG, GR, MSc, MPhil)**, various scholarships and allowances can be offered. 

**Collaboration and consultancies** are also welcome.

Please visit [**DHU Student Financial Aid Management Center**](http://web.dhu.edu.cn/dhuzizhu) or contact me **via Email** for more details.

### **『------News------』**

➤ {Paper}2021-11-19: My review paper entitled "**Model predictive control of microgrids – An overview**" published in the journal "**Renewable and Sustainable Energy Reviews**" has been [**highly cited**](https://www.webofscience.com/wos/woscc/full-record/WOS:000597235700002?SID=7AKF6rRDwVTwF22RakJ)! I'm one of the corresponding authors.
<table border="0">
  <tr>
    <td width="100%" align="center">
     <img src="/高被引截图6.png" width="70%"> 
    </td>
  </tr>
</table>

➤ {Paper}2021-10-28: My paper (1st author) entitled "**A Holistic Power Management Strategy of Microgrids Based on Model Predictive Control and Particle Swarm Optimization**" is online now! Published in the journal "**IEEE Transactions on Industrial Informatics**", Q1 top journal. Click [**here**](https://ieeexplore.ieee.org/document/9591449)!

➤ {Funding}2021-05-19: My "[**Shanghai Sailing Program**](http://stcsm.sh.gov.cn/zwgk/tzgs/gsgg/bsgsgg/kjjhxmjggb/20210518/9ecb2e8bc52742488372c9330c9a344f.html)" has been approved, it is about using MPC to address the fluctuations from renewables.

➤ {Funding}2021-04-28: My "**Initial Research Funds for Yong Teachers of Donghua University**" has been fully issued.

➤ {Paper}2021-03-04: My paper (1st author) entitled "**A Unified Model Predictive Voltage and Current Control for Microgrids with Distributed Fuzzy Cooperative Secondary Control**" is online now! Published in the journal "**IEEE Transactions on Industrial Informatics**", Q1 top journal. Click [**here**](https://ieeexplore.ieee.org/document/9369108)!

➤ {Funding}2021-01-21: One of my projects under "**Fundamental Research Funds for the Central Universities**" had been successfully approved. The topic is "**Research on the Secondary Adaptive Control of Microgrids Based on Model Prediction and Distributed Cooperation methods**". I am the first person in charge. The follow-up work will be carried out soon.

➤ {Paper}2020-10-8: Today, my paper (review paper) entitled "**Model predictive control of microgrids – An overview**" is online now! Published in the journal "**Renewable and Sustainable Energy Reviews**", Q1 top journal. This paper is supported by **three IEEE fellows**! Take a first look at [**here**](https://www.sciencedirect.com/science/article/pii/S1364032120307097)!

### **『------History records------』**

➤ **2021年上海电源学会年度学术交流会**安排在**11月27日**在**东华大学松江校区**举办，上海电源学会会员免费参加，围绕着“双碳”背景下能源电力技术领域开展研讨，邀请著名行业专家就综合能源系统的发展趋势、电力变换新技术、智慧能源等发表主旨演讲，详见[**会议通知**](https://github.com/ShanYinghao/shanyinghao.github.io/raw/main/2021%E5%B9%B4%E5%BA%A6%E4%B8%8A%E6%B5%B7%E7%94%B5%E6%BA%90%E5%AD%A6%E4%BC%9A%E5%B9%B4%E5%BA%A6%E4%BA%A4%E6%B5%81%E4%BC%9A%E8%AE%AE%E9%80%9A%E7%9F%A5%20V2.0.pdf)，***[已截止]***，欢迎大家齐聚美丽的东华大学~

### **『------Contact------』**

### Please save/scan my QR code below, stay in touch! 
<table border="0">
  <tr>
    <td width="100%" align="center">
     <img src="/MyQRCode.png" width="20%"> 
    </td>
  </tr>
</table>

![China_Shanghai_DHU](/China_Shanghai_DHU.png)
*Know more about **Shanghai**: 
please visit [**Official Encyclopedia**](http://zhuanti.shanghai.gov.cn/newencyclopedia/en/Default3.aspx), [**Travel Guides**](https://hk.trip.com/travel-guide/shanghai-2/)*

