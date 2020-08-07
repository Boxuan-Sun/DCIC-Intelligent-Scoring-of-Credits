# DCIC-Group-Image-of-Consumers-----Intelligent-Scoring-of-Credits
比赛：消费者人群画像—信用智能评分
主办方：福建省数字福建建设领导小组办公室 & 福建省工业和信息化厅 & 福州市人民政府 & 中国电子信息产业发展研究院 & 数字中国研究院 & 中国互联网投资基金

比赛链接：https://www.datafountain.cn/competitions/337/details

参赛人：Chain、我爱写代码、我真不会造轮子、憨子哥、Iron_man

这次比赛我们队取得了线上A榜和B榜的第六名，很遗憾我们未能进入最终的总决赛，但能取得这样的成绩已经很满意了（我没有做过比赛），希望能吸取这次的经验教训，继续学习，在以后的比赛中能有更好的表现。

在这里也要特别感谢那些大佬们的开源，正是他们的开源让我们学习到了很多，并且慢慢进步。在我们的代码中就有一些特征用到了那些大佬开源使用的方法，真的非常感谢。

比如郭大、林有夕、小兔子乖乖他们开源的这个：https://github.com/PandasCute/2018-CCF-BDCI-China-Unicom-Research-Institute-top2

以及鱼佬在知乎上写的文章都让我们受益匪浅。https://www.zhihu.com/people/wang-he-13-93/posts


运行代码步骤及说明：

1.先创建一个result的文件夹，来存放训练结果。

2.src文件夹中的main.py运行模型，然后运行dealdata.py来进行模型融合。

注：把文件夹名src改为src2（忘改回来了）



feature.py是我们构造的六套特征

model.py是我们的六个模型

我们这个虽然构造了六套特征，但其实主要就那几个特征，构造六套特征的目的是使特征之间有差异性，使融合的效果更好。
