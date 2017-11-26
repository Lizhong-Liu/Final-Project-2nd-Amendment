# How mass shootings polarize gun control debate in the US
### **Final Project PPHA 30550** Introduction to Programming for Public Policy

Students: Camila Carrasco (@camilacd), Lina Pedraza (@linapp), Evelyn Sanchez (@EvelynaS)

Date: December 1, 2017

* The description of the entire analysis is included in the [Final Presentation](https://github.com/camilacd/Final-Project-2nd-Amendment/blob/master/GunControlPresentation.pdf).

* The code used can be seen in [Final Code](https://github.com/camilacd/Final-Project-2nd-Amendment/blob/master/FinalCode.ipynb)

* The first proposal submitted on October 31st is described in [First Proposal](https://github.com/camilacd/Final-Project-2nd-Amendment/blob/master/Proposal_Oct31.pdf). At first, the idea was to focus on Las Vegas shooting, but it was changed to the Texas shooting due to data availability.

* Additional documentation includes:
  - [stocks](https://github.com/camilacd/Final-Project-2nd-Amendment/blob/master/stock%20prices.xlsx)

IN SUMMARY:

#**1. What are the effects of the Texas Shooting on social media and financial markets?**

In this work we want to assess how an extreme event -like a shooting- affects the discussion about the right to bear arms in U.S. and how it relates with gun stocks. We will characterize tweets evolution regarding the 2nd Amendment, perform a Sentiment Analysis in Twitter assessing if some significant changes occur in the aftermath of the Texas shooting and finally we will study the correlation between the tweets and gun stock prices. 

#**2. Sources**

Twitter database

o   We use the streaming API, that allows to filter through tweets in real time.  
o   Query: "2nd amendment" + "Second amendment".
o   Total amount of tweets: 166.610.
o   Dates: Nov, 1st 2017 16:00 - Nov, 7th 2017 07:00.
o   More information: https://developer.twitter.com/en/docs/tweets/filter-realtime/overview.html

Bloomberg database (* these are some examples of guns stocks)

o   Sturm Ruger (RGR): https://www.bloomberg.com/quote/RGR:US 
o   American Outdoor Brands (AOBC): https://www.bloomberg.com/quote/AOBC:US 
o   Olin (OLN) : https://www.bloomberg.com/quote/OLN:US
o   Standard and Poor's 500 - S&P 500 (SPX): https://www.bloomberg.com/quote/SPX:IND

#**3. Analysis**

- Analysis over Tweets on 2nd Amendment and Gun Control
- Sentiment Analysis in Twitter
- Correlation between number of tweets and gun stocks

#**4. Problems**
- Json file of tweets
- Stock series have gaps each day during the market closure

#**5. Solutions**
- Imputation



