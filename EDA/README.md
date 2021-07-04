# GLOBAL FOOD PRICE PROJECT PROPOSAL

## INTRODUCTION
Global Food Price is described as the average price of food commodities across countries, regions, and the global level. The level of food price usually depends on the food production process which includes food marketing and distribution. Fluctuations in the price of commodities can be multifactorial ranging from availability of natural resources for agriculture, market demand, energy cost, cost of production, exchange rate, government policy, and weather events amongst all. These factors have both positive and negative effects.

Starting from 2007-08 there was a surge in food prices, particularly in developing countries. This led to a global crisis causing political and economic instability as well as social unrest between poor and developed countries. 
The trend dropped and increased again in 2009 and 2010, reaching new heights in 2011 & 2012. Over the years prices dropped significantly reaching a lower point in March 2016 with a reduced Food and Agricultural Organization(FAO) food price index. The FAO Food Price Index (FFPI) is a measure of the monthly change in international prices of a basket of food commodities.
In recent times, global food prices rose in March 2021, which marked the 10th consecutive monthly increase with products like vegetable oil and dairy products leading the rise.

It is needful to say that at this point, the impact of food prices not only provides an indicator of the balance of agricultural produce and market demands but also has an impact on the cost of living,  food policies, and migration. While the producers benefit from the high food prices, consumers only benefit when the food prices are low. By implication, food prices now have an impact on food affordability, quality of a diet, undernourishment, and hunger.

In line with the United Nations Development Programme’s (UNDP) sustainable development goal 2, i.e., zero hunger we will be taking a closer look at the trends in global food prices, possible causes and effects of increased global food prices and offer our solution.




## PROBLEM STATEMENT
It can be observed from the previous discussion that global food price fluctuations can cause famine and large population shift. Hence, Identifying the drivers of global food prices and predicting  future changes in global food prices, could help in understanding food prices and its causal effects.



## AIM
Our research aims to understand and analyze fluctuations in global food prices and pair the outcome with currency fluctuations, weather patterns, and refugee movements. This will help us to build an end-to-end analysis and a food price prediction engine that will help the Government make better decisions on food policy adjustments, International bodies with planning of  food aid programmes, Individuals with planning and productivity in the advent of a potential food price crisis...

## OBJECTIVES
To achieve the above aim, we will:
Analyze available datasets to observe and make inferences about changing food prices, fluctuations, and the trend they follow.
Attempt to compare their correlation with factors such as currency fluctuation, weather patterns, and refugee movements.
Investigate which food item controls the trends of the majority of the food markets.
Use the best-performed model in predicting food prices and deploying it in a web application that can predict food prices.

## REVIEW OF PAST LITERATURE
Most of the recent research on Global Food Prices has centered around policy-making across nations and countries in addressing the issue. An article by ALNAP, it cited IFPRI/CGIAR, 2008 where it was stated that factors that have contributed to the global food price crisis are either cyclical, structural, or unique. Various World Organizations like WFP, UNOCHA/CERF, UNICEF, IMF, WORLD BANK, NEPAD, ADB, AU, WTO, etc have championed different policies towards mitigating the menace of the Global Food Prices crisis, especially through financial aids. Notable among them are FAO’s Procurement and distribution of seeds, fertilizers, and other inputs which have been carried out in 54 countries under the Food and Agriculture Organisation (FAO) Initiative on Soaring Food Prices (ISFP). FAO is also urging governments and the International community to implement measures in support of poor countries hard hit by food price increases, specifically to provide small farmers with improved access to inputs like seeds and fertilizers to increase local crop production (RHVP/Wahenga brief, 2008).

From a micro perspective, Nigeria as a country has had several policies both in present and in the past regarding mitigation of the food prices crisis. Policies like Operation Feed the Nation, Green Revolution, and presently FADAMA programs. These policies and programs have contributed little or none to solving the challenge of the food price crisis.

With regards to predictive modeling technique, Artificial Neural Network(ANN) algorithm and Time Series Forecasting algorithms like ARIMA have been used recently by researchers in this Global Food prices crisis domain. A Machine Learning Approach to Forecasting Consumer Food Prices, J. Jay Harris(2017), applied ANN in modeling Global Food Prices, which was significantly insightful. In this project, we shall also be exploring predictive modeling techniques as well as time series models in forecasting food prices.


## DATA COLLECTION
Data related to global food prices will be collected from the Open source database compiled by the World Food Programme and distributed by the Humanitarian Data Exchange. Data on currency fluctuations will be gotten from the World Bank’s open-source database on official exchange rates. Data on Refugee movements will be extracted from the  Refugee statistics of the United Nations High Commissioner for Refugees. Data on Weather patterns will be excerpts from the World Meteorological Organization.

## MACHINE LEARNING WORKFLOW

Data Volumes
         ↓
Data Ingestion
          ↓
Data Wrangling
          ↓
Data Cleaning
          ↓
Data preprocessing→ Stationarity check→ Time series modeling→forecasting
           ↓
Predictive modeling


## WEB APPLICATION  DEVELOPMENT  FOR THE MODEL
The end product of this Global food prediction engine will be in the form of a web app that can be accessed from anywhere as long as there is an Internet connection,
It will have a drop-down list to select the food categories, and a graph showing the trend of the price fluctuations over the years and the prediction over the next couple of months.
The web app will be built using the streamlit service which makes deploying models quick and easy. The model which would have been worked on and perfected is saved as a pickle file and a python script is created for the usage of the model, then using streamlit, the interface stated above is created in python, then connected and deployed for use.  


## References:
"World Food Situation". FAO. Archived from the original on 29 April 2011. Retrieved 24 April 2011.
 How do Food Prices Affect Producers and Consumers in Developing Countries?, ICTSD, Information Note Number 10, September 2009
 UN Food and Agriculture Organization (2009). The State of Food Insecurity in the World 2009. Rome.
 Rahman, M. Mizanur (11 August 2011). "Food price inflation: Global and national problem". The Daily Star.
 "FAO Food Price Index". FAO. Retrieved 2 May 2017.


## Group Trailblazers:
* Abiona Oluwafemi
* Roqeebat Olanrewaju
* Omeh Chukwuemeka
* Habeebullah Agbaje

## Terms
### Who is a refugee?
*Refugees are people who have fled war, violence, conflict or persecution and have crossed an international border to find safety in another country.They often have had to flee with little more than the clothes on their back, leaving behind homes, possessions, jobs and loved ones. 
Refugees are defined and protected in international law. The 1951 Refugee Convention is a key legal document and defines a refugee as:“someone who is unable or unwilling to return to their country of origin owing to a well-founded fear of being persecuted for reasons of race, religion, nationality, membership of a particular social group, or political opinion.” [link](https://www.unhcr.org/what-is-a-refugee.html)*

A refugee is a person who has fled their own country because they are at risk of serious human rights violations and persecution there. The risks to their safety and life were so great that they felt they had no choice but to leave and seek safety outside their country because their own government cannot or will not protect them from those dangers. Refugees have a right to international protection.

### Who is an asylum-seeker?
An asylum-seeker is a person who has left their country and is seeking protection from persecution and serious human rights violations in another country, but who hasn’t yet been legally recognized as a refugee and is waiting to receive a decision on their asylum claim. Seeking asylum is a human right. This means everyone should be allowed to enter another country to seek asylum.

### Who is a migrant?
There is no internationally accepted legal definition of a migrant. Like most agencies and organizations, we at Amnesty International understand migrants to be people staying outside their country of origin, who are not asylum-seekers or refugees.  

Some migrants leave their country because they want to work, study or join family, for example. Others feel they must leave because of poverty, political unrest, gang violence, natural disasters or other serious circumstances that exist there.
