---
title: "音质修复 (Speech enhancement)"
collection: talks
type: "Talk"
permalink: /talks/SE
---

## 音质修复 
- <font size=3> 音质修复包含很多方面，例如噪声去除，啸叫抑制，语音超分辨等，完成语音质量的提升。</font>  



###  噪声去除
-- <font size=3> 基于大数据和智能的方案，可以有效的去除非平稳噪声，达到相对于传统算法更优良的效果。 模型小，有利于实时实现。</font>  
  
-- <font size=3> 去噪之前</font>  
![SE before](/images/nesebefore.png){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/nesebefore.wav">{: .align-center}
 

-- <font size=3> 去噪之后</font>  
![SE after](/images/neseafter.png){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/neseafter.wav">{: .align-center}

-- 语音增强 *[DEMOPAGE](https://wanliangdaxia.github.io/){:target="_blank"}*.
###  啸叫抑制

-- <font size=3> 在扩声场景下，由于扬声器播发出的声音又被麦克风采集到，如此反复形成一个闭合回路，从而刺耳的啸叫声。这种情况不仅容易损坏设备，也同时影响听觉。</font>  

-- <font size=3> 啸叫抑制之前</font>  
![Howling before](/images/howlbefore.JPG){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/howl-noisy.wav">{: .align-center}
 

-- <font size=3> 啸叫抑制之后</font>  
![Howling after](/images/howlafter.JPG){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/howl-enhance.wav">{: .align-center}

 
###  语音超分辨

-- <font size=3> 将低采样率的语音转变成高采样率的语音，提升听感。</font>  

-- <font size=3> 超分辨之前</font>  
![super before](/images/superbefore.png){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/superbefore.wav">{: .align-center}
 

-- <font size=3> 超分辨之后</font>  
![super after](/images/superafter.png){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/superafter.wav">{: .align-center}

-- 超分辨 *[DEMOPAGE](https://sdnetdemo.github.io/){:target="_blank"}*.
