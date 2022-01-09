**《动手学习深度学习》** 是李沐老师（AWS 资深首席科学家，美国卡内基梅隆大学计算机系博士）主讲的一系列深度学习视频。

通常我们提到深度学习，常常会忘记深度学习只是机器学习的一小部分，而认为它是独立于机器学习的单独模块。这是因为机器学习作为一门历史更悠久的学科，在深度学习没有问世之前，在现实世界的应用范围很窄。像语音识别、计算机视觉、自然语言处理等领域，由于需要大量的领域知识并且问题异常复杂，机器学习往往只是解决这些领域问题方案中的一小部分。

但是就在过去的几年里，深度学习的问世和应用给世界带来了惊喜，推动了计算机视觉、自然语言处理、自动语音识别、强化学习和统计建模等领域的快速发展。

在 **《动手学习深度学习》** 这门课程中，既有少量的机器学习的基础知识，比如：线性神经网络，多层感知机等等；又有如今前沿应用的各种深度学习模型：包括leNet，ResNet，LSTM，BERT……同时每一章节的讲解还配备由pytorch实现的代码、教科书等等，可以帮助同学在短期内掌握深度学习的基础模型与前沿知识和并提高实践能力。

- B站教学网址：[动手学习深度学习（已完结）](https://space.bilibili.com/1567748478/channel/seriesdetail?sid=358497)

- 教材网址：[zh-v2.d2l.ai](https://zh-v2.d2l.ai)
- 论坛网址：[discuss.d2l.ai](https://discuss.d2l.ai/c/chinese-version/16)，[discuss.pytorch](https://discuss.pytorch.org)

此外，本门课程配备除了有专门的教材，还有代码实现。**每一章都是一个jupyter记事本，提供所有模型的完整实现**，所有的资源都可在网上免费获取。
本项目记录了我们在寒假期间学习交流的笔记，汇报展示用的PPT，和相关的代码。希望在自己学习的同时，也对大家学习李沐老师的《动手学习深度学习》有所帮助。


## 动手学深度学习笔记整理
| 序号 | 标题 | 视频 | 链接 |贡献者 |
| :----| :---- | :----| :---- | :---- |
| 序号 | [标题](笔记链接网址) | [视频](b站视频网址) | [笔记](笔记链接) [代码](代码链接) [PPT](PPT链接)| [贡献者](贡献者主页网址) |
| 00 | [预告](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/notes/00-%E9%A2%84%E5%91%8A.md) | [视频](https://www.bilibili.com/video/BV1if4y147hS?spm_id_from=333.999.0.0) | [笔记](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/notes/00-%E9%A2%84%E5%91%8A.md) [代码](https://github.com/yizhen20133868/DeepLearning-MuLi-Notes/blob/main/code/code_demo.py) [PPT](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/ppt/ppt_demo) | [kokolerk](https://github.com/kokolerk), [Aleafy](https://github.com/Aleafy) |
| 01 | [课程安排](notes/01-%E8%AF%BE%E7%A8%8B%E5%AE%89%E6%8E%92.md) | [视频](https://www.bilibili.com/video/BV1oX4y137bC?spm_id_from=333.999.0.0) | [笔记](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/notes/01-%E8%AF%BE%E7%A8%8B%E5%AE%89%E6%8E%92.md)  [PPT](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/ppt/00-02.%E9%A2%84%E5%91%8A%E3%80%81%E5%AE%89%E6%8E%92%E5%92%8C%E4%BB%8B%E7%BB%8D.pptx)| [Aleafy](https://github.com/Aleafy) |
| 02 | [深度学习介绍](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/notes/02-%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E4%BB%8B%E7%BB%8D.md) | [视频](https://www.bilibili.com/video/BV1J54y187f9?spm_id_from=333.999.0.0) | [笔记](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/notes/02-%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E4%BB%8B%E7%BB%8D.md)  [PPT](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/ppt/00-02.%E9%A2%84%E5%91%8A%E3%80%81%E5%AE%89%E6%8E%92%E5%92%8C%E4%BB%8B%E7%BB%8D.pptx)| [Aleafy](https://github.com/Aleafy) |
| 03 | [安装](https://github.com/kinza99/DeepLearning-MuLi-Notes/blob/main/notes/03-安装.md) | [视频](https://www.bilibili.com/video/BV18p4y1h7Dr) | [笔记](https://github.com/kinza99/DeepLearning-MuLi-Notes/blob/main/notes/03-安装.md)  [PPT](https://courses.d2l.ai/zh-v2/assets/pdfs/part-0_3.pdf)| [Kinza99](https://github.com/kinza99) |
| 04 | [数据操作和数据预处理](notes/04-%E6%95%B0%E6%8D%AE%E8%AF%BB%E5%8F%96%E5%92%8C%E6%93%8D%E4%BD%9C.md) | [视频](https://www.bilibili.com/video/BV1CV411Y7i4?spm_id_from=333.999.0.0) | [笔记](notes/04-%E6%95%B0%E6%8D%AE%E8%AF%BB%E5%8F%96%E5%92%8C%E6%93%8D%E4%BD%9C.md) [代码](code/04-%E6%95%B0%E6%8D%AE%E8%AF%BB%E5%8F%96%E5%92%8C%E6%93%8D%E4%BD%9C) [PPT](ppt/04%E6%95%B0%E6%8D%AE%E6%93%8D%E4%BD%9C%E5%92%8C%E6%95%B0%E6%8D%AE%E9%A2%84%E5%A4%84%E7%90%86%E6%80%BB%E7%BB%93%EF%BC%88%E5%BC%A0%E5%8D%9A%E9%91%AB%EF%BC%89.pptx)| [Atream](https://github.com/Atream) ，[benmagnifico](https://github.com/benmagnifico)|
| 05 | [线性代数](notes/05-%E7%BA%BF%E6%80%A7%E4%BB%A3%E6%95%B0.md) | [视频](https://www.bilibili.com/video/BV1eK4y1U7Qy?spm_id_from=333.999.0.0) | [笔记](notes/05-%E7%BA%BF%E6%80%A7%E4%BB%A3%E6%95%B0.md) [PPT](notes/05-05-%E7%BA%BF%E6%80%A7%E4%BB%A3%E6%95%B0.md.md)| [dcy-dhsunabzh](https://github.com/dcy-dhsunabzh) |
| 06 | [矩阵计算](notes/06-%E7%9F%A9%E9%98%B5%E8%AE%A1%E7%AE%97.md) | [视频](https://www.bilibili.com/video/BV1eZ4y1w7PY?spm_id_from=333.999.0.0) | [笔记](notes/06-%E7%9F%A9%E9%98%B5%E8%AE%A1%E7%AE%97.md)  [PPT](ppt/06-%E7%9F%A9%E9%98%B5%E8%AE%A1%E7%AE%97.pdf)| [EcolesYee](https://github.com/EcolesYee) |
| 07 | [链式法则和自动求导](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/notes/07-%E8%87%AA%E5%8A%A8%E6%B1%82%E5%AF%BC.md) | [视频](https://www.bilibili.com/video/BV1KA411N7Px?spm_id_from=333.999.0.0) | [笔记](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/notes/07-%E8%87%AA%E5%8A%A8%E6%B1%82%E5%AF%BC.md) [代码](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/code/07-%E8%87%AA%E5%8A%A8%E6%B1%82%E5%AF%BC.py) [PPT](ppt/04%E6%95%B0%E6%8D%AE%E6%93%8D%E4%BD%9C%E5%92%8C%E6%95%B0%E6%8D%AE%E9%A2%84%E5%A4%84%E7%90%86%E6%80%BB%E7%BB%93%EF%BC%88%E5%BC%A0%E5%8D%9A%E9%91%AB%EF%BC%89.pptx)| [Chigland](https://github.com/Chigland)|


## 文件夹说明
- **imgs**：笔记涉及到的图片
- **notes**：笔记的markdown版本
- **code**：课程涉及到的python代码
- **PPT**：课程汇报交流的PPT
