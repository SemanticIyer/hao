问：@图像视觉研究 有没有经典的Multi-Class boosting的相关资料推荐推荐？
答：找到几篇经典论文和几个工具包  [资料卡片](http://bigdata.memect.com/?tag=MultiClassBoosting)

# overview
http://www.svcl.ucsd.edu/projects/mcboost/

http://classes.soe.ucsc.edu/cmps242/Fall09/proj/Mario_Rodriguez_Multiclass_Boosting_talk.pdf  Multi-class boosting (slides), Mario Rodriguez, 2009

http://cmp.felk.cvut.cz/~sochmj1/adaboost_talk.pdf presentation summarizing AdaBoost 

#video lectures

https://www.youtube.com/watch?v=L6BlpGnCYVg  "A Theory of Multiclass Boosting", Rob Schapire, Partha Niyogi Memorial Conference: Computer Science

http://techtalks.tv/talks/multiclass-boosting-with-hinge-loss-based-on-output-coding/54338/ Multiclass Boosting with Hinge Loss based on Output Coding, Tianshi Gao; Daphne Koller, ICML 2011

# classical paper
http://web.mit.edu/torralba/www/cvpr2004.pdf Sharing features: efficient boosting procedures for multiclass object detection, Antonio Torralba Kevin P. Murphy William T. Freeman, CVPR 2004


http://dept.stat.lsa.umich.edu/~jizhu/pubs/Zhu-SII09.pdf  Multi-class AdaBoost, Ji Zhu†, Hui Zou, Saharon Rosset and Trevor Hastie, Statistics and Its Interface, 2009

http://www.cs.princeton.edu/~imukherj/nips10.pdf  A Theory of Multiclass Boosting, Indraneel Mukherjee, Robert E. Schapire, NIPS 2010

http://papers.nips.cc/paper/4450-multiclass-boosting-theory-and-algorithms.pdf Multiclass Boosting: Theory and Algorithms, Mohammad J. Saberian, Nuno Vasconcelos, NIPS, 2011 


# tools
http://www.multiboost.org/ a fast C++ implementation of multi-class/multi-label/multi-task boosting algorithms. It is based on AdaBoost.MH but also implements popular cascade classifiers and FilterBoost along with a batch of common multi-class base learners (stumps, trees, products, Haar filters).

http://scikit-learn.org/stable/auto_examples/ensemble/plot_adaboost_multiclass.html

https://github.com/cshen/fast-multiboost-cw

https://github.com/pengsun/AOSOLogitBoost

https://github.com/circlingthesun/omclboost