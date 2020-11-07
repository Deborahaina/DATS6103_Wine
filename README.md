# DATS6103_Wine
Data Source  
The orginial data was obtained from Kaggle posted by Zack Thoutt.He scraped the website winemag.com,(a wine enthusiasts website) after watching 'somm', a documentary on master sommelier(the ability to identify wines through blind tasting).This data is available under the Creative commons,Attribution and Share-Alike license and I do not own this data.It is being used for educational purposes only.Data collected include Description, Wine variety, Page Title, Country of origin, Price, Points, Province, Region, Winery,Taster's name, Taster Twitter Handle.

Additional Columns Added
I dropped unnecesaary columns from the datasets.I extracted the year column from the title column. There appeared to be a recurring pattern of the year being mentioned in almost all if not all of the wines collected in this datasets.I also sent requests to Google's api endpoint to retreive latitudinal and longitudinal points which was used for plotting data.I also created a column called category which included Red and White wines (Arguably there are 5 main wine categories Red, White,Sparkling,Blush,Fortified).For the sake of our analysis it was simplified to wither red or white.The cleaned dataset was saved and exported as a new csv file and also stored in a sqlite database.

Initial Analysis
We also take a look at the person who identified the most wine in descending order. Roger Voss identified the most wine, 18243 followed by Michael Schachner 14306 and third is Virgina Boone 9402.In all there are 19 wine tasters in this datatset.
I plotted a boxplot to see the distribution of the wine prices throughout the datasets. There is wine as cheap as $4 and wine as expensive as $3300. The average winr price is $37.64.





