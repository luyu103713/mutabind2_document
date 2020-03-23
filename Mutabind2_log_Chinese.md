# 2020-03-20 update：

## Dr.Anya's suggestions

### 1. There is no link to homologous binding sites from the results page although we talk about it in the paper;

>    *单突变的结果页面有homologous binding sites*

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.1.png)

>    *而多突变无法给出，所以没有*

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.2.png)

### 2.	The download file has energy terms which are not described anywhere including “Model_bias” – what is it?

>    *在readme文件里面中增加了一句*

>    *Model_bias is the average of the DDGexp in S4191/S1707.*

>    *预测值=Model_bias(训练集的实验值的平均值)+各个feature贡献值，详细的有关random forest的解释*

>    *<http://engineering.pivotal.io/post/interpreting-decision-trees-and-random-forests/>*

### 3.	“More details can be found in our paper.” – it should be changed into “more details can be found in the paper …and give a link to the paper);

>    *更改了首页的Reference和增加了"More details can be found in our paper"后面我们文献的pubmed链接*

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.re1.png)

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.re2.png)

### 4.	I think we should add something to the front page explaining why users get slightly different results every time they run mutabind on the same system.

>    *因为CHARMM的energy模块在计算PB时，每次都会产生一定的波动。*


## Mutabind2 多突变提交的问题

>    *类似提交同一个位置的不同类型突变，还是会提交到后端计算程序，我们在提交的时候没有过滤掉*

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.4.png)

>    *我们在网站加入限制，不管什么方法提交来的突变，不允许同一个mutation id下面出现相同的位置，否则会报错* 

>    *错误提示为*  

>    ***A multiple mutation cannot be occurred at the same mutated site simultaneously, please check you submission.***

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.6.png)

