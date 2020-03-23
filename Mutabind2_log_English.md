# The recent server changes

### 1. There is no link to homologous binding sites from the results page although we talk about it in the paper;

>    *There are homologous binding sites on the single mutation result page*

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.1.png)

>    *but it cannot be given in the multiple mutations*

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.2.png)

### 2.	The download file has energy terms which are not described anywhere including “Model_bias” – what is it?

>    *A sentence is added to the file of Readme*

>    *Model_bias is the average of the DDGexp in S4191/S1707.*

>    *The predicted value = Model_bias(the average of the experimental values of the training set)+the contribution values of each feature, the relevant detailed explanation of random forest:*

>    *<http://engineering.pivotal.io/post/interpreting-decision-trees-and-random-forests/>*

### 3.	“More details can be found in our paper.” – it should be changed into “more details can be found in the paper …and give a link to the paper);

>    *A PubMed link to our paper is attached below.*

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.re1.png)

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.re2.png)

## The submission issues about the multiple mutation 

>    *Different types of mutations similar to submitting the same location will still be submitted to the backend computing program, which we did not filter out when submitting.*

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.4.png)

>    *If we add a restriction to the site, no matter how the mutation is submitted, and the same mutation id is not allowed to the same location, otherwise an error infomation will occur.* 

>    *The error prompt is:*  

>    ***A multiple mutation cannot be occurred at the same mutated site simultaneously, please check you submission.***

>    ![alt img1](https://github.com/luyu103713/mutabind2_document/raw/master/imgs/19.6.png)

