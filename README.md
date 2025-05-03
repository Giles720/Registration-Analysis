# INTRODUCTION:
## This dataset records the registration details of beneficiaries from various Nigerian states who enrolled in different training schemes under the AYZ programme implementation. It spans 4 years, capturing the geographic spread, participant numbers, and other program-specific information.

# PROBLEM STATEMENT:
## Despite continuous efforts by the AYZ to implement training schemes across Nigeria, there is limited visibility into the patterns, distribution, and growth of beneficiary registration across different states and over time. Without a structured analysis of registration data, it is challenging to assess the effectiveness, zonal reach, and demographic inclusiveness of these programs. This dataset aims to address key questions such as:

- Which states consistently have higher or lower beneficiary registration numbers?
- How has registration for AYZ training schemes evolved over the years?
- What has the gender distribution of participation been over the years?
- Are there disparities in participation among different zones that need strategic intervention?
- Which schemes are the 4 topmost in demand?
- Which scheme attracts the highest registration, and how does this vary across zones?

# STRUCTURE OF THE DATASET:
- SCHEME: Training scheme name (e.g., A-NOAS, B-NOAS)
- PROGRAMME: Categorization of programme (VSD, REP, SSE and SPW)
- YEAR: Year of registration (e.g., 2020)
- SEX: Gender (M/F)
- STATES: State of registration 
- ZONE: Geopolitical zone 
- TOTAL REGISTERED: Number of people registered
- 2442 Rows and 7 columns excluding the index column
  
# OBJECTIVE:
## To analyse registration data of AYZ beneficiaries across various states and training schemes under the NDE programme over multiple years 
# SKILLS DEMONSTRATED 
1. Open the file in Excel.
2. Examination of the dataset
3. Use "Find & Replace" to correct typos:
      - Replace "Pleteau" with "Plateau"
      - Replace "North Cental" with "North Central"
4. Reshaping and Transformation of the dataset.[Details Here](https://github.com/Giles720/Registration-Analysis/commit/35397b0cc86bf36fb49c8f54bc7a84ca0748effa)
5. Used Power Query to load the dataset

# FINDING /ANALYSIS
1. ### Total number of registered beneficiaries: 		102,191
   
2. ### Percentage Registration Growth:				84.70%  
    This indicates a strong positive trend in registration, reflecting increased awareness or access to AZY programmes. The growth suggests successful outreach or improvements        in service delivery.
   
4. ### Male-to-Female Ratio:                    1.5   
    This implies that for every 1 female registrant, there are 1.5 male registrants. The gender imbalance suggests a need to develop targeted strategies to increase female 
    participation, ensuring inclusiveness and equity in program access.
   
5. ### State with the highest or lowest beneficiary registration numbers
   Abuja-FCT recorded the highest total registrations across all years, with 2,966, while Jigawa had the lowest with 2,638.[See Details Here]
     
6. ### Peak Registration Year
    The year 2024 has the highest registration of beneficiaries, reflecting increased outreach efforts.
   
7. ### Gender Participation
      Males constituted approximately 60% of total registrations, while Females were 40%, indicating a gender gap in participation.
  	
8. ### Disparities in participation among different zones
      The South East recorded the lowest participation rate at 13.63%, while the North Central and North West regions had the highest with 19.03% and 18.82% respectively. This          variation highlights a regional imbalance in engagement that may affect the overall inclusiveness of the program.
  	
9. ### The 4 topmost schemes in demand 
      The 4 topmost schemes in demand are;
            - B-NOAS:  	30,960
            - A-NOAS:   15,487
            - Quick-fix: 5,850
            - SPMESS:    5,074
10. ### Scheme attraction across zones
    Across all zones, B-NOAS (Basic National Open Apprenticeship Scheme) consistently had the highest registration figures, showing its widespread reach and appeal. A-NOAS 
    and Quick Fix schemes also rank consistently in the top three, suggesting these programs are the most popular or most implemented nationwide.

# LIMITATIONS
- While registration counts are available by scheme and zone, demographic details such as age or education level per scheme are not included, limiting deeper insights into 
   participant profiles.
- The dataset is for demonstration purposes and should be referenced for research purposes  

# RECOMMENDATIONS
- Target Underrepresented States to balance national coverage.
- Focus on Female Inclusion by introducing targeted programs for women.
- Expand Successful Schemes like A-NOAS to other regions.
- Implement a KPI dashboard for continuous tracking of yearly trends.

# CONCLUSION 
## The analysis provided valuable insights into zonal participation patterns, gender distribution, and scheme-specific engagement across different zones. While the data shows positive registration growth and highlights leading schemes in each zone, disparities persist, especially in gender balance and zonal participation. These findings underscore the need for targeted strategies to ensure more equitable and inclusive program implementation nationwide.
