# sustainability_assessment_of_EU_companies
This repository contains the steps to create a simple questionnaire to assess the environmental, social, and economic sustainability of the European Union (EU) companies and perform statistical analysis using the Seaborn library.

The questionnaire was hosted using the EU Survey management tool (https://ec.europa.eu/eusurvey). The EU Survey platform records the questionnaire results in an incremental manner, and the results are easily exportable in .pdf and .xls formats.

A sample of the questionnaire is shown in sustainability_assessment_of_EU_companies.pdf. For the purpose of this study, a sample of 300 random answers was created. The dataset is shown in sustainability_assessment_of_EU_companies.xls.

A Python script was created that imports the questionnaire dataset, converts it into a Pandas data frame, and cleans and prepares the data frame for further analysis with the Seaborn library which includes statistical comparisons using the Mann-Whitney-Wilcoxon test. 

