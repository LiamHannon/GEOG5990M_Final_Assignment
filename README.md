# GEOG5990M_Final_Assignment
# To what extent does an ageing population affect house prices in Leeds?
## Introduction and aims

An increasing ageing population is a new phenomenon that the world is facing in the 21st century characterised by low fertility rates, decreasing late-life mortality, and increasing migration (Harper and Leeson, 2008). it is estimated that by 2050, people aged 60 and over will double to over 2 billion (WHO, 2022, Harper and Leeson, 2008). This brings with it many implications, some positive such as increasing productivity in some countries (Healy, 2024) and some negative, such as an increase in informal caregiving (Ratcliffe et al., 2012). In this study, the focus is on the relationship that an ageing population has on house prices, more specifically in the Leeds area of the UK. 

The effect that ageing has on real estate and land prices can be seen more obviously in Japan because Japan has the fastest-growing rate of ageing population out of any developed country in the world (Saita et al., 2016). The findings by Saita et al. (2016) were that an ageing population has a negative effect on house prices in Japan. Takáts (2012) also found in their study of 22 advanced economies that ageing will decrease house prices by around 80 basis points per year. A third study in Australia concurs with these results, whereby ageing could affect property prices negatively by up to 27% over 2008-2050 (Guest and Swift, 2010).

The aims of this study are to establish first the average percentage per year differences between house prices and ageing separately. This derives the general trend of both datasets and creates averages for each LSOA in Leeds. These two results are then correlated to show their relationship to one another, with a respective r value which derives the strength of correlation. The final aim is to map where in Leeds there is a large increasing ageing population and where there is a low or even negative ageing population.

The intended audience is the general public and business owners in Leeds who are looking to purchase property. This would help them make an informed decision as to where in Leeds would be sensible to purchase property assets given the relationship between ageing and property prices.

Code is used to clean the data from numerous CSV files to create 2 variables. The first for an average percentage difference of house prices over 10 years (2013-2022), the second for an average percentage difference between over 65s (ageing population). The variables are correlated with one another and a graph showing this is output along with the r value for correlation. A map is then output showing the distribution of the average percent difference in ageing population in Leeds per LSOA.

The code is found in the ipynb file, all other data sources are listed below.


## Data

House price data and shapefile datafiles have been clipped to align with Github 25mb cap on file uploads.
full datasets for each variable and shapefile afre found below

Ageing:
ONS. 2024. Lower layer Super Output Area population estimates (supporting information) - Office for National Statistics. [Online]. [Accessed 9 May 2024]. Available from: https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/lowersuperoutputareamidyearpopulationestimates. 

House Prices:
ONS. 2024. House price data: annual tables - Office for National Statistics. [Online]. [Accessed 9 May 2024]. Available from: https://www.ons.gov.uk/economy/inflationandpriceindices/datasets/housepriceindexannualtables2039. 

LSOA Shapefile:
UK Data Service 2022. 2011 census geography boundaries (Lower Layer Super Output Areas and data zones). UK Data Service. [Online]. [Accessed 9 May 2024]. Available from: https://statistics.ukdataservice.ac.uk/dataset/2011-census-geography-boundaries-lower-layer-super-output-areas-and-data-zones. 

## Acknowledgements
-	Chat GPT 3.5 was used in some of the creation and error handling of this code. Comments have been made when used
-	Stack overflow was used for some of the creation of this code. Comments have been made when used.


## References 

Chat GPT 3.5 n.d. Chat GPT 3.5. [Online]. [Accessed 9 May 2024]. Available from: https://openai.com/. 

Guest, R. and Swift, R. 2010. Population ageing and house prices in Australia. Australian Economic Review. 43(3), pp.240–253. 

Healy, J. 2004. The benefits of an ageing population [Online]. Canberra: Australia Institute. [Accessed 13 May 2024]. Available from: https://library.bsl.org.au/jspui/bitstream/1/576/1/The%20benefits%20of%20an%20ageing%20population,%20Healy%20Judith.pdf. 

Harper, S. and Leeson, G. 2008. Introducing the Journal of Population Ageing. Journal of Population Ageing. 1(1), pp.1–5. 

Ratcliffe, J., Lester, L.H., Couzner, L. and Crotty, M. 2012. An assessment of the relationship between informal caring and quality of life in older community-dwelling adults - more positives than negatives? Health &amp; Social Care in the Community. 21(1) ,pp.35–46. 

Saita, Y., Shimizu, C. and Watanabe, T. 2016. Aging and real estate prices: Evidence from Japanese and US Regional Data. International Journal of Housing Markets and Analysis. 9(1), pp.66–87. 

Schober, P., Boer, C. and Schwarte, L.A. 2018. Correlation coefficients: Appropriate use and interpretation. Anesthesia & Analgesia. 126(5), pp.1763–1768. 

Stack Overflow. n.d. Where developers learn, share, & build careers. Stack Overflow. [Online]. [Accessed 10 May 2024]. Available from: https://stackoverflow.com/. 

Takáts, E. 2012. Aging and house prices. Journal of Housing Economics. 21(2), pp.131–141. 

WHO. 2022. Ageing and health. World Health Organization. [Online]. [Accessed 9 May 2024]. Available from: https://www.who.int/news-room/fact-sheets/detail/ageing-and-health. 
 
