# APMA-project

Thank you for showing interest in our presentation! This will describe how to use the various files in this github.

1. Gender Bias Model.Rmd has the code for the null, homophily-free, bias-free, and full models. You can tweak parameters and run the code through to get visualizations of hypothetical hierarchies.
2. Bifurcation Visualization.Rmd has the code for the bias-free model, and I used this to explore the bifurcation behavior.
3. cleaning_data.Rmd has the code for cleaning the IPEDS data from 1993-2020 for academic faculty by gender. The raw data is available to download at https://nces.ed.gov/ipeds/datacenter/DataFiles.aspx?year=2020&surveyNumber=5 , and I would provide a name for the specific file on this page but the name varies over time. In 2020, the file is called S2020_IS for reference.
4. fit our data.Rmd has the code for the model fitting with the data cleaned in step 3. It includes the parameters we used and the fitting algorithm, from the package FME. 
