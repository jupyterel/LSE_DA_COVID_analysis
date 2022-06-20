# LSE_DA_COVID_analysis
LSE DA Course 2 Assignment

200 words: describe 

Did you notice anything interesting about the data? 

For inland UK we have data just for Moffat in Scotland in both data frames, which also present values equal to zero for intermediate region code and the recovered and hospitalised last entries. With print(cov.info()) I notice that Deaths, Cases, Recovered, and Hospitalised are missing 2 rows of data and those should be the Bermuda’s values which we are going to explore further. 

With cov.describe() why does it show e+01 ate the end? Why Q1 is zero for Deaths and Recovered? 
 

With print(vac.describe()) I notice that I get the minum, Q1, and Q2 as 0 for Vaccinated, First, and Second doses. This could happen because considering the change over time for vac we see that the vaccinations took place well after cases started (e.g. in Anguilla they started from 11/01/2021). 

I also noticed that Saint Helena, Ascension, and Tristan de Cunha are under Subregion Name “Northern Europe” and under “Other” in UK we have data only for Moffat in Scotland.  

The value counts for cov[‘Lat’] are only 632, and vac[‘First Dose’} gives me a length of only 3206 and row zero didplayd a value of 4284. As this function does not show the frequency of NaN values I suppose there are missing values 

Does the DataFrame have a default index?  
Yes, the Dataframe has a default index: the columns names. 

 

What are some of the initial insights you've discovered? 
I have calculated the IQR, lower and upper limit, and the calculated range for Cases, Deaths, Recovered, and Hospitalised. 

 

How has the number of vaccinated individuals changed over time? What might these changes indicate? Include reasons to support your rationale. 
In cov we first notice that we start with hospitalisations and then the other values raise too (see the case of Anguilla). Bermuda records the first case in 19/03/2021 and every other country presents its own peculiarities. 

 

On which date(s) are there values missing, and from which columns and rows are these values missing? Which states or provinces do the missing values belong to? 

There are 2 Nan values in the cov DataFrame (in the Province/State Bermuda) which I shall replace at row 875 and 876 on 21st and 22nd September 2020.  

Is there anything unusual about the filtered Gilbraltar DataFrame? Include reasons to support your rationale.  

First deaths by COVID-19 start and then cases as it would be like if there wasn’t an established method to record or check positive cases? 

Deaths, Cases, Recovered, and Hospitalisations are cumulative and there are more Hospitalisations than cases from row 4050 to 4167, after that Hospitalisations reduce abruptly, then raise again. We also have two zero values for Recovered and Hospitalised in the last 2 rows. 
