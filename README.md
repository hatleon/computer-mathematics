# computer-mathematics 深度学习之数学实战

（1）（中文版）深度学习之数学实战
贝叶斯网引论-- 凸优化-- 深度学习花书-- The Matrix Cookbook

我的百度网盘-- （数学）机器学习-- 数学知识大全 凸优化中文版

D:\desktop\work\数学\凸优化
https://github.com/xinan711456/computer-mathematics

The Matrix Cookbook(译)
https://blog.csdn.net/wancongconghao/article/details/71156104

（花书）有什么深度学习数学基础书推荐？
https://www.zhihu.com/question/41459109/answer/202188958

（美国课程）机器学习应补充哪些数学基础？
https://www.zhihu.com/question/24345119/answer/564893704

本文为巡洋舰的深度学习实战课程数学预科准备。
你需要的深度学习数学基础： 从入门到进阶
https://zhuanlan.zhihu.com/p/31295279

（matrix cookbook 比较全，比较好）深度学习的数学基础
https://github.com/NLPpupil/mathematical_foundation

（深入很好）深度学习需要掌握哪些数学基础？
https://www.zhihu.com/question/64940506/answer/263807063

现在机器学习工业界和学术界的差别越来越大了吗？尽早实习和踏实科研各有什么利弊？
https://www.zhihu.com/question/63883029/answer/579269917

（2）深度学习的数学基础
深度学习用到的数学主要有概率与统计、线性代数和微积分，还有少量信息论和凸优化的内容。 下面详细介绍各部分和推荐相应学习资料，推荐的课件已经下载好了，但是推荐的书籍还要自己找资源（不能公开分享盗版书籍）。

概率与统计
大多数深度学习模型都是概率模型，训练参数的过程就是调整概率模型参数的过程。学习和设计深度学习模型的过程中贯穿了各种统计学知识，因此概率和统计非常重要。

想快速上手可以看斯坦福大学的课件 Review of Probability Theory。系统学习推荐教材 统计学完全教程(All of statistics)，作者是CMU的统计和数据科学教授，这本书主要是为计算机科学的学生而写。

线性代数
深度学习的参数大多可以用矩阵表示，深度学习用到的线性代数主要是矩阵乘法和矩阵微分。

课件推荐斯坦福大学的Linear Algebra Review and Reference。教材推荐《线性代数应该这样学》，这本教材没有从行列式讲起，也没有一开始就让读者陷入繁琐的矩阵计算中，而是把线性代数的思想和概念由浅入深地慢慢呈现在读者面前。MatrixMultPractice 是矩阵计算的练习题，The Matrix Cookbook 可以当做手册和工具书用。

微积分
主要用于反向传播的推导。

教材推荐James Stewart的 Calculus，Calculus Notes 是我从书上抄的笔记。不要看同济大学的 《高等代数》 了。

信息论
信息熵这个概念经常出现，跟概率密不可分，比如交叉熵、相对熵和最大熵。

看完南京大学的课件 Information Theory and Decision Tree 就够了。

凸优化
这块内容不懂也没事，但是想更上一层楼一定要懂。它是研究的的最小化一个函数，像推导SVM这样的理论问题都是要凸优化知识的。

推荐斯坦福大学的课件 Convex Optimization Overview。
