---
title: "声学回声消除 (Acoustic echo cancellation)"
collection: talks
type: "Talk"
permalink: /talks/AEC
---

##  声学回声消除  
- <font size=3> 回声消除(Acoustic echo cancellation, AEC)是利用远端信号作为参考信号，完成近端信号中的回声去除，完成清晰的通话。</font>  



###  <font size=4> 单通道回声消除 </font>
-- <font size=3> 利用时频域信息，设计了一个实时的全网络模型完成回声消除和噪声抑制，区别于常用的先传统方法和后滤波方案。</font>  
  
-- <font size=3> AEC之前</font>  
![AEC before](/images/neaecmic.JPG){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/neaecmic.wav">


-- <font size=3> AEC之后</font>  
![AEC before](/images/neaecout.JPG){: .align-center width="700px"}
 ​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/neaecout.wav">

### <font size=4> 立体声回声消除</font>
-- <font size=3> 立体声回声消除（SAEC）中，一个麦克风会接收到多个扬声器传来的回声，导致回声路径难以识别，回声消除任务变得更加困难。</font>  

-- <font size=3> 双通道AEC之前</font>  
![SAEC before](/images/saecbefore.png){: .align-center  width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/saecbefore.wav">
 

-- <font size=3> 双通道AEC之后</font>  
![SAEC before](/images/saecafter.png){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/saecafter.wav">
 
 

