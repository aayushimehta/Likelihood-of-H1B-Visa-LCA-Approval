# Likelihood-of-H1B-Visa-LCA-Approval

Introduction - Learning the Domain:
The US H-1B visa is a non-immigrant visa that allows US companies to temporarily employ foreign workers in specialty occupations. A specialty occupation requires a specialized knowledge and a bachelor's degree or equivalent work experience in areas such as information technology (IT), finance, accounting, architecture, engineering, mathematics, science, medicine, etc. A LCA (Labor Condition Application) is a mandatory document that the H1B Sponsor / employer needs to file with US Department of Labor before they file the H1B petition with USCIS for any non-immigrant worker.

Framing the Problem:
For a foreign national to apply for H1-B visa, a US employer must offer them a job and submit a petition for H-1B visa to the US immigration department. This is also the most common visa status applied for and held by international students once they complete college or higher education and begin working in a full-time position. A LCA (Labor Condition Application) is a mandatory document that the H1B Sponsor/employer needs to file with US Department of Labor before they file the H1B petition with USCIS for any non-immigrant worker. This form has all the key information regarding the offered job, wage details, location, etc. that is offered to the foreign worker. This application needs to be certified in order to get the H1B visa approved.
It is very important for an employer and employee to know if the LCA application will be approved/ certified for visa. Through this project, a definite answer to this question will be predicted.

Python files:

1 Initial Study of Data.ipynb: first python file for choosing columns from original data

2 Data Wrangling.ipynb: python file to analyze and wrangle the data in the selected columns from the first file

3 Building Models.ipynb: python file containing the final model and prediction analysis


Excel files:

Class Membership.csv: Final outcome of the project with predicted y values and predicted probablities.

soc_to_stem.csv: used to carry out SOC to Stem conversions

Data Source:
The source of data is the United States Department of Labour government website. In carrying out its responsibility for the processing of prevailing wage, labor certification, and labor attestation applications, the Office of Foreign Labor Certification (OFLC) generates an extensive amount of program data. But this data is very messy with 260 columns. I have collected the data file for applications attended in the reporting period of one year (from October 1, 2018, through September 30, 2019) which contains more than 36M data entries with over 260 features.

Data Source: https://www.foreignlaborcert.doleta.gov/pdf/PerformanceData/2019/H-1B_Disclosure_Data_FY2019.xlsx (270MB) 

Column metadata: https://www.foreignlaborcert.doleta.gov/pdf/PerformanceData/2020/H-1B_H-1B1_E-3_Record_Layout.pdf

LCA form: https://www.foreignlaborcert.doleta.gov/pdf/eta_form_9035.pdf
