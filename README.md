# 539Project
ECE 539 Project Proposal: GDP vs Fertility by Country
Declan Smith dsmith73@wisc.edu, __, __






































1. Overview: 
Our aim of this project is to determine if we can predict a country’s gross domestic product and its fertility rate. 
2. Background: Explain a bit background of this project, what have been done before, what is the state of the art outcome (A good place to cite a couple of most relevant works, including URLs, citation to references, etc.)
Fertility in high(3) income countries has been declining for years. This is due to high child costs and the decreased need for big families in well developed countries. Inversely, the lower(4) a country’s gdp the more the fertility rate is higher. It also had some issues with recording due to a number of factors we will explore throughout. This will come into play as we try to mitigate the noise that comes with this data and plot through the trends in order to classify countries correctly. 
3. Statement of Work
3-1. Datasets: where does it come from? What is in this dataset? Your preliminary inspection of the datasets and what others have said about this dataset. 
The data starts from 1960-present. Two of the datasets come from the World Bank. One of them captures the gdp of each country by their country domain. The other shows total fertility rate; representing the number of children that would be born to a woman if she were to live to the end of her childbearing years and bear children in accordance with age-specific fertility rates of the specified year. Some countries are missing either one or both of the features. 
The sources are:
( 1 ) United Nations Population Division. World Population Prospects: 2022 Revision. ( 2 ) Census reports and other statistical publications from national statistical offices, ( 3 ) Eurostat: Demographic Statistics, ( 4 ) United Nations Statistical Division. Population and Vital Statistics Reprot ( various years ), ( 5 ) U.S. Census Bureau: International Database
3-2. Method: What do you plan to do? What existing similar works have you found so far? What has been accomplished so far (prior work). What do you plan to do? Why do you want to do this? 
I plan to take all countries and match them based on name. I will isolate and discard unusable ones. I may also use regression analysis to predict which country comes next. And we can use KNN to group like terms. This is an exciting project because it combines real world data with a global mindset. The tools learned in this course will help us learn on a global scale. 
3-3. Outcome and Performance evaluation: What outcome do you anticipate in doing this project? What criteria (performance, costs) will be used to gauge quantitatively whether  the project is successful? 
We will gauge our progress on the accuracy of a correct prediction of a country's GDP ranking based on its fertility rate and vice versa. There are many different countries, so our time spent will also be important. Many countries will be grouped similarly so the training will have to be pretty extensive. A KNN classification of 70 percent and a linear regression accuracy of 80 percent. 
4. Project Plan
Break down the project into a set of tasks and provide a Gantt chart that schedules the beginning and end of each task within a duration of 7 weeks. Potential tasks may include (but not limited to) setting up an environment (e.g. GitHub account), data pre-processing, programming (specifying specific programming tasks as detail as possible), progress report and final report preparation, project presentation preparation, etc.
Each project will be conducted using a GitHub project. The project plan section should include the URL link to the GitHub project and will provide read access by the instructor and the TA. 


Weeks
1
2
3
4
5
6
7
Pre-Processing
O












Analysis


O










Models




O
O






Improvements








O
O
O



5. References
Give a numbered list of research papers, reports, blogs that you cite in your proposal. 


https://data.worldbank.org/indicator/SP.DYN.TFRT.IN
https://data.worldbank.org/indicator/NY.GDP.MKTP.CD
https://www.imf.org/en/Publications/fandd/issues/Series/Analytical-Series/new-economics-of-fertility-doepke-hannusch-kindermann-tertilt
https://www.imf.org/en/Publications/fandd/issues/Series/Analytical-Series/new-economics-of-fertility-doepke-hannusch-kindermann-tertilt 
Ahmed, Arshad. (2015). Using Machine Learning to predict fertility rates based on economic indicators. 10.13140/RG.2.1.3960.7444.  
6. Contributions
Each team member will write (no more than 50 words) his/her contributions to the proposal preparation. 


Declan: I brainstorm with my group members to find a topic we all are interested in. I then analyzed two data sets and wrote their descriptions. I also helped with the gantt chart.  


