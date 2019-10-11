# Problem Statement

How does the participation rate for SAT fare against the ACT. How can we improve SAT's participation rate and which states should we first focus on.


# Executive Summary

SAT was created to standardize college admissions procedures and increase access to higher education. In 1959, ACT was introduced and SAT faced competition. SAT went through a few major revisions throughout the years, with the lates in 2016, reversing some of the changes made earlier in the years in response to competition from ACT.
In this analysis, we are comparing how SAT fare against ACT in participation rates, look at causes that influence major increase in participation, and ultimately recommend actions to take and states to focus on to increase the participation for SAT. Data was obtained internally and also through public available records.
From the data, it is observed that when ACT's participation rate increases, SAT's decrease. And when SAT's participation rate increase, the total score also decreases. A year on year comparison was made and states with more than 20% increase in particiation rates are Colorado, Illinois and Rhode Island for SAT and Ohio for ACT.
The reason for the increase for Colorado and Illinois is due to a change in state regulation switching from ACT to the SAT.
Rhode Island do not mandate the SAT or ACT and there are 6 schools in Rhode Island which have made submitting SAT or ACT optional. Rhode Island is also one of the 10 states that give SAT to students for free.
It is recommended that we focus we do not try to influence too many states at the same time, or increase the participation rate drastically as it will affect our national average total score.
Ohio is already paying for students taking the SAT or ACT. We can work with the state Department of Education to make SAT mandatory, Ohio has a healthy 2018 participation rate and increasing their their participation rate will have manageable impact on the total scores.


# Outside Research

Colorado, Illinois and Rhode Island has more than 20% year on year growth rate for SAT. Below are the information gathered on the possible causes for the increase. Colorado Since 2001, Colorado juniors has been required to take the ACT In 2015, the state Department of Education chose The College Board SAT has a reputation of being more reason-based and focused on critical thinking compared to ACT being more fact-recall test _[source](https://www.chalkbeat.org/posts/co/2015/12/23/goodbye-act-hello-sat-a-significant-change-for-colorado-high-schoolers/)_
Illinois For the past 15 years, Illinois has been giving students the ACT The College Board won a bid with the State High school juniors will not be charged for taking the SAT Free college entrance exam has been popular _[source](https://www.chicagotribune.com/news/ct-illinois-chooses-sat-met-20160211-story.html#targetText=Illinois%20moves%20ahead%20with%20new%20testing%20plan%2C%20replacing%20ACT%20with%20SAT&targetText=It's%20official%2C%20according%20to%20the,into%20Illinois%20public%20high%20schools)_
Rhode Island All the flagship universities in the state have held on to the SAT as a prerequisite for admission, Rhode Island is also one of the 10 states that give the SAT to students for free 6 Schools in the Rhode Island have made submitting ACT or SAT scores optional for college admission 
_[Source](https://www.providencejournal.com/news/20181025/with-sat-required-ri-sees-jump-in-participation-decline-in-scores)_
_[Source](https://www.providencejournal.com/news/20180625/sat-requirement-waning-in-ri-and-nationally--poll)_


# Conclusions and Recommendations

Based on your exploration of the data, what are you key takeaways and recommendations? Choose one state with a lower participation rate and provide a suggestion for how the College Board might increase participation amongst graduating seniors in this state. Are there additional data you desire that would better inform your investigations?
It is recommended that we focus we do not try to influence too many states at the same time, or increase the participation rate drastically as it will affect the national average total score.
We can work with the the state's Department of Education to mandate the state to participate in SAT.
Ohio is already paying for students taking the SAT or ACT. We can work with the state Department of Education to make SAT mandatory, Ohio has a healthy 2018 participation rate and increasing their their participation rate will have manageable impact on the total scores.


# Data Dictionary

|Entity|Attribute(Column Name)|Data Type|Index(Y/N)|Description|
|---|---|---|---|---|
|df_sat2017|state|String|Yes|Index for the dataframe, show state name|
|df_sat2017|sat2017_participation|Integer|No|Shows State Participation Rate for SAT|
|df_sat2017|sat2017_evidence_base|Integer|No|Shows State Average Score for Evidence-Based Reading and Writing|
|df_sat2017|sat2017_maths|Integer|No|Shows State Average Score for Math|
|df_sat2017|sat2017_total|Integer|No|Show State Average Total, value is determined by evidence_base + maths
|df_act2017|state|String|Yes|Index for Data Frame, show state name|
|df_act2017|act2017_participation|Integer|No|Show State Participation Rate for ACT|
|df_act2017|act2017_english|Float|No|Show State Average Score for English
|df_act2017|act2017_maths|Float|No|Show State Average Score for Math
|df_act2017|act2017_reading|Float|No|Show State Average Score for Reading
|df_act2017|act2017_science|Float|No|Show State Average Score for Science
|df_act2017|act2017_composite|Float|No|Show State Average Composite Score, value is determined by (English + Maths + Reading + Science) / 4