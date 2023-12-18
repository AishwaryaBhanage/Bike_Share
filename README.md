# Bike_Share

Case Study 1: How Does a Bike-Share Navigate Speedy Success?

Introduction: 
In this case study, we delve into the intricacies of Cyclistic's bike-share program, aiming to understand and address the critical challenge of converting casual riders into annual members. The scenario unfolds in the vibrant urban setting of Chicago, where Cyclistic seeks sustainable growth by maximizing annual memberships. This real-world obstacle prompts an exploration into user behavior, motivations, and the impact of digital media on marketing tactics. Assumptions include the profitability of annual memberships and the potential to influence casual riders through targeted strategies.

Ask
Three questions will guide the future marketing program:
1. How do annual members and casual riders use Cyclistic bikes differently? 
2. Why would casual riders buy Cyclistic annual memberships? 
3. How can Cyclistic use digital media to influence casual riders to become members?

Case Study – Ask phase
•	What is the problem you are trying to solve?
->	The current marketing approach lacks effectiveness in converting casual riders into annual members, necessitating the development of a more targeted and compelling marketing strategy to enhance membership conversion rates.

•	How can your insights drive business decisions?
->	By finding the trend in the data to get the difference between the casual riders and annual members, it will help to maximize the annual members which will lead to make more profit in future and help business grow.

Key Tasks:
1.	Identify the business task
->	To find the different factors and how exactly the casual riders differ from annual members and to convert these casual riders into annual members.

2.	Consider key stakeholders
->	Cyclistics executives must approve the recommendations made based on the data.
  	
Deliverable
•	Develop a targeted marketing strategy to convert casual riders into annual members by gaining insights into the differences between these two customer segments, understanding the motivations behind casual riders purchasing memberships, and evaluating the influence of digital media on marketing tactics.

Problem: 
The major problem lies in the disparity between the profitability of annual members and casual riders. Analysis reveals that while the pricing model attracts diverse customers, there is an untapped opportunity to convert casual riders into members. Financial data supports the assertion that annual members contribute significantly to Cyclistic's success, forming the basis for the marketing team's strategic focus.

Prepare

Case Study – Prepare phase
1.	Where is your data located?
->	The data is located in an S3 bucket in Amazon AWS.
2.	How is the data organized?
->	The data is organized in a structured i.e table format of rows and columns with attribute names given to each column. 
->	We have given Trip information, station, and geographical information. That is Bike ID, Start and end time with dates, start and end station along with its latitude and longitude values and the kind of member they are to cyclistic.
3.	Are there issues with bias or credibility in this data? Does your data ROCCC?
->	Upon checking the data looks appropriate to solve the problem, but the data has more number of members than causal riders which makes it imbalanced data.
4.	How are you addressing licensing, privacy, security, and accessibility?
->	Bikeshare grants to us a non-exclusive, royalty-free, limited, perpetual license to access, reproduce, analyze, copy, modify, distribute in our product or service and use the Data for any lawful purpose. 
->	Prioritizing the anonymization of personal information in the data to protect user privacy.
->	Restricting access to bike share data based on role and responsibilities, ensuring that only authorized personnel can handle sensitive information.
->	Making it accessible only in a user-friendly format.
5.	How did you verify the data’s integrity?
->	By applying data validation rules to check for accuracy and completeness. This can involve checking ranges, formats, and relationships between different data fields.
->	Change the format of dates, ride Id, and other fields.
->	Implementing checks for duplicate entries within the dataset to maintain data consistency.
->	Engaging multiple stakeholders/executives in the data review process.
6.	How does it help you answer your question?
->	It helped in understanding the data and making it reliable for further analysis. It also helped in increasing knowledge by referring to other documents.
7.	Are there any problems with the data? 
-> There are some fields which have blanks or empty spaces for station information.

Key Tasks:
1.	Download data and store it appropriately.
-	Downloaded and stored data in a folder and also copied it to have it in its original form later.
2.	Identify how it’s organized.
-	Organized in a structured format resembling a table of rows and columns.
3.	Sort and lter the data.
-	Performed various filters and sorts to check the data’s credibility
-	
Deliverable
•	A data source used is an amazon aws s3 bucket which is a reliable source along with license. It’s a zip file having recent data and modified details.

Process

Case Study – Process phase
1.	What tools are you choosing and why?
->	The tools used are Google Sheets and SQL Workplace. It is easy to get familiar with the data to understand it in a proper way and make modifications to ensure its consistency. 
2.	What steps have you taken to ensure that your data is clean?
->	Check for duplicate data and format of data along with attribute naming conventions.
->	We conducted a thorough data profiling analysis to understand the data’s structure, patterns, and quality.
->	Use statistical methods to detect and handle outliers that might distort the analysis
3.	How can you verify that your data is clean and ready to analyze?
->	By cross verifying if there are any errors or duplicate values present or not. 
->	By Computing basic descriptive statistics such as mean, median, standard deviation, and quartiles to identify outliers or unusual values.
->	Visualize the data using charts, histograms, and scatter plots to identify any anomalies or unexpected patterns.
->	Engage in peer review by having another team member or a domain expert review the dataset and cleaning procedures.
4.	Have you documented your cleaning process so you can review and share those results?
->	Yes, the cleaning process has been documented along with steps taken during the process.

Key Tasks:
1.	Check the data for errors.
2.	Choose your  tools.
3.	Transform the data so you can work with it effectively.
4.	Document the cleaning process.
   
Deliverable
•	Documentation of any cleaning or manipulation of data created.

Analyze

Case Study – Analyze phase
1.	How should you organize your data to perform analysis on it?
2.	Has your data been properly formated?
3.	What surprises did you discover in the data?
4.	What trends or relationships did you find in the data?
5.  X	How will these insights help answer your business questions?

Key Tasks:
1.	Aggregate your data so it’s useful and accessible.
2.	Organize and format your data.
3.	Perform calculations.
4.	Identify trends and relationships.
   
Deliverable
•	A summary of your analysis
	During the analysis of the bike share trip data, distinct patterns emerged between casual and annual members. Casual riders predominantly favor the second half of the month, with weekends, particularly Saturdays, exhibiting the highest ride frequency. Conversely, annual members show a higher overall ride count, preferring Fridays and Saturdays. Notably, casual riders tend to engage in longer rides compared to their annual counterparts.

Share

Case Study – Share phase
•	Were you able to answer the question of how annual members and casual riders use Cyclistic bikes differently?
•	What story does your data tell?
•	How do your findings relate to your original question?
•	Who is the audience? What is the best way to communicate with them?
•	Can data visualization help you share your findings?
•	Is your presentation accessible to your audience?
Key Tasks:
1.	Determine the best way to share findings.
2.	Create effective data visualizations.
3.	Present findings.
4.	Ensure work is accessible.
Deliverable
•	Supporting visualizations and key findings
	Created in a document.

Act

Case Study – Act phase
•	What is your final conclusion based on your analysis?
	Through thorough problem analysis, we've uncovered the pivotal role annual memberships play in Cyclistic's success. Historical data serves as a rich resource, guiding the formulation of effective marketing strategies. The importance of understanding user behavior and motivations is a key takeaway, emphasizing the significance of data-driven decision-making in urban transportation.

Deliverable
Your top three recommendations based on your analysis
1. Targeted Promotions on Weekends:
Capitalize on the observed trend of casual riders favoring weekends, especially Saturdays. Implement targeted promotional campaigns during these peak days, offering incentives such as discounted annual memberships or bonus ride credits to encourage conversion.
2. Exclusive Friday and Saturday Offers:
Recognize the preference of annual members for Fridays and Saturdays. Design exclusive offers or benefits for casual riders who transition to annual memberships, emphasizing the advantages of riding on these days, such as priority access, special events, or extended ride times.
3. Tailored Benefits for Long Rides:
Leverage the insight that casual riders engage in longer rides. Develop membership packages that provide additional benefits for extended rides, such as discounted rates for ride durations exceeding a certain threshold. Highlight the cost-effectiveness and convenience of annual memberships for those who frequently enjoy extended rides.

Next Steps:
Choosing the best solution involves leveraging insights from historical data to craft targeted marketing tactics. Recommendations include refining pricing plans and employing digital media strategies to influence casual riders positively. The selected solution not only aligns with the company's growth strategy but also positions Cyclistic for sustained success in the competitive urban transportation landscape.


 
