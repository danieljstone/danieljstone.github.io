---
title: Presidential Coverage
permalink: /presidents/
layout: page
---

During the years of the Trump administration, it felt like Donald Trump was everywhere you looked. This was especially the case with the New York Times, where it sometimes seemed as though the whole paper was on the Trump beat. But was this truly the case?

Looking at the number of news articles and opinion articles mentioning Donald Trump shows that it was difficult to avoid him wherever you turned during the years of his presidency. Further, comparing numbers from the Trump years with other recent presidents demonstrates the extent to which the Times' coverage was particularly extensive.

Previously, some have attempted frequency analysis that looks at the number of times a word has appeared in the Times to measure the penetration of a concept. However, I submit that in this case the better measure is the proportion of articles and opinion pieces published that mention Trump or another. It represents, in my view, the likelihood of picking an article at random and encountering him, rather than something more abstract. This is to say that our goal is not lexical analysis, which might identify the emergence of a concept vis-á-vis a term's prevalence.

The figure below shows how many news articles, op-eds, and editorials mentioned "Trump" in a given week, from late 2014 to early 2022. I include the earlier data to show that even after the announcement of his candidacy on June 16, 2015, Trump did not factor particularly into Times coverage. Further, since "trump" is a word in its own right, it serves as a sort of control to demonstrate that the numbers we see correspond to the person. I include data for the period following the inauguration of Joe Biden on January 21, 2021 to show the extent to which Donald Trump remains in view.

{% include trumpweekly.html %}

To better comprehend the above, it is helpful to divide the above into several periods in the Trump timeline: prior to candidacy, candidacy to nomination, nomination to election, election to defeat, defeat to inauguration, and inauguration to early 2022. 

| Period                              | Weekly Average News | Weekly Average Op-Eds | Weekly Average Editorials | Week of Highest News Coverage | Number of Weeks when Every  Editorial Mentioned "Trump" |
| ----------------------------------- | ------------------- | --------------------- | ------------------------- | ----------------------------- | :-----------------------------------------------------: |
| Before candidacy                    | 0.78%               | 2.48%                 | 0.65%                     | 3/30/2015 (1.40%)             |                            0                            |
| Candidacy to Nomination             | 8.53%               | 22.76%                | 11.01%                    | 7/18/2016 (21.87%)            |                            0                            |
| Nomination to Election              | 14.80%              | 46.42%                | 33.17%                    | 11/7/2016 (37.07%)            |                            0                            |
| Election to Defeat                  | 24.16%              | 51.63%                | 61.85%                    | 1/30/2017 (39.79%)            |                            9                            |
| Defeat to Biden Inauaguration       | 30.45%              | 57.64%                | 65.49%                    | 11/2/2020 (49.10%)            |                            3                            |
| Biden Inauguration to February 2022 | 11.83%              | 31.35%                | 43.75%                    | 1/25/2021 (26.14%)            |                           15                            |



The weeks of highest coverage, which is to say the proportion of news articles mentioning Trump, identified above are unsurprising: nomination, election, ascension, defeat, and stepping down from office. What is most worth noting are the rows corresponding to the dates of the Trump presidency, which show that roughly 1 in 4 news articles, 1 in 2 op-eds, and 1 in 2 editorials mentioned him.

To make sense of what the Trump numbers actually mean, we can compare them to other recent and current presidents.



# **How the Trump Numbers Compare**



I think that it is most fruitful to compare the Times's proportional treatment of different presidents by centering the data around the dates of their first inaugurations. Here I consider data for news articles, op-eds, and editorials in turn across the presidencies of Bill Clinton, George W. Bush, Barack Obama, Donald Trump, and Joe Biden.  

Since, as is shown above, weekly numbers are quite messy to look at for a single president, here I will use monthly numbers. I also tabulate 48-month numbers for each chart, corresponding roughly to a president's first term. While three of the presidencies under consideration were two-term presidencies (Clinton, Bush, Obama), it makes for a more even measure. (The Biden numbers correspond to January 2021 to February 2022)



**News Articles**

{% include newschart.html %}

|                  | Clinton | Bush   | Obama  | Trump  | Biden  |
| ---------------- | ------- | ------ | ------ | ------ | ------ |
| 48-Month Average | 9.78%   | 11.81% | 12.12% | 24.85% | 19.63% |
| 48-Month Minimum | 6.87%   | 8.23%  | 8.73%  | 19.89% | 15.18% |
| 48-Month Maximum | 16.46%  | 15.79% | 20.29% | 35.88% | 31.56% |

The Trump effect is quite pronounced here, with more than twice as great a proportion of articles being written mentioning Trump than Obama; similarly Obama's month of greatest coverage is only 0.4% greater than Trump's month of least coverage. Biden coverage comes closest, but as shown in the graph appears to be tapering off. 



**Op-Eds**

{% include opedchart.html %}

|                  | Clinton | Bush   | Obama  | Trump  | Biden  |
| ---------------- | ------- | ------ | ------ | ------ | ------ |
| 48-Month Average | 39.96%  | 51.50% | 40.19% | 52.49% | 37.49% |
| 48-Month Minimum | 26.55%  | 31.45% | 23.67% | 37.44% | 28.63% |
| 48-Month Maximum | 60.71%  | 69.72% | 73.05% | 73.52% | 58.48% |

There is relative parity in the proportion of op-eds that have mentioned each president, but Trump is still highest on average. 

**Editorials**

{% include editorialchart.html %}

|                  | Clinton | Bush   | Obama  | Trump  |
| ---------------- | ------- | ------ | ------ | ------ |
| 48-Month Average | 33.69%  | 41.45% | 36.67% | 62.01% |
| 48-Month Minimum | 21.15%  | 25.26% | 28.35% | 40.74% |
| 48-Month Maximum | 46.61%  | 54.55% | 55.08% | 77.89% |

The Times changed the way it indexes editorials in 2020, which forces us to exclude (until I can verify my hand counts) the Biden presidency. However, as with news coverage, the Trump presidency received markedly more attention from the Times's editorial board than previous presidencies. 





**Sources**

The above data were collected using the New York Times's [Article Search API](https://developer.nytimes.com/docs/articlesearch-product/1/overview).











