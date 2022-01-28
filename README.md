# Covid Policy and Data Science 
`EDA` `Preprocessing Ideas` `Analytics and Visualisation `

## Introduction 
- Covid has generated so much data so rapidly it's frankly mind boggling.
- Although a lot of data is not really usable without cleaning or some sort of preprocessing. 
- This page is just experiments on Covid Data while I learn DS/ML stuff. 






## Experiments 
|Experiment|Date|Description|
|-|-|-|
|[NHSPI Correlation](./experiments/NHSPI_correlation.ipynb)|28 January 2022|Correlating the NHSPI with vaccinations and case peaks|




## Ideas 

1. Validity of NHSPI, [this](https://www.cambridge.org/core/journals/prehospital-and-disaster-medicine/article/validity-of-the-national-health-security-preparedness-index-as-a-predictor-of-excess-covid19-mortality/F70209423461F6A9C2522CE140DCD520#metrics) paper says against but is it ? It's basically the first paper on google scholar when you put in the terms `nhspi covid`. Does the index deserve this ? 
    - Now we have information on the fact that a lot of serious covid cases and deaths are a result of comorbidities so to just use the index and deaths in the first 6 months is a little disingenuous I think. 
    - In order to actually give the index a fair shot, we somehow need to adjust the index based on the demographic of the state or just do states with favorable demographics or for context, those with unfavorable. 
    - __EXPERIMENT__ : 
        - Make a list of states with similar demographics : Factor in obesity, diabetes, age, other state wise health factors.
        - Now with a level playing field, do the same test the paper runs but on each of the sets of states which come out similar and then look at the result. 
    - __Doubts regarding this approach__
        - Should policy and goverment action/inaction also be somehow put into the equation ? HOW. 
        - Even if my experiement comes up with the same result, is it valid or am I missing something else. 
        - Covid is a supremely nice test of this index, generally speaking. Is there any way to make it so that the test has very little bias and still proves/disproves the validity of this index ?  
    
    - _Slice of life Questions_ 
        - Do the feelings of people working to make the index hurt when they see this paper? 
        - How much would they value a rebuttal, financilly speaking ofc. [More Capitalist than slice of life but meh.]
        - This is all too surface level and the index is super in depth so does anyone really care? 