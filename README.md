<h1>Gloabl Education Analysis</h1>

![global_education](https://user-images.githubusercontent.com/43104489/121780711-326b0a80-cbbf-11eb-9bd6-b5e182331d69.png)


<p>In this notebook, we explored and analyzed the Global education data and extract the meaning ful information out of it </p>

<h2> :floppy_disk: Data Description</h2>
The Data is hosted by the World bank on Global education.</br>
The DataSet has over 3,500 internationally comparable indicators that describe education access, progression, completion, literacy, teachers, facilities, population, and expenditure. </br>


<p>The quality of education can be measured by the OECD Program for International Student Assessment (or PISA) as well as equality of education. </br>
The data is stored from 1970 to the present also few predicted values are kept in the dataset up to 2100 and more the 200 countries have participated in it.
</p>

![missing_value](https://user-images.githubusercontent.com/43104489/121783871-cd1f1580-cbce-11eb-8325-3cb40e14d821.png)
<p>
This Graph clearly shows that the data is full of null values so we will only consider those columns which have the least number of null values, thus we selected years from 2000 to 2015 as our observable unit.
</p>



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Data Sets</h2>
<b> 1. df_country(EdStatsCountry.csv) </b></br>
<p>contains list of all countries that are present in the data (total of 241 countries); along with other features specific to the country like - Region, Income Group specific to the country etc</p>

<p><b>2. df_data(EdStatsData.csv)</b> </br>
contains each country, with list of indicators (3665 unique indicators); contains measurement value for each indicator from years 1970 to 2017; from 2020 to 2100 - contains projections</p>

<p><b>3. df_countryseries(EdStatsCountry-Series.csv)</b></br>
contains indicators and data sources for certain countries</p>

<p><b>4. df_footnote(EdStatsFootNote.csv)</b><br>
 contains the estimations and uncertainty bounds for each year - looks like some years are missing</p>
 
 <p><b>5. df_StatsSeries(EDStatsSeries.csv) </b></br>
 contains Series Code along with Topics for each Indicator Plus their long & sort definations</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Objectives</h2>

<p>:</p>

<p>1. Correlation between Expenditure on education as % of total government expenditure (%) and youth/adult literacy rate for countires with similar GDP per capita PPP.</p>

<p>2. How does India compare to it's neighboring countries or countries with similar GDP in it's literacy rate.</p>

<p>3. Variation in performance of Females and Males in PISA and TIMSS across years - for PISA - from 2000 to 2015; for TIMSS take 1995 - 2015 - consider only participating countries; data not available for all countries.</p>

<p>4. Relationship between internet users and literacy rate.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


