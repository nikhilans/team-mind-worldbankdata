<h1>World Bank Global Education Analysis</h1>

![global_education](https://user-images.githubusercontent.com/43104489/121780711-326b0a80-cbbf-11eb-9bd6-b5e182331d69.png)


<p>In this notebook, we explored and analyzed the World Bank Global Education data and extracted meaningful insights out of it </p>

<h2> :floppy_disk: Data Description</h2>
The Data is hosted by World Bank on Global education.</br>
The DataSet has over 3,500 internationally comparable indicators that describe education access, progression, completion, literacy, teachers, facilities, population, and expenditure. </br>


<p>The quality of education can be measured by the OECD Program for International Student Assessment (or PISA) as well as equality of education. </br>
The data is stored from 1970 till present. Also few a projetion values are available in the dataset up to 2100 and more than 200 countries have participated in it.
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

<p>1. Correlation between youth/adult literacy rate for countries with similar GDP per capita PPP. </br>
Expenditure on education as % of total government expenditure (%) across different countries. </p>

<p>2. How does India compare to it's neighboring countries with respect to Gross Enrolment Ratio.</p>

<p>3. Variation in performance of Females and Males in PISA from 2000 to 2015 </br>
      Performance in PISA for year 2015 across different countries </br>
      Performance in TIMSS for year 2015 across different countries </p>

<p>4. Relationship between internet users and literacy rate.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Contributors -->
<h2 id="Contributors"> :scroll: Contributors</h2>

Mukund Jha </br> [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/estoymukundjha/Global-education-analysis)</br> </br>
Nikhila N S </br> [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nikhilans/global-education-analysis) </br> </br>
Sriram Sureshkumar </br> [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sriram1717/World-Bank-Global-Education-Analysis.git) </br> </br>
Yogesh Patil </br> [![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yogesh-8998/World-Bank-Global-Education-Analysis)
