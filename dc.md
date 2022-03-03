---
title: D.C. Covid Deaths and Homicides
permalink: /dc/
layout: page
---

**Introduction**

This page presents detailed age-distribution data for covid mortality and homicides in Washington, D.C. from March 2020 to February 2022. Most of the numbers presented here are not available elsewhere since they come from recreating a non-public database. Moreover, typical covid and homicide age-distribution data groups populations in large bands (e.g., 34-55), meaning that one rarely sees the shape of the underlying data.

To be clear, the only direct connection that I draw between the covid pandemic and homicide surge is that:

-  in the past two years they have received more public attention than any other causes of deaths in the nation's capital and 
- have been considered addressable if not largely solvable by public policy. 

As a consequence, I think the charts and numbers shown on this page should be part of the discussion around these topics. Further, they ought to be published by the government of Washington, D.C. rather than by me.

**Background**

I was motivated to compile the covid data presented here after finding it was impossible to calculate the ratio of reported covid cases to deaths across age groups using published data. (The D.C. government uses different age brackets for case data and fatality data.)

I sought these numbers in effort to investigate whether early-stage vaccination distribution strategy targeted groups that would benefit from the vaccine. I ultimately found that a large proportion of then-scarce doses were going to young people at virtually no risk of dying from covid, while many older people continued to die from the virus, which I wrote about in [The Washington Post](https://www.washingtonpost.com/opinions/2021/03/30/why-are-half-newly-vaccinated-people-dc-younger-than-44/).

I was motivated to compile the homicide data presented here in effort to better understand the District's [widely-reported](https://www.washingtonpost.com/local/public-safety/homicides-rise-washington/2020/12/31/59dd659e-3953-11eb-bc68-96af0daae728_story.html) surge in homicides during the covid pandemic.

The main finding presented here is unsurprising. Since March 2020, Washington D.C. has faced two epidemics: one of the old (covid) and one of the young (violence).

There are a lot of different ways to present this data, so I welcome any suggestions.

## The Charts

#### Total Homicides and Covid Deaths

Before turning to the age-distribution data, it is worth looking at two more familiar charts about how covid deaths and homicides have occurred over time.

**Monthly Homicides and Covid Deaths March 2020 - Present**

This chart shows the peaks and troughs that correspond to covid's primary waves: the initial surge, delta, and omicron. Further, it shows a period between May and December of 2021 when monthly homicides exceeded covid deaths; some hay has been made of this period, but seen in a broader (and more appropriate) context, we can see that it mostly corresponded with the timing of D.C.'s vaccination program and the receding delta surge. 

{% include /dccharts/monthlychart.html %}

**Total Homicides and Covid Deaths March 2020 - Present**

This chart shows the accumulation of covid deaths and homicides since March of 2020. What is particularly strikingly visible are the impacts of the two first covid surges.

{% include /dccharts/cumchart.html %}

#### Overall Covid Data (March 2020-Present)

**All D.C. Covid Deaths by Age, March 2020 - Present** 

This chart shows the number of people of a given age who have died of covid in Washington, D.C. since the start of the pandemic. Even without correcting for how many people of a given age actually live in D.C. (the next chart), we can see that the population skews older. The median age of a covid decedent is 72.  The youngest reported age is 17 and that is something of an outlier. 

{% include /dccharts/covidbyage.html %}

**All D.C. Covid Deaths by Age, March 2020 - Present, Population Adjusted**

This chart is an important complement to the previous chart. Each bar represents the number of covid deaths as a proportion of the population of people of a given age in Washington. As you can see, one is actually exponentially more likely to have died of covid the older one is; the effect is accentuated by the fact that DC's population skews heavily towards young adults.

{% include /dccharts/covidage_adjusted.html %}

*Census data only provides population estimates for the 85+ population, which means that the rightmost bar corresponds to that group.*

To better understand the numbers in the above chart, it is helpful to tabulate the another representation the data—the 1 in X probabilities of someone of a given age having died of covid:

|                                   Age Group |      0-9      |      10-19      |      20-29      |    30-39     |    40-49     |     50-59      |     60-69      |     70-79     |      80+       |
| ------------------------------------------: | :-----------: | :-------------: | :-------------: | :----------: | :----------: | :------------: | :------------: | :-----------: | :------------: |
|         People in Age Group per Covid Death | 1 in ∞ (none) | 1 in     66,645 | 1 in     26,270 | 1 in   4,460 | 1 in   1,495 | 1 in       431 | 1 in       193 | 1 in      120 | 1 in        56 |
| Increase in Rate versus next youngest group |       -       |        -        |      2.5 X      |    5.9 X     |     3 X      |     3.5 X      |     2.2 X      |     1.6 X     |     2.1 X      |



 **Percent of D.C. Covid Cases Resulting in Deaths, March 2020 - Present**  

Trying to make this chart led to my making this page. We can see that getting covid has been a lot more deadly for older people than younger people, and also generally more deadly for men. While there are a number of issues attendant to using case counts, such as the prevalence of testing, even directionally this chart shows the extent of these trends.


{% include /dccharts/cfr.html %}

#### Covid Data Since Widespread Vaccination (May 2021-Present)

In this section, I try to explore whether the ready availability of the covid vaccine, which I date to May 2021, corresponded to any changes in the age distribution of covid fatalities. There are certain obvious complications that arise in making any definitive conclusions, namely the fact that the sample size is much smaller: only about 205 of the 1,309 reported covid deaths in Washington, D.C.  (16%) have occurred since then. This reduction in itself partly attests to the efficacy of the vaccination regime and also the waning of the virus. 

**All D.C. Covid Deaths by Age, May 2021 - Present**

The crucial difference between the age distribution here and the overall data above is that the numbers skew slightly younger. The overall median is 68 versus 72. The range of ages is also much narrower, though it is hard to tell how much that is attributable to the difference in the number of deaths under consideration.

{% include /dccharts/covidagepv.html %}



**All D.C. Covid Deaths by Age, May 2021 - Present, Population Adjusted**

What is striking about the post-vaccination, population-adjusted chart is the extent to which it no longer skews so heavily right. The diminished risk of the chance of dying from covid is also clearer in this form.

{% include /dccharts/covidage_adjustedpv.html %}

*Census data only provides population estimates for the 85+ population, which means that the rightmost bar corresponds to that group.*

To better understand the numbers in the chart, it is again helpful to tabulate the another representation the data—the 1 in X probabilities of someone of a given age having died of covid:

| Age  Group                                                   | 0-9           | 10-20         | 20-29         | 30-39       | 40-49      | 50-59      | 60-69      | 70-79    | 80+      |
| ------------------------------------------------------------ | ------------- | ------------- | ------------- | ----------- | ---------- | ---------- | ---------- | -------- | -------- |
| March 2020 - May 2021                                        | 1 in ∞ (none) | 1 in 66,645   | 1 in 26,270   | 1 in 6,132  | 1 in 1,936 | 1 in 537   | 1 in 235   | 1 in 144 | 1 in 62  |
| May 2021 - Present                                           | 1 in ∞ (none) | 1 in ∞ (none) | 1 in ∞ (none) | 1 in 16,352 | 1 in 6,554 | 1 in 2,180 | 1 in 1,087 | 1 in 727 | 1 in 554 |
| Difference  (x times less likely to die of covid after May 2021) | -             | -             | -             | 2.7         | 3.4        | 4.1        | 4.6        | 5        | 8.9      |

#### Homicide Data (March 2020-Present)

**Homicides by Age**

Whereas, covid is a disease that affects older people most, most homicide victims are between 24 and 40, with a median age of 30.  It also demands noting that there are many very young victims (19 under the age of 18), whereas no covid deaths of people under 18 have been recorded in Washington, D.C.

{% include /dccharts/homicidesage.html %}

**Homicides by Age, Population Adjusted**

This chart mainly shows that, unlike with covid, accounting for population does not skew the prevalence of homicides markedly rightwards. This is to say that even though D.C.'s population is disproportionately young adults, homicides even more disproportionately affect that population. 

{% include /dccharts/homicide_adjusted.html %}

**Homicides by Age and Gender, Population Adjusted**

Disaggregating data by gender shows the extent to which young men are homicide victims (as high as 1 in 280 for men aged 22 versus 1 in 570 for all 22 year-olds ).

{% include /dccharts/homicide_adjusted_gen.html %}

To better appreciate these numbers, it is helpful to tabulate them by age group and gender:

| Age Group |     0-9     |   10-19    |   20-29    |   30-39    |   40-49    |   50-59    |    60-69    |    70-79    |     80+     |
| --------: | :---------: | :--------: | :--------: | :--------: | :--------: | :--------: | :---------: | :---------: | :---------: |
|   Overall | 1 in 24,813 | 1 in 1,625 |  1 in 796  | 1 in 1,258 | 1 in 1217  | 1 in 2,248 | 1 in 4,765  | 1 in 9,627  | 1 in 11,350 |
|       Men | 1 in 19,063 | 1 in 8,92  |  1 in 437  |  1 in 695  |  1 in 795  | 1 in 1,422 | 1 in 3,119  | 1 in 16,090 | 1 in 4,096  |
|     Women | 1 in 36,312 | 1 in 8,632 | 1 in 3,012 | 1 in 5,866 | 1 in 3,076 | 1 in 9,095 | 1 in 11,291 | 1 in 7,473  |      -      |

#### Comparing Homicide Data and Covid Fatality Data

The following charts compare homicide and covid death age distribution. They mainly illustrate the very divergent populations most affected by each cause of death.

**Overall Incidence**

{% include /dccharts/combinedchart.html %}

**Incidence Since May 2021**

We see here how the reduction in covid fatalities in more recent months has meant that the numbers of lives lost to both homicides (180) and covid (209) since May 2021 are comparable. 

{% include /dccharts/postvaxcombinedchart.html %}

**Incidence Since May 2021, Population Adjusted**

{% include /dccharts/pv_popadjusted.html %}

*Census data only provides population estimates for the 85+ population, which means that the rightmost bar corresponds to that group.*





## Sources



**Case Counts** D.C. Government (Retrieved February 24, 2022) (This page may be overwritten.)

**Population Counts**  [U.S. Census Bureau (2020 Singe-Age Population Estimate)](https://www2.census.gov/programs-surveys/popest/datasets/2010-2020/state/asrh/SC-EST2020-AGESEX-CIV.csv)

**Age Count Data**  I wrote a script that extracts age, date, and gender information from Washington, D.C.'s semi-daily press releases, which list more specific information for each covid decedent than is included in published numbers. You can find the raw data [here](https://github.com/danieljstone/DC-COVID-Deaths-Age-Gender/blob/main/dc_covid_deaths.csv).

**Homicide Data** I scraped most of the data from [DCWitness.org](https://dcwitness.org/interactive-map/), but filled in a number of gaps (namely missing ages) with my own research.

