# Project 2: NYC Housing Litigation Analysis

## ** To quickly see the Shiny app of the analysis, click the link: https://sh3799.shinyapps.io/HousingLitigations/

+ **Project summary**: 

This app contains three topics, including litigations overview, buildings details, and respondents search. We used [Housing Litigations](https://data.cityofnewyork.us/Housing-Development/Housing-Litigations/59kj-x8nc) dataset from NYC OpenData. The analysis covers NYC buildings ID, location information, and related respondent information between year 2000 and 2019. This topic is excluded from “suggested" list.

The first tab shows litigations overview by case types(i.e.Comprehensive) and open year(i.e.2019) selected. By choosing specific case type and status, a colored map is produced based on different zipcodes. The deeper the color, the higher frequency litigations exist in that area. Therefore, users could compare the difference in color directly from map to get information about litigations frequency.

The second tab exhibits detailed litigations information of each building. By setting number of litigations as condition for a building to show on map, user may click on the blue circle to detailed information of that building such as address, number of litigations, and most recent repondents. Addtionally, clicking on the See/Update Building Details bottom will display two graphs below; one is about trend of litigations amount through years and the other is proportion distribution of case types and status.

The third tab takes care of respondents. User might type in the name of respondent and then the location of related building would show on map. Besides, a histogram for number of building vs. number of litigations is generated.

The last two tabs are Appendix. Appendix A is about case development and Appendix B is housing litigation procedure, which illustrate structure of how litigation proceed further to help users better understand case types. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── app/
├── lib/
├── data/
├── doc/
└── output/
```

Please see each subfolder for a README file.

