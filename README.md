# California-state-hospital-data-Analysis
This is an analysis and comparison of Methicillin-Resistant Staphylococcus aureus Bloodstream Infection rates for 2021 and 2022. Data is the actual data collected from the 
website https://catalog.data.gov/dataset/methicillin-resistant-staphylococcus-aureus-mrsa-bloodstream-infections-bsi-in-california--fdb65.

The data files uploaded here are cdph_mrsa_datadictionary_2021.xlsx, cdph_mrsa_bsi_odp_2021.csv, cdph_mrsa_datadictionary_2022.csv, mrsa_bsi_odp_2022.csv. The file
cdph_mrsa_datadictionary_2021.xlsx and cdph_mrsa_datadictionary_2022.csv contains the explanation of all columns in the actual data set for 2012 that is cdph_mrsa_bsi_odp_2021.csv and 2022 that is mrsa_bsi_odp_2022.csv respectively. 

The jupyter notebook file Python_Data_Analysis_Medica_data.ipynb contains all the corresponding codes for the entire data processing and transformation process and its corresponding visualizations.

These data set files were concatenated to get the data of 2021 and 2022 under one pandas data frame

The entire analysis is done using Python and the libraries used are pandas, numpy, plotly.express, and os. 

Plotly gives us an interactive graphical interface and hence makes visualization way more fun and easy .:)

**Below are the plots from the analysis of data**

![newplot](https://github.com/Debarchan1994/California-state-hospital-data-Analysis/assets/76666637/c77b37af-6558-4bf8-8c5c-b69f0daaa50c)

The above plot shows the number of infections recorded per year for different kinds of hospital types as per the California State Medical department.

![newplot_1](https://github.com/Debarchan1994/California-state-hospital-data-Analysis/assets/76666637/c08335d2-e2ed-4c37-a927-93a331e9dfd3)

The above plot shows the growth in infection rate in 2022 as compared to 2021 in percentage with respect to different types of Hospitals.

![newplot_2](https://github.com/Debarchan1994/California-state-hospital-data-Analysis/assets/76666637/06816705-c079-441e-8187-121ed33c4afc)

The above tree plot shows the County concerning the number of reported infections per year which is 2021 and 2022. The tree plot helps to get a fast understanding of large amounts of data as compared to bar or pie plots as we can understand the contribution of data points with their corresponding box sizes hence in this case we can understand which county's have the highest number of infections and needs special heat from the medical department.

![newplot_3](https://github.com/Debarchan1994/California-state-hospital-data-Analysis/assets/76666637/be363510-14ee-4246-8f96-876d7f51c53e)

The above donut plot shows the top 10 counties with the highest infection prediction error rate that is they have the most significant difference in the actual number of infections and projected/predicted infections. 

![newplot_4](https://github.com/Debarchan1994/California-state-hospital-data-Analysis/assets/76666637/9d70832c-50ae-470a-919a-419bb052a061)

The above bar plot shows the number of times incomplete data was provided from different counties. This indicates that the hospitals from these counties are providing most incomplete information. 


**End of analysis**





