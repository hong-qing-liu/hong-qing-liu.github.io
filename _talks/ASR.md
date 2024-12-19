---
title:  "<span style=\"color: blue; text-decoration: none;\"> 语音识别 </span>"   
collection: talks
type: "Talk"
permalink: /talks/ASR
---

---
- <font size=3> 利用transformer结构的encoder-decoder方案，可以实现轻松的转录。</font>  

---
### 方言识别
- <font size=3> 采集了约40小时的重庆方言。</font>
- <font size=3> 训练轻量化模型。 </font>
 <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
    <iframe 
    src="//player.bilibili.com/player.html?isOutside=true&aid=1705132836&bvid=BV1dT421i7ZU&cid=1562461104&autoplay=0" 
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
    frameborder="0" 
    allowfullscreen="true">
    </iframe>
  </div>
 
### 粤语英语混合识别
- 由于特定地区说话的方式，混合语言识别更能体现本地化。但是一般这种情况语料稀缺，在同一段话或句子中，可能会存在快速的语言切换（例如，粤语和英语交替使用），而且粤语有六个声调，英语通常没有类似的音调变化，需要模型能够处理两种语言交替使用的词汇和语法结构。
- 识别结果
  ![AEC before](/images/mixedASR.jpg){: .align-center width="700px"}
