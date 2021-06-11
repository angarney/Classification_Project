# Classification Project

AmeriCorps, a government organization, provides a vital source of grant funding and volunteers to non-profit organization. AmeriCorps has a variety of grant opportunities. Currently, the AmeriCorps grant application process includes different organization submitting grants application for requests for applications. Each application is reviewed and approved/not approved for funding. The results/application are posted on the AmeriCorps website. Data from the AmeriCorps website were explored in Google Sheets and initial findings show larger organizations are more successful in the grant application process. Large organization tend to submit more grants, get approved at a higher rate, and receive a higher amount per grant on average. Moving forward, Natural Language Processing Topic Modeling should be performed on the grant applications. This can support smaller grant writing teams by 1. improving grant writing expertise through a database of all grant applications to highlight key trends and 2. connecting applicants with similar grants to provide additional support.

## Design
AmeriCorps grants data were explored look at opportunities to increase the benefits for applicants outside of funding. 
* **Opportunity:** Only a small portion of applicants receive funding and explicitly benefit from the process.
* **Impact:** Improve outcomes for smaller grant teams
* **Data Science Solution Path:** Natural Language Processing Topic Modeling
* **Impact Hypothesis:** Providing additional resources and peer support will increase the chances of smaller teams writing successful grants.

## Data

~23,000 data were obtained from Maker Megan. 

**Maker Megan Features:** ua browser version, ua browser, ua form factor, ua os version, ua os, page path, page resource id, page type, page url, location city, location region, location country, referrer host, referrer name, referrer path, referrer source, referrer url, hour, day, week, month, quarter, year, hour day, day name, month name, visitors, sessions, avg duration, bounce rate, item in cart, reached checkout, purchased item, total page views

## Algorithms
**Cleaning:** The raw data sets were merged on grant ID and several calculated columns were added including: City, State, Fiscal Year, Name of Funding Type, Awarded Funding (Yes/No). 

**Aggregating:** The data were aggregated organization and several calculated columns were added including: Total Grants Awarded, Total Grant Applications, % of Application Awarded, One-time Grant Applicant, First Grant Application Year, First Grant Awarded (Yes/No), Most Recent Grant Application Year, Most Recent Grant Awarded (Yes/No), Total Funding Awarded, Average Awarded per Grant, Type of Organization (determined by searching through organization name strings). 


## Tools
* [Google Sheets](https://www.google.com/sheets/about/): Data cleaning/merging and exploratory data analysis
* [Tableau](https://public.tableau.com/en-us/s/): Data visualization and exploratory data analysis
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): Websraping

## Communication
Visuals and a ()) were created. 

![barchat](https://github.com/angarney/Classification_Project/blob/main/Visuals/betas_maker_megan.png)