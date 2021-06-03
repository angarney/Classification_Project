# Classification Project Proposal

**Question/Need: What is the framing question of your analysis, or the purpose of the model/system you plan to build? Who benefits from exploring this question or building this model/system?**  

[Maker Megan](https://makermegan.com/) is an e-commerce platform that sells small batch clay earrings. Maker Megan was launched during May 2020 in the COVID-19 pandemic. 

Framing Question:
* Problem: As vaccinations increase and stores reopen, Maker Megan needs to maintain/increase sales in the e-commerce platform. 
* Initial Impact Hypothesis: Customer segmentation will enable Maker Megan to maintain/increase sales as in-person stores become more competitive. 
* Measures of success, both technical and non-technical: 

**Data Description: What dataset(s) do you plan to use, and how will you obtain the data? What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with? If modeling, what will you predict as your target?**

The data for this project will be obtained through Maker Megan's Shopify portal. The individual unit will be one website visit. The dataset includes ~23,000 website visits. 

Features: ua_browser_version, ua_browser, ua_form_factor, ua_os_version, ua_os, page_path, page_resource_id, page_type, page_url, location_city, location_region, location_country, referrer_host, referrer_name, referrer_path, referrer_source, referrer_url, hour, day, week, month, quarter, year, hour_day, day_name, month_name, visitors, sessions, avg_duration, bounce_rate, item_in_cart, reached_checkout, purchased_item, total_pageviews

Target: order_placed

**Tools: How do you intend to meet the tools requirement of the project? Are you planning in advance to need or use additional tools beyond those required?**  
I will be using sklearn and xgboost to create my classification model. Additionally, I hope to use within python visualization to support my final recommendations for Maker Megan. 


**MVP Goal: What would a minimum viable product (MVP) look like for this project?**  
The MVP will be a initial classification mode with 2-3 of the variables. 

