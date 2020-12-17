# ada-2020-project-milestone-p3-p3_xuehuapiaopiao
ada-2020-project-milestone-p3-p3_xuehuapiaopiao created by GitHub Classroom


1. ### Title

   Is political power a major factor of racial disparities in police stops?

2. ### Abstract 

   Recently, there are many researches assessing the racial disparities in policing in the United States, revealing the unfair treatment the minority drivers have faced. The reasons for such phenomenon might be various: racial discrimination, finance, crime rate, political power, etc. In this project, we will draw attention to political power and test its role in racial disparities. Specifically, we will first measure the political power of a group through its presence, voice and representation in politics. Through factor analysis we evaluate the political power quantitatively. Then by comparing stop/search rates with regard to the political power, we expect to find evidence that political power has a significant influence on police’s behavior. Finally, we try to analyze the effect of Obama’s victory in the president election of 2014, after which the inequalities in policing are expected to reduce.

3. ### Research Questions

   (1)     How to measure the political power of a group?
   
   (2)     To what extent does the political power affect racial disparities in traffic stops?
   
   (3)     How did the election of President Obama impact the racial disparities in traffic stops?

4. ### Proposed dataset 

   For policing stops, we mainly use the dataset released by the original paper, available at [https://openpolicing.stanford.edu](https://openpolicing.stanford.edu). Thanks to the Open Policing Project, we are able to use the raw data of almost the whole country.

   Moreover, we measure the political power in three aspects: 
   1) Presence, defined as the percentage of the population that is black, dataset available at [here](https://www.census.gov/topics/population/data.html); 
   2) Voice, defined as percentage of the voting population that is black, dataset available at [here](https://www.kesci.com/mw/dataset/5f894f59e48a3f0030286e2f); 
   3) Representation, defined as percentage of the local elected government that is black, dataset available at [here](https://www.kaggle.com/jerimee/north-carolina-voter-file?select=ncvhis_Statewide). 
   
   Note that we have referenced the eighth charpter in [1].

5. ### Methods

   In this part, we plan to use methods, like factor analysis, regression analysis, etc.

   Through factor analysis, we evaluate the political power quantitatively. Factor analysis is to use a few potential variables to explain the complex relationships that exist in observable variables. In other words, factor analysis breaks down each original (observable) variable into two parts, one of which consists of a few common factors shared by all variables; The other part is the so-called special factor part, which is the existence of a special factor that distinguishes a variable from other variables.

   There are many methods of factor extraction, most of which is principal component analysis(PCA). There are also other methods, such as the least Squares, Maximum Likelihood, Alpha Factoring, Image factoring, etc. In the future, we will consider the characteristic of our dataset, to test and choose the proper method. 
   
   Then in the part of regression analysis, we can compare the performance among different methods, such as maximum likelihood, gradient descent, and logistic. After that, we choose the best model to conduct further interpretation of our results. Comparing stop/search rates related to political power, we hope to discover that political power has a significant influence on the police’s behavior.

6. ### Proposed timeline

   *First week*: gather all needed data and understand them, and revise our objectives / methods if necessary depending on the data.

   *Second week*: utilize the methods mentioned before to analyze the data, change our methods if necessary. Analyze the results. Doing more experiments and analysis if necessary.

   *Third week*: at the end of this week we need to submit our report; creating and furnishing our plots / tables, and finish our report.

   *Final week*: make a video introducing our work.

7. ### Organization within the team

   * Screen and choose data from different states or cities
   * Understand and analyze the chosen dataset
   * Promote different hypothetical arguments
   * According to several hypotheses above, propose a feasible model to verify
   * Implement our model
   * Conduct the analysis and summary of our model
   * Reflection and correction
   * Sum it up into an article

8. ### Questions for TAs

    None at this stage. But we are more than delighted to have some suggestions to enrich our project and make it more meaningful to the practical world.

### Reference
[1] Baumgartner, F.R., Epp, D.A. & Shoub, K. Suspect Citizens: What 20 Million Trafc Stops Tell Us about Policing and Race (Cambridge Univ. Press, 2018)