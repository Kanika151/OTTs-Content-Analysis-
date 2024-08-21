# OTTs-Content-Analysis-

OTT Content Analysis 

### Dashboard Link : 
![Dashboard_upload] (https://github.com/Kanika151/OTTs-Content-Analysis-/blob/main/Untitled.png)

## Problem Statement: 

**OTT Content Analysis Across Netflix, Amazon Prime Video, and Hotstar**

The data analysis solution provides insights into the content available on major OTT platforms, including Netflix, Amazon Prime, and Hotstar. The analysis will focus on content ratings, genres, and the distinction between movies and TV shows. Additionally, it will examine release trends by year and country to identify patterns and trends in content distribution across these platforms.

**Key Components & Features:**

1. **Content Rating Analysis:**
   - Analyze the distribution of content ratings (e.g., G, PG, PG-13, R, etc.) across Netflix, Amazon Prime, and Hotstar.
   - Compare the content rating distributions between platforms to understand their target audience demographics.
   - Identify trends in content ratings over time and by country, and assess how these trends align with platform-specific strategies.

2. **Genre Analysis:**
   - Explore the genre distribution across each OTT platform, comparing the popularity of different genres (e.g., Drama, Comedy, Action, Thriller).
   - Identify which genres are more prominent on each platform and how this reflects the platform’s content strategy.
   - Analyze the evolution of genre popularity over time and across different regions or countries.

3. **Movies vs. TV Shows:**
   - Categorize content into movies and TV shows, and analyze the balance between these two categories on each platform.
   - Visualize the proportion of movies versus TV shows available on each platform.
   - Identify trends in the production and release of movies versus TV shows over time and by country.

4. **Releases by Year:**
   - Analyze the number of content releases (both movies and TV shows) by year across Netflix, Amazon Prime, and Hotstar.
   - Visualize trends in content production and releases over the years to understand how these platforms have grown or shifted focus.
   - Identify peak years for content releases and correlate them with platform expansions or major industry events.

5. **Country-Specific Analysis:**
   - Examine the geographical distribution of content on each platform, identifying the most prolific countries of origin.
   - Analyze how the country of origin influences content ratings, genres, and the type of content (movies vs. TV shows).
   - Compare the availability of local versus international content on each platform.

6. **Platform Comparison:**
   - Conduct a comparative analysis of the content strategies of Netflix, Amazon Prime, and Hotstar based on ratings, genres, and release patterns.
   - Identify unique strengths and niches of each platform in terms of content offerings.
   - Explore how each platform tailors its content library to different regions and demographics.

**Stakeholders:**
- **Content Creators and Producers:** To understand the competitive landscape and identify gaps or opportunities in content production.
- **OTT Platform Strategists:** To refine content acquisition and production strategies based on competitor analysis and audience preferences.
- **Marketers:** To design targeted marketing campaigns that align with content trends and audience preferences on each platform.
- **Data Analysts and Researchers:** To explore content trends, audience behavior, and regional preferences across OTT platforms.

**Outcome:**
The data analysis will deliver a comprehensive overview of the content landscape across Netflix, Amazon Prime, and Hotstar. By understanding content ratings, genres, release trends, and country-specific patterns, stakeholders will be able to make data-driven decisions that enhance content strategies, improve audience targeting, and optimize platform offerings. The analysis will also provide valuable insights into how these platforms have evolved and differentiated themselves in the competitive OTT market.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns had missing values. 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 8 : Visual Cards were added for KPIs like Total Shows, No of Ratings, Total Genre, From & to year. 
- Step 9 : Five card visuals were added to the canvas, one representing average departure delay in minutes & other representing average arrival delay in minutes.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
Although, by default, while calculating average, blank values are ignored.

- Step 10 : A bar charts was also added to the report design area representing the change in Shows% Genre wise, No of released every year. 


- Step 11 : Pie Chart is also added to show distinctoon between movies & shows. 


