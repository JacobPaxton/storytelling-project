# Telco Data Project Brainstorming
Google Doc for this .md here: https://docs.google.com/document/d/1b1zaLlNPEh5IQeInW68lQ5YBAkZeichciSArmZnGkJA/edit

## Telco spreadsheet located here: 
https://docs.google.com/spreadsheets/d/1KarDF5wzubtUQiH4Ng9I6QHhC2mZDqDEtO5_dQFwfqw/edit?usp=sharing

## Initial thoughts and questions during spreadsheet exercises
- What data is included? A: Customer plans, rates, churn, and demographics
- What are the summary statistics for rates compared to plans?
- What are the summary statistics for rates compared to demographics?
- What correlations are there between churn and the rest of the data?

## Find a driver of churn
- Built multiple pivot tables of count % between churn and different plans/demographics
### Churn drivers
- Following information is captured in screenshot, filtered to month-to-month customers only. Percentages here: percentage of all options churned/not-churned, churned is % higher than not-churned (please see screenshot if confused)
- Phone service: 'No lines' -2%, 'One line' -12%, 'Two lines' -1%
- Internet service: 'none' with -8%, 'DSL' -11%, 'Fiber Optic' with +5%
- Senior Citizen: True -16%, False +2%
- Gender: Female -6%, Male with -8%
- Payment Type: Bank transfer (auto) -5%, Credit Card (auto) -5%, Electronic check +3.5%, Mailed check with -8%

## Create the story
### Prepare to Create
- Took a break, put on some music
- Put entire requirements sheet into a .md file, segregated portions with md syntax while reading it
- Made pivot tables for multiple combinations of metrics v churn
- Chose Fiber Optic v Other when it comes to churn
- Use Man In Hole framework due to lack of trend data (what is/could be) and lack of historical context (foundation-climax-resolution)
- Audience: exec team
- - Level of language: summary, little jargon
- - Types of charts: summary, simple
- - Amount of teaching required: little
- Setting and deliverables: noted in requirements
- What I learned from brainstorming: use the Fiber Optic metric as it is most distinct, goal should be to give metrics of with-fiber versus without-fiber churn
- Visualizations that align with my goals: bar chart comparing churn of different internet plans, churn percentage of keep-offering-fiber versus potential churn percentage of no-longer-offer-fiber
### Talk and Listen
- Control for month-to-month contract
- Consider "market share" of each option (ex: % of churned no-phone customers versus all churned/not-churned no/1/2-line customers)
- Visualizations in JupyterNB versus Google Sheets
- - Google Sheets is fast and easily-shared
### Sketch
- Screenshots included in Google Doc
- Put churn v not-churned in chart for different internet types and revenue
### Prototype
#### Slides
- Title slide: Title, name, date
- Agenda slide: "Today I will speak to you about churn factors"
- Executive Summary slide: "Fiber Optic customers have a high churn rate, Cutting the Fiber option for future customers may decrease overall churn rate"
- Overview about data sample: Fiber is % of all customers and % of all revenue
- Visualization of issue: Fiber churn rate v other internet
- Recommendation: Stop offering fiber in new plans to decrease churn
- Visualization of post-changes: Overall churn without Fiber option
- Conclusion and next steps: "Thank you"
- Appendix: data dictionary, sample explanations, summary data