# **CUSTOMER CHURN ANALYSIS**

![purple-divider](https://user-images.githubusercontent.com/7065401/52071927-c1cd7100-2562-11e9-908a-dde91ba14e59.png)

<head>
<br>
<p>
This project is a real world dataset from a telecommunication company that gives customer details which are: usage patterns, demographics, and I checked for churned customers(i.e customers that left the company)and those that did not. The analysis includes the following steps: Cleaning and preprocessing, Exploration, Modelling, Visualization then Summary.
<style>
    .image-separate {
        display: block;
        margin: 0 auto;
        clear: both;
    }
</style>
<p><img style = "float: left;  margin : 25px 50px 25px 10px; width: 95%" 
src = "https://softwareequity.com/wp-content/uploads/2021/02/SEG_BlogHeader_CustomerChurn.png"; alt = "Customer Churn" class="image-separate">
</p>
</head>
<br>
The analysis was carried out based on the following aim:
<ol>
    <li>Cleaning and preprocessing the dataset</li>
    <li>Exploratory Data Analysis.</li>
    <li>Convey information through Data Visualisation that affects customer churn.</li>
    <br>
    <ol>
        <li><b>Cleaning and preprocessing the dataset:</b>
        <p>This process is a necessity and also a prerequisite to other steps of Data Analysis. It consists of viewing the properties,statistical summary, size and shape of the data. The major aim of this process includes: 
        <ul style= 'list-style-type:circle'>
            <li>Remove Duplicates: Duplicated values will skew analysis performance and to avoid this it is always best to check for duplicated values using variable <code>.duplicated.sum()</code> (i.e. check for the count of duplicated values) and drop them.</li>
            <li>Treat Missing values: Spot missing values, then it is either you drop the rows affected or use the <code>fillna</code> method, with the use of mean and median to fill missing values.</li>
            <li>Convert Data types: Data type that does not rhyme with the pattern of the feature(float, int, string, e.t.c)e.g. a date in string format or a float in an object format should be converted to the right data type.</li>
            <li>Detect Outliers: Outliers can be figured through the use of quartile range boundaries, box plot and scatter plot. This affects the standard deviation.</li>
            <li>Detect Outliers: Outliers can be figured through the use of quartile range boundaries, box plot and scatter plot. This affects the mean of the dataset and this tends to affect the standard deviation.</li>
            <li>Analysis of Qualitative Datasets: Categorical data can be encoded through <code>OneHotEncoder</code>, <code>LabelEncoder</code>, which are <code>sckit-learn</code> algorithms and can also be performed with <code>Pandas</code> <code>get_dummies</code> function.</li>
        </ul>
        </p>
        </li>
        <br>
        <li><b>Exploratory Data Analysis: </b>
        <p>This gives you the chance to ask questions about the dataset and involves scanning through the data for quantitative and qualitative features.
                <ul style= 'list-style-type:circle'>
                <li>Perform Descriptive Statistics: Calculating the statistical summary for quantitative/numerical features with the <code>describe</code> function, which displays the count, mean, std, min, 1st quartile, median, 3rd quartile, maximum values of wach numerical feature.</li>
                <li>Analyse the distribution of categorical features: distribution includes counts, ratios, e.t.c.</li>
                <li>Correlation: identify the relationship of numerical features through heatmaps and scatter plots.</li>
                <li>Hypothesis Testing: with the use of t-test to help make inferences about the data and gain insights from the result.</li>
                </ul>
                </p>
                </li>
                <br>
                <li><b>Convey information through Data Visualisation:</b>
                <p>Showcasing the pictorial result of the cleaned and analysed dataset. It comprises of:
                <ul style= 'list-style-type:circle'>
                <li>Identifying Trends: this is done through visualisation of scatter plots, line plots and bar plots</li>
                <li>Spread of Categorical and Numerical values: with the use of bar plots, histograms to validate the distribution of the values.</li>
                <li>Distribution of Numeric values: the use of scatter plots, histograms, and density plots.</li>
                </ul>
                </p>
                </li>
            </ol>
        </ol>
<br>
<p>The following visualisation libraries were used:
<ul style='list-style-type:disc'>
    <li><code>plotly</code></li>
    <li><code>matplotlib</code></li>
    <li><code>seaborn</code></li>
</ul>
</p>

</p>