<h1>💰 Donor & Fundraising Analysis Using SQL</h1>

<h2>Project Overview</h2>

This project analyzes donor and donation data for Education for ALL, a hypothetical nonprofit organization seeking to strengthen its fundraising strategy.

The analysis uses two relational datasets containing donor demographics, donation activity, donation frequency, educational background, geographic location, and other donor characteristics.

Using SQLite and SQL, I combined and analyzed the datasets to identify patterns in donor behavior, recurring contributions, donation value, and geographic performance. Tableau was also used to visualize selected findings.

The goal was to transform donor data into actionable insights that could help the organization increase its donor base, improve donation frequency, and increase the value of future contributions.

<h2>Project Objective</h2>

The analysis sought to answer:

- How many donors are currently represented in the database?
- What is the total value of donations?
- How frequently are donors contributing?
- Who are the organization's highest-value donors?
- How does donation behavior vary by gender?
- Are donation patterns associated with job field or university education?
- Which geographic areas demonstrate stronger donation activity?
- Which donor segments represent potential fundraising opportunities?

<h2>Tools & Skills</h2>

<h3>Tools</h3>

- SQLite — relational database management and SQL querying
- SQL — donor segmentation, aggregation, filtering, and relational analysis
- Tableau — data visualization and geographic donor analysis
- GitHub — portfolio documentation and project presentation

<h3>SQL Skills Demonstrated</h3>

- SELECT statements
- JOIN operations
- WHERE filtering
- BETWEEN conditions
- AND / OR logical operators
- SUM() aggregation
- COUNT() aggregation
- AVG() aggregation
- GROUP BY
- HAVING
- ORDER BY
- Relational data analysis
- Donor segmentation
- Business-focused querying

<h2>📁 DATASETS</h2>

The analysis used two relational datasets containing donor and donation information.

- [Donation Data](Data/2.4-EFO_Donation_Data.sql)
- [Donor Data](Data/2.6-EFO_Donor_Data.sql)

<h3>Donation Data</h3>

The donation dataset contains information including:

- Donor ID
- First name
- Last name
- Email
- Gender
- Job field
- Donation amount
- State
- Shirt size

<h3>Donor Data</h3>

The donor dataset contains additional donor characteristics including:

- Donor ID
- Donation frequency
- University
- Car
- Second language
- Favorite color
- Movie genre

Both datasets were imported into SQLite and connected using the donor ID field to support relational analysis.

<h2>🔗 RELATIONAL ANALYSIS: Donor & Donation Data</h2>

<h3>Analysis Approach</h3>

The two datasets contained complementary information about donor characteristics and donation behavior.

SQL JOIN operations were used to connect donor demographic information with donation activity, allowing individual donations to be analyzed alongside attributes such as gender, location, university affiliation, job field, and donation frequency.

<h3>Analytical Value</h3>

- Combined information stored across multiple relational tables
- Connected donor characteristics with donation behavior
- Enabled multidimensional donor segmentation
- Supported fundraising analysis beyond basic donation totals
- Created a foundation for targeted donor strategies

<h2>💵 FUNDRAISING ANALYSIS: Donation Performance</h2>

<h3>Research Question</h3>

What does the existing donor database reveal about overall fundraising performance?

<h3>Analysis</h3>

SQL aggregation functions were used to measure the size and monetary value of the donor database.

The analysis identified:

- 1,000 donors in the database
- $249,085 in total donations

COUNT() and SUM() queries established baseline fundraising metrics that could then be combined with more detailed donor segmentation.

<h3>Analytical Value</h3>

- Established baseline fundraising KPIs
- Quantified the organization's existing donor population
- Measured total donation value
- Provided context for deeper donor analysis

<h2>🏆 DONOR SEGMENTATION: High-Value Donors</h2>

<h3>Research Question</h3>

Which donor characteristics are associated with larger and recurring donations?

<h3>Analysis</h3>

SQL filtering, JOIN operations, sorting, and conditional logic were used to investigate donors contributing higher donation amounts.

Queries examined donation amounts between $400 and $500, recurring donation frequency, gender, state, job field, and university affiliation.

The analysis identified 20 women contributing more than $400 on a monthly basis compared with 18 men meeting the same criteria.

<h3>Analytical Value</h3>

- Identified high-value recurring donor segments
- Compared donation behavior across demographic groups
- Connected donation value with contribution frequency
- Supported development of more targeted fundraising strategies

<h2>🌎 GEOGRAPHIC ANALYSIS: Donation Activity by State</h2>

<h3>Research Question</h3>

Which geographic areas demonstrate stronger donor activity?

<h3>Analysis</h3>

Donation activity was compared across U.S. states to identify geographic patterns within the donor database.

The original analysis identified California, New York, and Florida as notable areas of donation activity, with Florida demonstrating particularly strong monthly donation behavior.

Tableau was used to visualize geographic and donor patterns identified through the analysis.

<h3>Analytical Value</h3>

- Identified geographic concentrations of donor activity
- Compared recurring donation behavior across states
- Supported geographic donor segmentation
- Provided potential direction for targeted fundraising campaigns

<h2>🎓 DONOR PROFILE ANALYSIS: Education & Giving Behavior</h2>

<h3>Research Question</h3>

Does university affiliation appear to correspond with recurring donation behavior?

<h3>Analysis</h3>

The project compared donation patterns among donors with and without university affiliations.

The original analysis found that donors associated with universities demonstrated higher recurring donation frequency than donors without collegiate affiliation.

This finding suggested that education-related donor segmentation could provide an additional dimension for future fundraising outreach.

<h2>📄 ORIGINAL PROJECT REPORT</h2>

The original Data Analyst II portfolio report documents the business problem, relational datasets, SQL methods, donor analysis, Tableau visualization, findings, and fundraising recommendations developed during the EntryLevel apprenticeship.

[View the Original Data Analyst II Portfolio](https://github.com/TheData-Cleaner/EntryLevel_Data_Analyst_II/blob/main/Entry%20Level%20Data%20Analyst%20II%20-%20Portfolio.pdf)

<h2>🔎 KEY FINDINGS</h2>

- The donor database contained 1,000 donors.
- Total donations represented $249,085 within the analyzed dataset.
- Women slightly outnumbered men among monthly donors contributing more than $400, with 20 women compared with 18 men.
- Geographic differences appeared in recurring donation behavior.
- California, New York, Florida, and other states emerged as notable donor markets within the original analysis.
- Florida demonstrated particularly strong monthly donation activity.
- University-affiliated donors demonstrated higher recurring donation frequency in the original analysis.
- Combining donor demographics with transaction data revealed patterns that would not have been visible from either dataset independently.

<h2>💡 FUNDRAISING RECOMMENDATION</h2>

The original analysis recommended using donor segmentation to support more targeted fundraising efforts, particularly among recurring donors, university-affiliated donors, and donors located in stronger geographic markets.

Rather than treating all donors as a single population, the analysis demonstrated how demographic, behavioral, and geographic information could be combined to identify donor segments with greater potential for recurring contributions.

Future analysis could expand this work through donor lifetime value, retention analysis, donation cohorts, campaign response rates, and predictive donor segmentation.

<h2>Project Outcomes</h2>

- Imported and analyzed relational donor datasets using SQLite
- Used SQL JOIN operations to connect donor and donation information
- Applied aggregation functions to calculate donor and fundraising KPIs
- Used conditional filtering to identify high-value recurring donors
- Analyzed donor behavior across gender, education, job field, and geography
- Used Tableau to visualize selected donor patterns
- Translated SQL query results into fundraising insights
- Developed data-informed recommendations for donor targeting and fundraising growth
