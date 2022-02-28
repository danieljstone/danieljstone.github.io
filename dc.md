---
title: D.C. Covid Deaths and Homicides
permalink: /dc/
layout: page
---

**Introduction**

This page presents detailed age-distribution data for covid mortality and homicides in Washington, D.C. from March 2020 to February 2022. To my knowledge, many of the numbers presented here are not available elsewhere.

 The only direct connection that I draw between the covid pandemic and homicide surge is that:

-  in the last two years they have received more public attention than any other causes of deaths in the nation's capital and 
- have been considered addressable if not largely solvable by public policy. 

**Background**

I was motivated to compile the covid data presented here after finding it was impossible to calculate the ratio of reported covid cases to deaths across age groups using published data. (The D.C. government uses different age brackets for case data and fatality data.)

 I sought these numbers in my effort to investigate whether early-stage vaccination distribution strategy targeted groups who would benefit from the vaccine. I ultimately found that a large proportion of then-scarce doses were going to young people at virtually no risk of dying from covid, while many older people continued to die from the virus, which I wrote about in [The Washington Post](https://www.washingtonpost.com/opinions/2021/03/30/why-are-half-newly-vaccinated-people-dc-younger-than-44/).

I was motivated to compile the homicide data presented here in effort to better understand the District's [widely-reported](https://www.washingtonpost.com/local/public-safety/homicides-rise-washington/2020/12/31/59dd659e-3953-11eb-bc68-96af0daae728_story.html) surge in homicides during the covid pandemic.

The main finding presented here is unsurprising. Since March 2020, Washington D.C. has faced two epidemics: one of the old (covid) and one of the young (violence). However, writing in the early months of 2020, the extent to which age distributions of each differ is rarely acknowledged.

There are a lot of different ways to present this data, so I welcome any suggestions.

## The Charts

#### Total Homicides and Covid Deaths

**Monthly Homicides and Covid Deaths March 2020 - Present**

{% include /dccharts/monthlychart.html %}

**Total Homicides and Covid Deaths March 2020 - Present**

{% include /dccharts/cumchart.html %}

#### Overall Covid Data (March 2020-Present)

**All D.C. Covid Deaths by Age, March 2020 - Present** 

{% include /dccharts/covidbyage.html %}

**All D.C. Covid Deaths by Age, March 2020 - Present, Population Adjusted**

Census data only provides population estimates for the 85+ population, which means that the rightmost bar corresponds to that group.

{% include /dccharts/covidage_adjusted.html %}


**Percent of D.C. Covid Cases Resulting in Deaths, March 2020 - Present **


{% include /dccharts/cfr.html %}

#### Covid Data Since Widespread Vaccination (May 2021-Present)

**All D.C. Covid Deaths by Age, May 2021 - Present **

{% include /dccharts/covidagepv.html %}

**All D.C. Covid Deaths by Age, May 2021 - Present, Population Adjusted**

Census data only provides population estimates for the 85+ population, which means that the rightmost bar corresponds to that group.



{% include /dccharts/covidage_adjustedpv.html %}



#### Homicide Data (March 2020-Present)

**Homicides by Age**

{% include /dccharts/homicidesage.html %}

**Homicides by Age, Population Adjusted**

{% include /dccharts/homicide_adjusted.html %}

**Homicides by Age and Gender, Population Adjusted**

{% include /dccharts/homicide_adjusted_gen.html %}



#### Comparing Homicide Data and Covid Fatality Data

**Overall Incidence**

{% include /dccharts/combinedchart.html %}

**Incidence Since May 2021**

{% include /dccharts/postvaxcombinedchart.html %}



**Incidence Since May 2021, Population Adjusted**

Census data only provides population estimates for the 85+ population, which means that the rightmost bar corresponds to that group.

{% include /dccharts/pv_popadjusted.html %}







## Sources



**Case Counts** D.C. Government (Retrieved February 24, 2022) (This page may be overwritten.)

**Population Counts**  [U.S. Census Bureau (2020 Singe-Age Population Estimate)](https://www2.census.gov/programs-surveys/popest/datasets/2010-2020/state/asrh/SC-EST2020-AGESEX-CIV.csv)

**Age Count Data**  I wrote a script that extracts age, date, and gender information from Washington, D.C.'s semi-daily press releases, which list more specific information for each covid decedent than is included in published numbers.

**Homicide Data** I scraped most of the data from [DCWitness.org](https://dcwitness.org/interactive-map/), but filled in a number of gaps (namely missing ages) with my own research.

