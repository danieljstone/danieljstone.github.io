---
layout: post
title:  "The Coronavirus Numbers I Follow"
date:   2020-08-01 23:03:25 -0400
categories: numbers
---

### Background

In April, I couldn't find a website that had rolling averages of U.S. coronavirus death and case counts.  So I made a spreadsheet calculating weekly average counts and shared it with some friends.


Since then, I have continued to add other summary statistics and charts to the spreadsheet, taking advantage of the growing availability of reliable and easy-to-use data sources, namely the COVID Tracking Project.  Here I've assembled some of these charts.

The data should automatically refresh every day, though the CDC age data are updated less frequently.

## The Charts
### Rolling Indexed 7-Day Averages
This chart takes weekly case, death, positive, and test counts and divides them by their highest values in the past 150 days. This helps show how things stand today relative to where they have stood in the past five months.  For instance, if there is a spike in deaths in one week, this chart makes it easy to tell whether that spike has a greater magnitude than past spikes.

There are a lot of things that this chart does not show---among them actual counts. Relatedly, formulating this chart so that there is always a 100% value for every metric means that numbers that are actually small can appear large.

<iframe width="987" height="600" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=793749523&amp;format=interactive"></iframe>

### Looking at with Recent Increases in Death and Case Counts
With the next charts I look at whether recent surges in death and case counts are happening in places that did not experience the initial wave as harshly as other states.  To do this I generated two pairs of charts. The first looks at places that have seen an increase in case counts (the focus of many initial news reports) and the second looks at death counts.

#### States with higher case counts today than in April
* In the first pair of charts, I divide states into two groups:
  * states where weekly case counts are currently lower than they were on April 21 (the peak of the first wave) and
  * states where the case counts are lower.
* I graph death and case data about the groups in two ways:
  * The first chart plots raw weekly death and case counts.
  * The second plot looks at total per capita numbers for the same two groups.


**Counts**
<iframe width="785" height="498" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=1568055513&amp;format=interactive"></iframe>
**Cumulative Per Capita Counts**
<iframe width="785" height="592" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=576510956&amp;format=interactive"></iframe>


#### States with higher death counts today than in April
* In the second pair of charts, I divide states into two groups:
  * states where weekly death counts are currently lower than they were on April 21 (the peak of the first wave) and
  * states where the death counts are lower. The first chart plots raw weekly death and case counts, while the second plot looks at total per capita numbers for the same two groups.
* I graph death and case data about the groups in two ways:
  * The first chart plots raw weekly death and case counts.
  * The second plot looks at total per capita numbers for the same two groups.
**Counts**  
<iframe width="805" height="498" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=140196596&amp;format=interactive"></iframe>
**Cumulative Per Capita Counts**
<iframe width="805" height="592" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=550498935&amp;format=interactive"></iframe>

### Tri-state Area Versus the Rest of the Country

#### Cumulative Death Counts
This chart illustrates how at the start of the pandemic, the Tri-state Area saw a disporportionate portion of coronavirus deaths compared with the rest of the county.

<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=1357899177&amp;format=interactive"></iframe>

#### Per Capita Death Counts
At the time of writing, this chart shows that at least on a per capita basis, the Tri-state area has been hit especially hard compared with the rest of the country.

<iframe width="287" height="406" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=404931936&amp;format=interactive"></iframe>

### Trump States v. Clinton States
This chart compares how both weekly and cumulative death counts have changed over time in states that Donald Trump won with states that Hillary Clinton won.

<iframe width="489" height="406" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=941948628&amp;format=interactive"></iframe>

### Deaths by Age
Here are two charts that show the age-distribution of coronavirus deaths.

#### Coronavirus Numbers Only
I would have liked to use a pie chart here to show the extent to which coronavirus has disproportionately affected older Americans, but the numbers for younger age groups were too small to be visible.  Instead here the counts are shown on a logarithmically scaled bar chart.

<iframe width="765" height="252" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=108151911&amp;format=interactive"></iframe>

#### Including non-Coronavirus Deaths
This chart incorporates data about deaths attributed to other causes during the same period.  As I understand it, non-coronavirus deaths here may include excess deaths that might otherwise be attributable to coronavirus.

<iframe width="769" height="676" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=1175736046&amp;format=interactive"></iframe>

## Tables about States
The following tables are fairly self explanatory.

**States by Deaths per Thousand**
<iframe width="328" height="498" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=965571508&amp;format=interactive"></iframe>
**States by Cases per Thousand**
<iframe width="348" height="498" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=1117844997&amp;format=interactive"></iframe>
**New Weekly Cases**
<iframe width="415" height="498" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=1984358509&amp;format=interactive"></iframe>
**New Weekly Deaths**
<iframe width="415" height="498" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=1049778343&amp;format=interactive"></iframe>
**Weekly Cases Per Million People**
<iframe width="328" height="498" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=1768093945&amp;format=interactive"></iframe>
**Weekly Deaths Per Million People**
<iframe width="328" height="498" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyrpfNTurjdXm3Im0H6jVSqNYZHNg9oEQngbyOFCH8vkHF7s4lLEl9I1VFpb4ZQ8mHJ_--VNEsLwMI/pubchart?oid=1523288557&amp;format=interactive"></iframe>
### Sources

* Most of the numbers here come from the COVID Tracking Project.  The underlying data can be accessed [here](https://covidtracking.com/data/api).
* Age data come from the  [CDC](https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-by-Sex-Age-and-S/9bhg-hcku).
* I have used Census projections for 2019 state population for all "per capita" data, which may be found [here](https://www.census.gov/data/tables/time-series/demo/popest/2010s-state-total.html).

