<h1>This is first notebook , for fuel emission eda</h1>

<h3> In this notebook I(harsh joshi) tried to perform eda on fuel Emissiondata</h3>
<p> Data is obtained through <a herf="https://www.kaggle.com/datasets/ahmettyilmazz/fuel-consumption">Kaggel</a></p>

<h3>Objectives</h3>
<p>The objective of this project is to analyze the fuel consumption data and identify the correlation between fuel consumption, engine size, and emissions. The insights gained from this analysis will provide valuable information on the impact of different factors on emissions levels.</p>

<h3>Steps i followed </h3>

<p>
    <ul>
        <li><p>Loading the required data manipuation libraries and data visualisation libraries</p></li>
        <li><p>Importing the dataset</p></li>
        <li><p>Exploring the data set</p></li>
        <li><p>Creating visualisation</p></li>
        <li><p>Finding Co-relations and Trends in data</p></li>
        <li><p>Documentation</p></li>
    </ul>    
</p>


<h3>Insights from EDA:</h3>

<ol>
    <li><strong>FUEL CONSUMPTION, HWY (L/100 km), COMB (L/100 km), ENGINE SIZE, and CYLINDERS</strong> have a <u>direct positive relationship</u> with <u>EMISSIONS</u>, indicating that higher values in these factors correspond to higher emissions.</li>
    <li><strong>COMB (mpg)</strong> exhibits an <u>indirect negative relationship</u> with <u>EMISSIONS</u>, suggesting that higher miles per gallon (better fuel efficiency) lead to lower emissions.</li>
    <li>The dataset spans from <strong>2000 to 2022</strong>. The histogram shows an increasing trend in car number over years until <strong>2007</strong>, followed by a plateau from <strong>2007 to 2018</strong>, and a decline thereafter. The year with the highest frequency of car records is <strong>2014</strong>.</li>
    <li>The pie chart reveals the distribution of fuel types in the dataset. <strong>Fuel type X</strong> holds the majority share at <strong>52.4%</strong>, followed by <strong>fuel type Z</strong> at <strong>41.3%</strong>. <strong>Fuel type N</strong> has the smallest presence.</li>
    <li>The popular fuel types X and Z are predominantly used in the most common engine sizes, such as <strong>2.0 and 3.0</strong>, suggesting a strong association between fuel type preference and engine size selection.</li>
    <li><strong>HWY (L/100 km):</strong> As highway fuel consumption increases, emissions tend to increase, indicating a positive correlation.</li>
    <li><strong>COMB (L/100 km) and FUEL CONSUMPTION:</strong> Both factors exhibit a positive relationship with emissions, confirming their influence on emission levels.</li>
    <li><strong>COMB (mpg):</strong> Higher miles per gallon (better fuel efficiency) correspond to lower emissions, suggesting a negative correlation.</li>
    <li>The line chart demonstrates a <strong>declining trend in average emissions from 2002 to 2014</strong>, reaching its lowest point in <strong>2014</strong>. However, there has been an upward trend in average emissions since then, with a notable spike in <strong>2014-2015</strong>.</li>
    <li>There is a general trend indicating that <strong>higher engine sizes</strong> are associated with <strong>higher emissions</strong>, providing insights into the impact of engine size on emissions.</li>
    <li>Among vehicle classes, <strong>SUVs have the highest emissions</strong>, followed by <strong>compact cars, midsize cars, pickup trucks, and subcompact cars</strong>.</li>
</ol>

These insights from EDA highlight important relationships and trends in the data, providing valuable information about fuel consumption, emissions, engine size, and vehicle classes.
