# sustainability_assessment_of_EU_companies
Here are the guidelines and the python script to convert a simple EUSurvey questionnaire to a Pandas dataframe, and to perform statistical analysis using the Seaborn library.

The scope of the questionnaire was to assess the sustainability of the European Union (EU) companies, with a focus on their environmental, social and economic sustainability. In total, 9 enquiry questions were created using chatgpt3 each containing 3 possible answers indicating the level of sustainability from low to high. 

The questionnaire was hosted using the EUSurvey management tool. The EUSurvey is an online survey management system for creating and publishing forms available to the public. The EUSurvey is hosted at the European Commission's Department for digital services (DG DIGIT), and is available free of charge to all EU citizens. EUSurvey can be accessed from: (https://ec.europa.eu/eusurvey). 

The EUSurvey platform records the questionnaire results in a incremental manner, and the results are easily exportable in .pdf and .xls formats. 
A sample file of the questionnaire can be viewed here: /pdf/sustainability_assessment_of_EU_companies.pdf. 
For the purpose of this study, a random sample of 300 companies was created. 
The sample file can be viewed here: /xls/sustainability_assessment_of_EU_companies.xls. 

For the purpose of this study, a Jupyter notebook script was created that imports the questionnaire sample file and turns it into a Pandas dataframe. Successively, the script cleans and prepares the dataframe for further analysis with the python Seaborn library and includes statistical comparisons using the Mann-Whitney-Wilcoxon test. 
The script can be viewed here: /sustainability_assessment_of_EU_companies.ipynb

The method shown here can be reproduced on any EUSurvey questionnaire. However, additional complexity in the structure of the questionnaire would require modifications to the python script. 
