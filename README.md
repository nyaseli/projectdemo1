# projectdemo1

## Group Members
* Justin Chow
* Elias Mwita
* Liang Gong

## Instructions

Project Proposal

Team members: Justin Chow, Elias Mwita, Liang Gong

Our project is to uncover patterns in successfully patented cases among patent applications to USPTO and the associated inventors and attorneys. 

Data to work with: 
https://www.uspto.gov/learning-and-resources/electronic-data-products/patent-examination-research-dataset-public-pair (For 2019 Release)
https://www.uspto.gov/learning-and-resources/electronic-data-products/patent-claims-research-dataset

Areas to study: 
•	“application_data”: calculate period between filing_date and patent_issue_date to see on average long it takes to issue a patent for different categories. 
        Focus on appl_status_desc and calculate numeric values under “Patented Case”. Study which uspc_class has the most filings and patented rate. 
        Study small_entity_indicator to see if there is any implications on small entrepreneurships. 
•	“all_inventors”: plot the inventors' geolocation distributions. Study which inventors has the most filings and which are the most successful in patent filings. 
•	Merge “application_data” and “all_inventors”: study the inventors distribution, create heatmap based on number of applications each state and patented rate, 
        and potentially use census API to see if there is correlation between state population and patented cases, etc. 
•	“attorney_agent”: study which attorneys has the most filings and which are the most successful in patent filings. 
•	“foreign_priority”: study which country has the most applications to USPTO and their patented rate
•	(Liang) “patent_claims_stats”: study claim numbers on each granted application, focus on word counts, character counts, key words count, etc. 
•	(Liang and all) Merge “application_data” and “patent_claims_stats”: focus on the claims trend for patented cases. Find out common claim features in patented cases. 

Major findings

Make presentation slides

