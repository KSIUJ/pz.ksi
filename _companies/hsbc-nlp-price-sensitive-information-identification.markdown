---
layout: project
permalink:
company: HSBC
company_img:
company_desc: HSBC Holdings PLC is a British multinational banking and financial services holding company. It has around 4,000 offices in 70 countries and territories across Africa, Asia, Oceania, Europe, North America and South America and over 200 000 employees. 
project: NLP - Price sensitive information identification
project_img:
technological_stack: |
    - R
    - SAS
    - Python
    - C++
    - Matlab/Octave/Scilab
methodology: Our workflow is most similar to Agile, although we do not follow very strictly.
shipment_method: You will engage in regular communications with the team coordinator.
training: The students will have access to mentoring conducted by a member of HSBC GRA Team.
tools_provided: HSBC will provide the students with their own personal computers during the internship, as well as the necessary software.
mentor: The GRA team consists of several post-doctoral and post-graduate staff that will be available to support the students.
worktime: Flexible. However within HSBC core working hours and business needs.
location: Flexible / to be agreed. 
money: HSBC offers a set internship salary.
later_employment: If the work is of high quality and there is a clear fit with the team, an offer of employment may be made.
team_size: Flexible number of members in a team.
requirements: |
The candidate should be:
- willing to learn new concepts related to financial mathematics and derivative pricing,
- capable of algorithmic programming, experience in scientific computing is a plus,
- competent in one of the following programming languages: C++, R, SAS or Python, Matlab/Octave/Scilab
- be fluent in both spoken and written English.
project_roles: Students will be part of and supported by the HSBC GRA team. Students may take different roles depending on capabilities.
copyrights: HSBC will retain the rights to the project. All of the information the students will have access to will be restricted and confidential and will not be made publically available during or after the project. 
---
With the use of chosen software and publicly available data news articles (or tweeter – for abundance of articles and ease of use), please build an algorithm for classifying texts into groups:

1. Containing stock price sensitive information,
2. Not containing price sensitive information.

### Input

Connect to twitter and select a chosen number of authors to follow

### Processing

Classify sample of tweets manually into groups appearing / not appearing to have some price sensitive information

#### Or

Observe price movements of stocks and tweets appearing referring to those stocks. Single out information appearing prior to “significant” movements of stock prices and build a classifier that looking at tweet contents could predict if it will be connected to a price movement of underlying stock.

### Objectives

Build a model that would predict if a particular tweet contains price sensitive information or not.

Build a dictionary of words that could indicate contents of price-sensitive information.

Price sensitive information is agnostic to the direction of price, most easily reflected in the high trading volumes or high price volatility of tradable instruments associated with the corporate entity.