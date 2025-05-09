# PDS-Assgn-3-SP25

<p><strong>Data Link:</strong></p>
<a href='https://app.box.com/s/7qv44umhw0vnzgmoe9krfkfkv5kf2atv'>Diabetes.csv</a><br><br>

1. The data file diabetes.csv contains data of 768 patients. In this data there are 8 attributes
(Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age)
and 1 response variable (Outcome). The response variable, Outcome, has binary value (1 indicating the
outcome is diabetes and 0 means no diabetes). For this assignment purposes we will consider this data
as a population. Use this data to perform the following:</p>
<ol type='a'>
    <li>
        <p>set a seed (to ensure work reproducibility) and take a random sample of 25 observations and
        find the mean Glucose and highest Glucose values of this sample and compare these statistics
        with the population statistics of the same variable. You should use charts for this comparison.</p>
        <img src="charts/glucose_mean_comparison_chart.png" alt="Glucose Mean Comparison">
        <h3>Findings: </h3>
        <p>The population distribution shows approximately normal distribution with a mean of 120.89 and a maximum of 199.00. The sample distribution is more irregular, with a mean of 116.64 and a maximum of 183.00. Comparatively Mean and Highest value of Population is higher than that of Sample.</p>
    </li>
    <li>
        <p>Find the 98th percentile of BMI of your sample and the population and compare the results
        using charts.</p>
    </li>
    <li>
        <p>Using bootstrap (replace= True), create 500 samples (of 150 observation each) from the
        population and find the average mean, standard deviation and percentile for BloodPressure and
        compare this with these statistics from the population for the same variable. Again, you should
        create charts for this comparison. Report on your findings.</p>
       
    </li>
</ol>

<p><strong>Submission:</strong></p>
<p>Create a public GitHub repo and upload the folders for the assignment on the GitHub and submit the link to Canvas.</p>
