# 📊 GHANA HIV PREVALENCE ANALYSIS (2004–2014)
Comprehensive Regional, Gender, Age, Site, and Mortality Insights
This project presents an in-depth analysis of HIV trends in Ghana using five major datasets covering prevalence, gender distribution, regional distribution, age patterns, site-level data, and AIDS-related deaths.
All analyses were visualized through multi-dashboard Power BI reports.
<p></p>
<img width="3508" height="2480" alt="1" src="https://github.com/user-attachments/assets/776c8fd4-20e7-4040-a686-c79a45531747" />

## INTRODUCTION
HIV remains one of the most significant public health challenges in Ghana, affecting individuals, families, and entire communities across the country. Understanding the prevalence and distribution of HIV is essential for guiding national health policies, allocating resources, and implementing targeted interventions.
<p></p>
By analyzing trends across regions, age groups, and years, stakeholders can identify high-risk areas, monitor progress toward national health goals, and strengthen prevention and treatment strategies. This analysis provides valuable insights into how HIV cases are evolving over time, helping health authorities, researchers, and policymakers make informed decisions that support a healthier and more resilient nation.

## PROBLEM STATEMENT
HIV continues to pose a significant public health challenge in Ghana, affecting individuals, families, and communities across all regions. Despite ongoing interventions, variations in prevalence still exist between regions, age groups, and genders, making it necessary to conduct detailed and data-driven assessments. Understanding these patterns is essential for guiding national strategies, improving resource allocation, and strengthening prevention and treatment programs.
However, existing HIV-related data in Ghana is often scattered across multiple reports and datasets. 
<p></p>
This makes it difficult to gain a complete and unified view of national trends. To address this gap, this study brings together five key datasets to analyze HIV prevalence, demographic patterns, regional distribution, and AIDS-related deaths. By combining these datasets, the analysis provides clearer insights that can support more informed decision-making and targeted interventions.

## DATA USED
This analysis is based on five key datasets that collectively provide a comprehensive understanding of HIV patterns, trends, and demographic impacts in Ghana. Each dataset contributes unique information that enhances the depth and accuracy of the findings.
<p></p>
<b>Data Source:</b>
(Ghana Health Service; Pdf extracted)
<p></p>
<b>1. HIV Prevalence by Age Group Dataset:</b>
This dataset shows the proportion of HIV-positive individuals within each age group relative to the number tested. It supports the calculation of prevalence rates and helps identify age groups with higher vulnerability. This information is important for designing age-specific prevention and counselling programs.
<p></p>
<img width="560" height="298" alt="hiv prevalence by age group" src="https://github.com/user-attachments/assets/3ff194c0-4946-45d7-af61-c236d26f00e2" />

<p></p> 
<b>2. HIV Gender Estimates Dataset:</b>
This dataset breaks down HIV-positive cases by male and female populations. It is useful for examining gender disparities, understanding which groups are more affected, and supporting targeted public health responses. The data helps measure progress in reducing gender-based infection gaps.
<p></p>
<img width="663" height="258" alt="hiv gender estimate" src="https://github.com/user-attachments/assets/727f3fc0-775c-4d14-afbb-9c97895549fa" />
<p></p>

<p></p>
<b>3. HIV Positive by Age Group & Site Dataset:</b>
This dataset captures HIV cases categorized by different age groups and testing sites. It provides insight into which age ranges carry the highest infection burden. The dataset also helps identify site-specific variations that may affect surveillance, prevention, and testing strategies.
<p></p>
<img width="645" height="524" alt="hiv positive by age group and site" src="https://github.com/user-attachments/assets/331dfc4b-fdf1-4b23-b753-96e3a455f37d" />

<p></p>
<b>4. AIDS Related Deaths Dataset:</b>
This dataset contains annual records of AIDS-related deaths across the regions of Ghana. It helps assess the mortality burden associated with HIV and evaluates how deaths have changed over time. The data is essential for understanding the severity of the epidemic and identifying regions that require enhanced treatment and support services.
<p></p>
<img width="536" height="483" alt="aids related deahts" src="https://github.com/user-attachments/assets/95c68628-6e65-4751-8909-247718ab9290" />

<p></p>
<b>5. Ghana HIV Map (2004–2014):</b>
This dataset provides geographically referenced HIV-positive cases across Ghana’s regions, including coordinates such as latitude and longitude. It supports spatial analysis and the creation of map visuals that illustrate regional variations in HIV infections. It helps highlight geographic hotspots and spread patterns over the 10-year period.
<p></p>
<img width="502" height="617" alt="ghana hiv map" src="https://github.com/user-attachments/assets/9b1eb346-decb-4573-9b20-a237e201d526" />
<p></p>

## KEY VARIABLES AND THEIR MEANINGS
<img width="1361" height="707" alt="image" src="https://github.com/user-attachments/assets/4ff05a32-2cd4-4d6e-94f2-8a190fa8b17e" />
<P></P>

## OBJECTIVES
1. Determine the prevalence of HIV across different regions of Ghana from 2004 to 2014.
2. Analyze trends over the years to identify whether HIV prevalence is increasing, decreasing, or remaining stable.
3. Assess the distribution by age groups and gender to identify high-risk populations.
4. Compare regional differences to highlight areas with the highest and lowest prevalence.
5. Provide insights for public health interventions based on observed patterns and trends.
<P></P>

## DATA CLEANING & PREPARATION
<b>Tools Used: Excel, Power Bi,</b>
<p></p>
<b>Data cleaning involved:</b>
<ul>
  <li>Removing empty or duplicate rows</li>
  <li>Correcting inconsistent region names</li>
  <li>Ensuring uniform year formats</li>
  <li>Formatting numeric fields (percentages, totals, prevalence rates)</li>
  <li>Mapping regional capitals with accurate latitude and longitude values</li>
</ul>
<p></p>
<b>Data Modeling</b>   
<p></p>
<b>Tool Used: Power BI </b>
<p>Relationships were created in Power BI to connect datasets logically:</p>
<ul>
  <li>Region ↔ HIV Map Data</li>
  <li>Region ↔ Prevalence Data</li>
  <li>Region ↔ AIDS-Related Deaths</li>
  <li>Year ↔ HIV Positive / Gender Data</li>
</ul>

## KPIs
<img width="3508" height="2480" alt="2" src="https://github.com/user-attachments/assets/685bec56-920a-449b-bee2-182e68157cf9" />

## DASHBOARD 1: HIV Cases (Regional & Gender)
<ul>
  <li>KPIs for total male, female, and overall HIV cases</li>
  <li>Regional comparison of male vs. female cases</li>
  <li>Line chart showing trends in HIV-positive cases by region</li>
  <li>Gender distribution pie chart</li>
</ul>
<img width="3508" height="2480" alt="DASH 1" src="https://github.com/user-attachments/assets/68b5e062-aa96-4028-8d3e-50531f3f2c25" />

## DASHBOARD 2: AIDS-Related Deaths
<ul>
  <li>KPIs for male, female, and total deaths</li>
  <li>Gender death distribution</li>
  <li>Trend analysis showing decline in AIDS-related mortality</li>
</ul>
<img width="3508" height="2480" alt="DASH 2" src="https://github.com/user-attachments/assets/e5ba973c-4b28-4605-9787-59544abfe60e" />

## DASHBOARD 3: Geographic Map
<ul>
  <li>Filled map visual showing total HIV cases across regions</li>
  <li>Identification of high-burden regions (Greater Accra, Ashanti)</li>
  <li>Spatial distribution trends over the years</li>
</ul>
<img width="3508" height="2480" alt="DASH 3" src="https://github.com/user-attachments/assets/c883ac8c-74a7-4c83-b0b0-6a8f4fcab9ee" />

## DASHBOARD 4: Age Group & Site Analysis
<ul>
  <li>Regional breakdown of positive cases by age</li>
  <li>Hotspot sites with higher positivity rates</li>
  <li>Age brackets with highest infection burden (25–39 years)</li>
</ul>
<img width="3508" height="2480" alt="DASH 4" src="https://github.com/user-attachments/assets/e0063cbd-55fb-4c6e-b94e-581cc2faeca6" />
<p></p>

## FINDINGS & INSIGHTS

<b>1. Overall HIV Trends</b>
<ul>
  <li>HIV prevalence in Ghana shows steady regional and national growth over the 2004–2014 period.</li>
  <li>Greater Accra and Ashanti regions consistently report the highest number of HIV-positive cases, likely due to urbanization, higher population density, and increased mobility.</li>
  <li>Lower prevalence regions such as Upper West, Upper East, and Northern show slower growth but still require attention to prevent future outbreaks.</li>
</ul>
<p></p>

<b>2. Gender Disparities</b>
<ul>
  <li>Females consistently have higher HIV prevalence than males across almost all regions, accounting for roughly 55–60% of total HIV cases.</li>
  <li>Similarly, AIDS-related deaths are slightly higher in females, though overall deaths are declining over time due to improved treatment (ART programs).</li>
  <li> <b>Insight:</b> Gender-specific interventions targeting women are critical, including education, testing, and access to healthcare services.</li>
</ul>
<p></p>

<b>3. Age Group Patterns</b>
<ul>
  <li>HIV is concentrated in adults aged 25–39, with 25–29, 30–34, and 35–39 being the most affected age brackets.</li>
  <li>Younger populations (15–19) and older adults (45+) have lower prevalence, though awareness programs are still needed.</li>
  <li> <b>Insight:</b> Prevention and behavioral intervention campaigns should focus on high-risk adult groups, particularly in urban regions.</li>
</ul>
<p></p>

<b>4. AIDS-Related Deaths</b>
<ul>
  <li>AIDS-related deaths declined from ~24,639 in 2004 to ~16,277 in 2014, reflecting successful treatment interventions and ART rollout.</li>
  <li>Decline is more significant in males, possibly indicating better female engagement with care programs or higher initial female prevalence.</li>
  <li> <b>Insight:</b> Continuous treatment access and education are critical to sustaining this downward trend.</li>
</ul>
<p></p>

## SUMMARY
<b>1. Overall Trends:</b>
<ul>
  <li>HIV prevalence in Ghana from 2004–2014 shows a steady increase, with Greater Accra, Ashanti, and Central regions being the most affected.</li>
  <li>Urban regions report higher HIV-positive cases than rural areas, reflecting population density and mobility.</li>
</ul>
<p></p>

<b>2. Gender Disparities:</b>
<ul>
  <li>Females consistently show higher HIV prevalence than males, accounting for roughly 55–60% of total cases.</li>
  <li>AIDS-related deaths have declined overall, but females still represent a slightly higher proportion of deaths.</li>
</ul>
<p></p>

<b>3. Age Distribution:</b>
<ul>
  <li>Adults aged 25–39 years are most affected by HIV, indicating high-risk age groups.</li>
  <li>Younger (15–19) and older adults (45+) have lower prevalence rates but still require awareness interventions.</li>
</ul>
<p></p>

<b>4. Mortality Trends:</b>
<ul>
  <li>AIDS-related deaths decreased from ~24,639 in 2004 to ~16,277 in 2014, showing effectiveness of treatment programs (ART).</li>
  <li>Decline in deaths is slightly more noticeable in males than females, suggesting a need for sustained female-targeted interventions.</li>
</ul>
<p></p>

<b>5. High-Risk Populations and Hotspots:</b>
<ul>
  <li>High-risk demographic: women aged 25–39 in urban centers.</li>
  <li>Geographic hotspots: Greater Accra, Ashanti, and Central regions.</li>
</ul>

## RECOMMENDATIONS 
<b>Gender-Specific Interventions</b>
<ul>
  <li>Enhance HIV awareness, testing, and treatment access for women, particularly in urban regions</li>
</ul>
<p></p>

<b>Age-Targeted Programs</b>
<ul>
  <li>Focus on adults 25-39 through education, behavioral interventions and support programs</li>
</ul>
<p></p>

<b>Urban-Focused Strategies</b>
<ul>
  <li>Intensify prevention, testing and treatment campaigns in high prevalence urban regions</li>
</ul>

<p></p>

<b>Rural Outreach Programs</b>
<ul>
  <li>Implement mobile clinics, community awareness, and education to improve testing and treatment accessibility in rural areas </li>
</ul>
<p></p>

<b>Sustain ART and Healthcare Programs</b>
<ul>
  <li>Continue providing antiretroviral therapy and monitor treatment adherence to maintain declining AIDS-related deaths</li>
</ul>

## CONCLUSION
The comprehensive analysis of HIV trends in Ghana from 2004–2014 reveals a clear pattern shaped by gender, age, and regional disparities. 
<p></p>
HIV prevalence remains highest in Greater Accra, Ashanti, and Central, with urban areas recording significantly more cases than rural settings due to population density and wider testing coverage. Women continue to bear a disproportionate burden of infections, accounting for the majority of HIV-positive cases and AIDS-related deaths. Adults aged 25–39 emerged as the most affected demographic, emphasizing the need for targeted prevention and education within this productive age group. Despite rising HIV prevalence, the consistent decline in AIDS-related deaths demonstrates progress in treatment accessibility and effectiveness of ART programs. 
<p></p>
However, the persistent gender gap, urban concentration of cases, and growing burden among young adults highlight the need for tailored, region-specific interventions. Strengthening awareness, expanding testing services, improving ART adherence, and focusing on high-risk populations will be essential in sustaining progress and reducing the overall HIV burden across the country.
<p></p>

<img width="3508" height="2480" alt="3" src="https://github.com/user-attachments/assets/3dc27047-939f-4fad-92aa-7361e6045324" />
<p></p>

👨‍💻 <b>Author:</b>
Everking Nketia Godfred
Power BI Analyst | Data Enthusiast | Graphics Designer | Web Developer
<p>&copy; 2025 Everking. All rights reserved.</p>
