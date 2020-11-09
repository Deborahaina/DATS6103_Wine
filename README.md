<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4259227.svg)](https://doi.org/10.5281/zenodo.4259227)


# DATS6103_Wine
Data Source  
The orginial data was obtained from Kaggle posted by Zack Thoutt.He scraped the website winemag.com,(a wine enthusiasts website) after watching 'somm', a documentary on master sommelier(the ability to identify wines through blind tasting).This data is available under the Creative commons,Attribution and Share-Alike license and I do not own this data.It is being used for educational purposes only.Data collected include Description, Wine variety, Page Title, Country of origin, Price, Points, Province, Region, Winery,Taster's name, Taster Twitter Handle.

Additional Columns Added     
I dropped unnecesaary columns from the datasets.I extracted the year column from the title column. There appeared to be a recurring pattern of the year being mentioned in almost all if not all of the wines collected in this datasets.I also sent requests to Google's api endpoint to retreive latitudinal and longitudinal points which was used for plotting data.I also created a column called category which included Red and White wines (Arguably there are 5 main wine categories Red, White,Sparkling,Blush,Fortified).For the sake of our analysis it was simplified to wither red or white.The cleaned dataset was saved and exported as a new csv file and also stored in a sqlite database.

Initial Analysis        
We also take a look at the person who identified the most wine in descending order. Roger Voss identified the most wine, 18243 followed by Michael Schachner 14306 and third is Virgina Boone 9402.In all there are 19 wine tasters in this datatset.
I plotted a boxplot to see the distribution of the wine prices throughout the datasets. There is wine as cheap as $4 and wine as expensive as $3300. The average winr price is $37.64.

Visualizations
We plot a correlation matrix to see if there is any correlation between price, year and wine grade. There seem not be a correlation between year and price of wine but we identify a strong correlation between grade of wine and price of wine.

Our first analysis is to take a look wine prices versus by wine grade.We see a progressive linear trend, the higher the grade the more expensive the wine is. 
Second analysis is to take a look at wine prices by the year the wine was produced. There is no significant trend here but we see that older wines are on average more expensive than recent wines. 
Third analysis is to take a look at wine prices by country of origin.
The last analysis is to look at the number of wineries per country.
We perform the same analysis again but this time, our focus will be on the United States

Conclusions          
The country with the most wineries is the United States.   
The most expensive wine in absolute value is from France worth $3300.   
The most expensive wine on average is from England.   
The higher the grade of wine, the more expensive the wine is.   
On average older wines, that is wines produced in the 1980's are more expensive than the ones produced recently.   
The state with the most wineries in the US is California.  
The most expensive wines on average in the US is from California.  





