---
title: "声学回声消除-AEC"
collection: talks
type: "Talk"
permalink: /talks/AEC
---

### <font size=4> 声学回声消除 </font>
- <font size=3> 回声消除(Acoustic echo cancellation, AEC)是利用远端信号作为参考信号，完成近端信号中的回声去除，完成清晰的通话。</font>  



####  全神经网络方案
- 利用时频域信息，设计了一个实时的全网络模型完成回声消除和噪声抑制，区别于常用的先传统方法和后滤波方案。
  
- AEC之前
![AEC before](/images/neaecmic.JPG){: .align-center width="300px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/neaecmic.wav">
 

- AEC之后
![AEC before](/images/neaecout.JPG){: .align-center width="300px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/neaecout.wav">
 

