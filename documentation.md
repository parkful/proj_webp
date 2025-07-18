# Cultural heritage and tourism: impact on local economies

## 1. Introduction

In recent years, Italy's cultural heritage and tourism industry have become central topics of discussion, both nationally and internationally. Italy's rich cultural heritage is globally renowned, attracting millions of visitors each year. From UNESCO World Heritage Sites to local historical landmarks, cultural assets play a significant role in shaping tourism and, by extension, local economies. However, the economic and social impact of this cultural wealth varies significantly across different regions of the country. While some regions, such as Tuscany and Lazio, have successfully leveraged their cultural assets to drive tourism and economic growth, others struggle to fully capitalize on their potential.

The Italian economy, particularly in the post-pandemic era, has faced challenges in revitalizing its tourism sector, which is a key driver of employment and regional development ([ResearchGate](https://www.researchgate.net/publication/352268393_Post-pandemic_tourism_resilience_changes_in_Italians%27_travel_behavior_and_the_possible_responses_of_tourist_cities)). At the same time, disparities in economic performance, employment rates, and income levels persist across regions ([OECD](https://www.oecd.org/en/publications/job-creation-and-local-economic-development-2024-country-notes_ad2806c1-en/italy_9a583862-en.html)), raising questions about the role of cultural heritage in fostering sustainable economic growth.

In this context, three key questions arise:
1. How does the presence of cultural heritage sites impact tourism activity and economic performance in different Italian regions?
2. Are regions with a higher concentration of cultural heritage sites better positioned to achieve economic resilience and growth?
3. What strategies can local governments use to leverage cultural heritage for economic growth?

This project aims to explore these questions by analyzing economic and employment data across different Italian regions. By comparing GDP, tourism revenue, employment indicators and regions with varying levels of cultural assets, the project seeks to uncover patterns and trends that can inform policy decisions and promote sustainable development.

The project aligns data from multiple sources, including:
- Cultural heritage data (e.g., museums, historical sites) from MiBACT and Europeana,
- Tourism data (e.g., tourist arrivals, nights spent) from Eurostat and ISTAT,
- Economic data (e.g., regional GDP, employment rates, income levels) from ISTAT, Eurostat, and the Bank of Italy.

The ultimate goal is to create an explorable map and visualizations that allow users to compare tourism activity, economic performance, and cultural heritage across Italian regions. By doing so, the project aims to highlight the economic potential of cultural heritage and provide actionable insights for policymakers, tourism boards, and local communities.

## 2. Application Scenario

This project aligns data from different sources to explore the relationship between cultural heritage, tourism, and economic development across Italian regions. By analyzing regional GDP, employment levels, tourism revenues, and household income, we aim to determine how cultural heritage contributes to local economies and whether regional disparities exist in its economic impact.

In particular, we investigate:

The correlation between the presence of cultural heritage sites and tourism revenues – Do regions with a higher density of cultural landmarks generate significantly more income from tourism?
The impact of cultural heritage on employment and income levels – Does tourism-driven economic activity lead to higher employment rates and better income distribution in culturally rich regions?
Policy strategies for leveraging cultural heritage – What approaches have been most effective in enhancing the economic benefits of cultural assets?

The findings of this project can be valuable for policymakers, local governments, tourism boards, and cultural institutions seeking to optimize the economic benefits of cultural heritage.
Policymakers can use the insights to design regional economic strategies that enhance the role of cultural heritage in employment and income growth. Local governments can identify underperforming regions where cultural assets remain an untapped economic resource and implement initiatives to strengthen their impact on tourism-driven development. At the same time, tourism boards can refine their promotional strategies by focusing on regions with high cultural value but lower economic returns, ensuring a more balanced distribution of tourism benefits. Finally, cultural institutions can leverage the data to advocate for increased funding, demonstrating their contribution not only to cultural preservation but also to regional prosperity.
By providing data-driven insights, this project aims to support sustainable economic growth and promote more balanced regional development through better utilization of Italy’s cultural heritage.

## 3. Original Datasets and Mashup Dataset

### D1.
[Establishments, bedrooms, and bed-places in tourist accommodation (NUTS 2 region)](https://ec.europa.eu/eurostat/databrowser/view/tour_cap_nuts2__custom_15258263/default/table?lang=en)

Source: Eurostat

Accessed on: Eurostat Data Browser

License: Eurostat open data policy

Description: This dataset provides information on the number of tourist accommodation establishments, bedrooms, and bed places across different NUTS 2 regions in Italy. It is useful for analyzing the availability of infrastructure for tourism across regions and its potential link to economic performance.

### D2.
[Guest nights spent at short-stay accommodations via collaborative economy platforms (NUTS 3 region)](https://ec.europa.eu/eurostat/databrowser/view/tour_ce_oan3__custom_15258506/default/table?lang=en)

Source: Eurostat (Experimental Statistics)

Accessed on: Eurostat Data Browser

License: Eurostat open data policy

Description: This dataset presents the number of guest nights booked through short-term rental platforms (e.g., Airbnb, Booking.com) at the NUTS 3 level. It helps assess the impact of peer-to-peer accommodations on regional tourism activity.

### D3.
[Accommodation establishments: Occupancy in collective tourist accommodation by type of accommodation(monthly data)](http://dati.istat.it/?lang=en#)

Source: ISTAT

Accessed on: ISTAT Data Browser

License: ISTAT open data policy

Description: This dataset provides detailed monthly occupancy statistics for different types of tourist accommodations across Italy, categorized by NACE rev. 2 industry codes. It includes information on the country of residence of guests, enabling an analysis of domestic vs. international tourism trends. The dataset helps assess how different types of accommodations (e.g., hotels, B&Bs, campsites) perform seasonally and regionally, offering a more granular view of tourism dynamics

### D4.
[Arrivals at tourist accommodation establishments by NUTS 2 region](https://ec.europa.eu/eurostat/databrowser/view/tour_occ_arn2/default/table?lang=en&category=tour.tour_inda.tour_occ.tour_occ_a)

Source: Eurostat

Accessed on: Eurostat Data Browser

License: Eurostat open data policy

Description: This dataset tracks the number of tourist arrivals at accommodation establishments across NUTS 2 regions in Italy. It provides an important indicator of tourism flows into different regions and helps assess how cultural heritage sites attract visitors relative to other areas.

### D5.
[Nights spent at tourist accommodation establishments (NUTS 2 region)](https://ec.europa.eu/eurostat/databrowser/product/view/tour_occ_nin2?category=tour.tour_inda.tour_occ.tour_occ_n)

Source: Eurostat

Accessed on: Eurostat Data Browser

License: Eurostat open data policy

Description: This dataset reports the total number of nights spent by tourists in accommodations across NUTS 2 regions, providing insights into tourism demand and visitor behavior in different parts of Italy.

### D6.
[Occupancy in tourist accommodation, by NUTS 2 region](https://ec.europa.eu/eurostat/databrowser/view/tour_occ_anor2/default/table?lang=en&category=tour.tour_inda.tour_occ.tour_occ_or)

Source: Eurostat

Accessed on: Eurostat Data Browser

License: Eurostat open data policy

Description: This dataset provides net occupancy rates of bed places and bedrooms in hotels and similar accommodations (NACE Rev. 2 activity I55.1) at the NUTS 2 regional level. Unlike other datasets that require occupancy rates to be calculated from total nights spent and available bed places, this dataset offers direct occupancy metrics, allowing for more efficient analysis. It can be particularly useful for cross-verifying occupancy rates derived from other datasets and for assessing regional disparities in accommodation usage.

### D7.
[Luoghi della cultura](https://dati.beniculturali.it/lodview/resource/Distribuzione/datasetLuoghiDellaCultura-JSON_LD)

Source: MiC – Direzione generale Organizzazione

Accessed on: MiC Open Data Catalog

License: Creative Commons Attribution 3.0 Unported (CC BY 3.0) License

Description: This dataset contains data from DBUnico 2.0, describing state and non-state owned cultural sites in Italy, categorized by province and regions, managed and updated by MiC (General Directorate for Organization).

### D8.
[Gross Domestic Product Supply Side](https://esploradati.istat.it/databrowser/#/en/dw/categories/IT1,DATAWAREHOUSE,1.0/UP_ACC_TERRIT/IT1,93_498_DF_DCCN_PILT_1,1.0)

Source: ISTAT

Accessed on: ISTAT Data Browser

License: ISTAT open data policy

Description: This dataset provides a breakdown of Italy's GDP by analyzing the value added by different economic sectors, such as agriculture, industry, and services. It enables users to assess each sector's contribution to the overall economy, facilitating a comprehensive understanding of economic performance from the supply side.

### D9.
[Employment by Economic Sector (2010 Classification)](https://esploradati.istat.it/databrowser/#/en/dw/categories/IT1,DATAWAREHOUSE,1.0/UP_ACC_TERRIT/UP_DCCN_OCCTSEC2010/IT1,93_379_DF_DCCN_OCCTSEC2010_2,1.0)

Source: ISTAT

Accessed on: ISTAT Data Browser

License: ISTAT open data policy

Description: This dataset provides employment data categorized by economic sector based on the 2010 classification. It details the distribution of the workforce across agriculture, industry, and services at different territorial levels, helping assess employment trends and the economic structure of Italian regions.

### D10.
[Household Net Income by Source of Income](https://esploradati.istat.it/databrowser/#/en/dw/categories/IT1,HOU,1.0/HOU_INCOME/DCCV_REDNETFAMFONTERED/IT1,32_292_DF_DCCV_REDNETFAMFONTERED_9,1.0)

Source: ISTAT

Accessed on: ISTAT Data Browser

License: ISTAT open data policy

Description: This dataset provides information on household net income, broken down by different sources of income (e.g., wages, pensions, business income) at various territorial levels. It is useful for analyzing regional disparities in income levels and understanding how different economic activities contribute to household earnings.

