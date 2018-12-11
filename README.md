# 百度机器阅读理解竞赛 3rd 解决方案
[百度 PaddlePaddle AI 大赛——智能问答](https://www.kesci.com/home/competition/5ad56e667238515d80b53704/content)  
百度机器阅读理解竞赛模型核心代码的 tensorflow 实现 ，排行榜上以0.5*BLEU-4+0.5*ROUGE-L计为总分来排名，一个 epoch 线上成绩可达到 41+；
获得 final 第三名，最终评审得到二等奖。

模型实现主要采用了百度 DuReader 的代码 ：https://github.com/baidu/DuReader （引用的代码文件开头都保留了原来的版权声明的注释信息）我的工作主要在 notebook 里面，如果要理解相关算法原理建议直接看 DuReader baseline 。
