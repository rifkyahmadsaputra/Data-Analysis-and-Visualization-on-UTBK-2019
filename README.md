# Data Analysis UTBK 2019 Indonesia

## Introduction
<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this project, I do some analysis and visualization on samples of scores UTBK SBMPTN 2019 data. I do that because I want to find informations and insights about UTBK  in 2019, e.g. what majors and universities are the most favourite in 2019, distribution of participants UTBK scores in 2019,  etc.
 <br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The data  used in this project is 147k samples of scores from Indonesia UTBK SBMPTN 2019, taken from Kaggle (https://www.kaggle.com/ekojsalim/indonesia-college-entrance-examination-utbk-2019). After that, I do some preprocessing on the data and create new columns that is participants average scores (do average on each participants scores), majors and universities names of the participants first and second choice, etc. Then, do some analysis in order to get insight or information from data, and make data visualization so that the data can be easily understood. 
</p>

## Data
<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; There are about 147 thousand samples (out of 1.1 million total scores) and this data is not indicative of the whole 1.1 million dataset as it is collected from a third-party sources (with maybe some invalid data strewn in). This dataset also contains the major picked by those exam-takers.
 <br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The testing part of UTBK SBMPTN was held in 'waves' and 'batches'. There are 2 'waves' of examinations and an exam-taker could take part in both 'waves' and thus have 2 scores for the examination. The first part of these two examinations are general knowledge and reasoning tests covering. The second part differs according to the examination types, science-type examinations (science-related major) or humanities-type examinations (humanities-related major). 
 <br></br>
 Check this link for details of the data : https://www.kaggle.com/ekojsalim/indonesia-college-entrance-examination-utbk-2019
</p>

## Summary (Analysis and Visualization)
<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; First thing that I do in this project is do some preprocessing data and create some new columns, that is  participants average scores (do average on each participants scores), majors and universities names of the participants first and second choice, participants average scores from each majors and universities (calculated based on average scores on each participants who choose the same major and universitiy), etc.
</p>

<p align="center"> 
 <img src="images/data preprocessed (1).png" /> 
 <img src="images/data preprocessed (2).png" /> 
 <img src="images/data preprocessed (3).png" /> 
 <br></br>
 Data preprocessed
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; After that I do some visualizations on the data. Firstly, I do analysis and visualize of capacity on each majors in universities. The following are some informations and the distribution plot.
</p>

<p align="center"> 
 <img src="images/information and distribution plot of capacity on each majors in universities.png" /> 
 <br></br>
 Information and distribution of capacity on each majors in universities
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Based on picture above, major and university that have the most capacity is law major in Diponegoro University. Meanwhile, majors and universities that have least capacity are chemistry, math, biology and aquaculture majors in Ganesha University of Education and puppetry art major in ISI Denpasar. Then, based on informations and distribution plot,  distributions of capacity are around 30 to 60 and the average capacity of majors and universities in Indonesia is around 51. After that, I want to know what the most majors are provided by universities and the universities has most numbers of majors. So,  that are visualizations of top 10 most majors are provided by universities and top 10 universities based on the most number of majors.
</p>

<p align="center"> 
 <img src="images/top 10 first choices humanities-related majors and universities.png" /> 
 <br></br>
 Top 10 first choices humanities-related majors and universities
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Can be seen from pictures above, management (63 universities), accountant (59 universities) and law (57 universities) majors are the three majors that are mostly provided by universities in Indonesia. Meanwhile, Indonesia University of Education (81 majors), Brawijaya University (75 majors) and Haluoleo University (74 majors) are the three universities with the most majors. After that, I also find out the comparison of the number of majors based on the type of majors, which is humanities and science -related majors. So, here is  the visualization.
</p>

<p align="center"> 
 <img src="images/comparison type of majors.png" /> 
 <br></br>
 Comparison type of majors
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Can be seen from picture above, number of majors which type science-related majors is more than humanities-related majors, by comparison 53.96%% (1709 majors) on  science-related majors and 46.04% (1458) on humanities-related majors. After that , I do analysis and visualization separately based on major types (humanities dan science -related majors) which choose by participants.
</p>

#### Analysis and Visualization on Participants Who Take Humanities-type Examinations
1. First choices humanities-related majors and universities from participants who take humanities-type examinations.
<br></br>
 
- Top 10 first choices humanities-related majors and universities

<p align="center"> 
 <img src="images/top 10 first choices humanities-related majors and universities.png" /> 
 <br></br>
 Top 10 first choices humanities-related majors and universities
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Can be seen from picture above, that law, management and accountant majors is the top three most chosen majors in the first choice by participants. Meanwhile in universities section, there are University of Indonesia, Padjadjaran University and Brawijaya University which become top three most chosen universities in the first choice by participants who take humanities-type examinations.
</p>
 <br></br>
 
- Average score participants on top 10 first choices humanities-related majors and universities.

<p align="center"> 
 <img src="images/average score participants on top 10 first choices humanities-related majors and universities.png" /> 
 <br></br>
 Average score participants on top 10 first choices humanities-related majors and universities
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Based on pictures above, top 10 humanities-related majors has almost the same on participants average scores distributions. It could be said that majors has a same difficult level of competition. Meanwhile in universities section, there are three universities which has higher participants average scores distributions than other universities, that is Gadjah Mada University, University of Indonesia and Diponegoro University. It can also be concluded, that three universities has a more difficult level of competition than other universities.
</p>
<br></br>

- Top 5 first choices humanities-related majors - universities (with average score participants).
<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this section, I do more specific analysis to the participants data, that is grouping and analyzing data participants who chose the same humanities-related major and university as the first choice.
</p>

<p align="center"> 
 <img src="images/top 5 first choices humanities-related majors – universities (with average score participants).png" /> 
 <br></br>
 Top 5 first choices humanities-related majors – universities (with average score participants)
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Can be seen from barplot above, law major in Diponegoro University has most participants that is 721 number of participants, followed by law major in University of Indonesia with 536 number of participants, law major in Brawijaya University with 454 number of participants, etc. Meanwhile in the boxplot, can be seen that law major in University of Indonesia has participants average scores distributions which is quite higher than other majors - universities. Based on that, it can be concluded that it’s not easy to get into law major in University of Indonesia.
</p>
<br></br>
<br><br>

2. Second choices humanities-related majors and universities from participants who take humanities-type examinations.
<br></br>
 
- Top 10 second choices humanities-related majors and universities

<p align="center"> 
 <img src="images/top 10 second choices humanities-related majors and universities.png" /> 
 <br></br>
 Top 10 second choices humanities-related majors and universities
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Can be seen from picture above, that management, law and communication science majors is the top three most chosen majors in the second choice by participants. Meanwhile in universities section, there are Indonesia University of Education, Brawijaya University and Padjadjaran University which become top three most chosen universities in the second choice by participants who take humanities-type examinations.
</p>
 <br></br>
 
- Average score participants on top 10 second choices humanities-related majors and universities.

<p align="center"> 
 <img src="images/average score participants on top 10 second choices humanities-related majors and universities.png" /> 
 <br></br>
 Average score participants on top 10 second choices humanities-related majors and universities
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Based on pictures above, top 10 humanities-related majors has almost the same on participants average scores distributions. It could be said that majors has a same difficult level of competition. Meanwhile in universities section, there are two universities which has higher participants average scores distributions than other universities, that is University of Indonesia and Diponegoro University. It can also be concluded, that two universities has a more difficult level of competition than other universities.
</p>
<br></br>

- Top 5 second choices humanities-related majors - universities (with average score participants).
<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this section, I do more specific analysis to the participants data, that is grouping and analyzing data participants who chose the same humanities-related major and university as the second choice.
</p>

<p align="center"> 
 <img src="images/top 5 second choices humanities-related majors – universities (with average score participants).png" /> 
 <br></br>
 Top 5 second choices humanities-related majors – universities (with average score participants)
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Can be seen from barplot above, law major in Diponegoro University has most participants that is 471 number of participants, followed by communication science major in UPNV Jakarta with 384 number of participants, law major in Brawijaya University with 368 number of participants, etc. Meanwhile in the boxplot, can be seen that law major in Diponegoro University has participants average scores distributions which is quite higher than other majors - universities. Based on that, it can be concluded that it’s not easy to get into law major in Diponegoro University.
</p>
<br></br>

<br></br>

#### Analysis and Visualization on Participants Who Take Science-type Examinations
1. First choices science-related majors and universities from participants who take science-type examinations.
<br></br>
 
- Top 10 first choices science-related majors and universities

<p align="center"> 
 <img src="images/top 10 first choices science-related majors and universities.png" /> 
 <br></br>
 Top 10 first choices science-related majors and universities
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Can be seen from picture above, medical education major is the  most chosen majors in the first choice by participants, even the comparison is very far from other majors. Meanwhile in universities section, there are Brawijaya University, Gadja Mada University and Diponegoro University which become top three most chosen universities in the first choice by participants who take science-type examinations.
</p>
 <br></br>
 
- Average score participants on top 10 first choices science-related majors and universities.

<p align="center"> 
 <img src="images/average score participants on top 10 first choices science-related majors and universities.png" /> 
 <br></br>
 Average score participants on top 10 first choices science-related majors and universities
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Based on pictures above, medical education major has higher participants average scores distributions than other majors. It could be said that the major has a fairly difficult or high level of competition, so it’s not easy to get in that majors. Meanwhile in universities section, there are four universities which has higher participants average scores distributions than other universities, that is Bandung Institute of Technology, University of Indonesia, Sepuluh Nopember Institute of Technology and Gadjah Mada University. It can also be concluded, that four universities has a more difficult level of competition than other universities.
</p>
<br></br>

- Top 5 first choices science-related majors - universities (with average score participants).
<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this section, I do more specific analysis to the participants data, that is grouping and analyzing data participants who chose the same science-related major and university as the first choice.
</p>

<p align="center"> 
 <img src="images/top 5 first choices science-related majors – universities (with average score participants).png" /> 
 <br></br>
 Top 5 first choices science-related majors – universities (with average score participants)
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Can be seen from barplot above, medical education major in University of Indonesia has most participants that is 591 number of participants, followed by STEI major in Bandung Institute of Technology with 550 number of participants, psychology major in Padjadjaran University with 529 number of participants, etc. Meanwhile in the boxplot, can be seen that psychology major in Padjadjaran University has participants average scores distributions which is quite lower than other majors - universities. Based on that, it can be concluded that it’s easier to get into psychology major in Padjadjaran University than other top 5 majors - universities.
</p>
<br></br>
<br><br>

2. Second choices science-related majors and universities from participants who take science-type examinations.
<br></br>
 
- Top 10 second choices science-related majors and universities

<p align="center"> 
 <img src="images/top 10 second choices science-related majors and universities.png" /> 
 <br></br>
 Top 10 second choices science-related majors and universities
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Can be seen from picture above, medical education major is the  most chosen majors in the second choice by participants, it’s the same with the first choice section which has a fairly far comparison with other majors. Meanwhile in universities section, there are Brawijaya University, Diponegoro University and Sebelas Maret University which become top three most chosen universities in the second choice by participants who take science-type examinations.
</p>
<br></br>
 
- Average score participants on top 10 second choices science-related majors and universities.

<p align="center"> 
 <img src="images/average score participants on top 10 second choices science-related majors and universities.png" /> 
 <br></br>
 Average score participants on top 10 second choices science-related majors and universities
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Based on pictures above, medical education major has higher participants average scores distributions than other majors. It could be said that the major has a fairly difficult or high level of competition, so it’s not easy to get in that majors. Meanwhile in universities section, there are three universities which has higher participants average scores distributions than other universities, that is Gadja Mada University, University of Indonesia, Sepuluh Nopember Institute of Technology. It can also be concluded, that three universities has a more difficult level of competition than other universities.
</p>
<br></br>

- Top 5 second choices science-related majors - universities (with average score participants).
<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this section, I do more specific analysis to the participants data, that is grouping and analyzing data participants who chose the same science-related major and university as the second choice.
</p>

<p align="center"> 
 <img src="images/top 5 second choices science-related majors – universities (with average score participants).png" /> 
 <br></br>
 Top 5 second choices science-related majors – universities (with average score participants)
</p>

<p align = "justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Can be seen from barplot above, agrotechnology major in Brawijaya University has most participants that is 354 number of participants, followed by medical education major in Sebelas Maret University with 334 number of participants, psychology major in Sebelas Maret University with 307 number of participants, etc. Meanwhile in the boxplot, can be seen that medical education major in Sebelas Maret University has participants average scores distributions which is higher than other majors - universities. Based on that, it can be concluded that it’s not easy to get into medical education major in Sebelas Maret University.
</p>
<br></br>

