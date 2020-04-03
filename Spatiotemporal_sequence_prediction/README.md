# Spatiotemporal sequence prediction Papers

- Introduction:
    - List of awesome papers from various research fields in  Spatio-temporal sequence prediction, mainly including algorithms based on deep learning about RNN and GAN. 
    - I will mainly give the name of the paper, paper download link,  paper introduction and my own understanding.
    - A link of open source code is given if avaliable on [Papers With Code](https://paperswithcode.com/) or [Github](https://github.com/).
    - I also get open source some codes as well.
    - Some papers will give links to reading notes.
- 介绍：
    - 收录时空序列预测各个研究领域的高水平文章，主要包含基于深度学习算法，比如RNN和GAN。
    - 我将主要给予论文的名称、下载连接、论文简介以及我个人的一些主要理解。
    - 如果 [Papers With Code](https://paperswithcode.com/) 或 [Github](https://github.com/) 上存在该论文的开源代码，则给出其链接。
    - 我也会独立开源一些代码以及框架。
    - 有些论文会给出解读的链接。




### Recurrent Neural Network (循环神经网络)



#### ** Convolutional LSTM Network: A Machine Learning  Approach for Precipitation Nowcasting** (**NIPS2015**) [[paper](https://arxiv.org/pdf/1506.04214.pdf)] *

- In this paper, we formulate precipitation nowcasting as a spatiotemporal sequence forecasting problem in which both the input and the prediction target are spatiotemporal sequences. By extending the fully connected
    LSTM (FC-LSTM) to have convolutional structures in both the input-to-state and state-to-state transitions, we propose the convolutional LSTM (ConvLSTM) and use it to build an end-to-end trainable model for the precipitation nowcasting problem. 
- 在这个论文中，我们把降水预测作为时空序列问题来处理。通过将input-to-state and state-to-state转换从全连接转换成卷积，我们提出了ConvLSTM并且利用它去建立端到端模型应用于降水预测问题。
    - 提出了convLSTM
    - 提出了encoding-forcasting结构
    - 提出了把深度学习这些模型应用到降水预测中， 并且相当于给予了一些思路和baseline
    - 强调了out-of-domain这个方面以及整个方面在实际应用中的重要性

| paper-notes（论文解读笔记）                  |                            公众号                            |                             CSDN                             |                            知乎                            |
| :------------------------------------------- | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------------------------------------------------------: |
| 时空序列预测模型之Convolutional LSTM Network | [公众号](https://mp.weixin.qq.com/s?__biz=MzA4ODUxNjUzMQ==&mid=2247484743&idx=2&sn=10387417121b70ec27e311f9c5b0e493&scene=19&token=1999900258&lang=zh_CN#wechat_redirect "悬停显示") | [CSDN](https://blog.csdn.net/qq_33431368/article/details/100053949"悬停显示") | [知乎](<https://zhuanlan.zhihu.com/p/92868370> "悬停显示") |