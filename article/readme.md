# Article

Please host the drafts and all the materials, including the final version, related to your article in this folder.
Crunching the Numbers: A Comprehensive Data Analysis of the Indian Startup Ecosystem from 2018–2021.

Introduction:

Over the last 4 years, India’s start-up ecosystem has been thriving, with entrepreneurs and investors equally looking for the next big idea to disrupt established industries and generate new opportunities. While concepts, creativity, and execution are necessary for a start-up to flourish, they are inadequate on their own. Investor — funding is often necessary to turn those ideas into reality, grow the business, and make a long-term effect. In this article, we will investigate the funding received by start-ups in India from 2018 to 2021, using a dataset of separate CSV files containing information about the start-ups, funding amounts received, and investors.

Methodology:

To begin the analysis, I installed and imported all the required libraries for the analysis. The individual datasets for the project ranging from 2018 to 2021 were loaded into the Jupyter Notebook. I then performed Exploratory Data Analysis (EDA) commencing with a data overview on each of the datasets to gain an idea of the column names, non-null counts, and datatypes present in the datasets. I proceeded to the preprocessing phase of the project where I cleaned each of the data sets individually to remove any duplicates or incomplete information, employed the use of CrunchBase to fill some of the missing rows, and verified the datatype of each row. I then aggregated the individual CSV files for each funding year. I then dropped all columns that were of the least relevance to the analysis.

To begin our analysis, we loaded all the individual dataset from 2018 to 2021. I then perfomed a dataset overview on  each of the datasets to have an idea of the column names , non-null counts and datatypes . I proceeded to the preprocessing phase of the project  where  I cleaned the data to remove any duplicates or incomplete information , employed the use of  CrunchBase to fill in the missing rows  and verified the datatype of each row . I then  aggregated  the individual csv files for each funding year. I then dropped all columns that  were of least relevance  to  the analysis. 

 I conducted a univariate analysis of the combined data which revealed some discrepancies such as missing values stage, sector, and HeadQuaters columns. A boxplot visualization also highlighted some outliers in the amount column. I filled in this missing data using the mode for the sector and stage columns. The median was used to fill in missing values in the amount column. Whilst the geolocator helps to fill in the missing values for the Headquarters columns. I continued with my bivariate analysis, multivariate analysis, and feature processing

I explored the data using different statistical and data visualization tools to identify patterns and trends in the funding received by Indian start-ups over a four-year period. I used my analysis to answer the various questions I related to the dataset.
Finally, I save data and uploaded it in PowerBI using Python scripting where I plotted different graphs to provide deep understanding and insight revealed from our analysis.

Results:

The analysis revealed several key findings about start-up funding in India:
Total funding received: Over the four-year period from 2018 to 2021, start-ups in India received a total of $89 Trillion in funding. This represents a significant increase from previous years and highlights the growing interest in the Indian start-up ecosystem. Therefore an average of $31M was invested in the Indian startup ecosystem each year from 2018 to 2021.
