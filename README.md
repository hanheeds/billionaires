# Understanding the Underpinnings of Vast Wealth: An Exploratory Analysis of Billionaire Traits

In an endeavor to understand the underpinnings of vast wealth, I embarked on an exploratory analysis of billionaires' traits, aiming to uncover the patterns and characteristics shared among the world's richest. As thus, my initial question as an aspiring wealthy person was as follows:

### What are the most common characteristics of billionaires?

## Dataset Overview

The exploration began with sourcing a comprehensive 2023 dataset detailing statistics on all recorded billionaires, yielding an extensive list of 2,640 individuals (rows) whose financial stature towers above the rest. As the organization and title column of the dataset were very sparse and not important to this topic, those columns were removed from the dataset during data cleaning.

## Section 1: Demographics of Billionaires

### Age Distribution

At the heart of the demographic examination is age — a crucial factor in wealth accumulation. The data suggests a bell-shaped age distribution, with the pinnacle between 50 and 75 years old. This distribution implies that youth and very old age are less associated with this level of affluence. This makes sense as it is very uncommon that if you are younger than 50 years old, you are most likely still building up wealth. I’d assume that the number drops off after 75 not because of old age, but because of death. The mean age of death of the world is 73, which pretty much lines up with the drop off the number of billionaires.

![Age Distribution](https://github.com/hanheeds/billionaires/blob/main/images/Age.png)

### Gender Distribution

Next, I wondered, does gender play a role? The gender landscape among billionaires is markedly uneven. A staggering 87% are male, while a mere 13% are female, signaling a pronounced gender gap in the highest echelons of wealth.

![Gender Distribution](https://github.com/hanheeds/billionaires/blob/main/images/Gender.png)

From the individual demographic characteristics, my curiosity naturally led me to the stage upon which these billionaires act: the global arena.

## Section 2: Overview of the Billionaires

### Global Distribution of Billionaires

Intrigued by demographics, I turned to geography. A glimpse into the geographic dispersal uncovers that the United States and China are the front-runners, hosting the majority of billionaires. Countries like India, Germany, the UK, and Russia also feature significantly on the map, revealing a global distribution with notable concentrations.

![Global Distribution](https://github.com/hanheeds/billionaires/blob/main/images/Global%202.png)

### Old Money vs New Money

Based upon the distribution of the countries and my knowledge of countries, I wondered, is it easier to succeed / become a billionaire with “new money” in a capitalist country like America? I decided to check. While America had around ⅔ of its billionaires come from new money, China, a communist country, had almost all of its billionaires come from new money. In general, I was surprised by the amount of self-made billionaires in general. This was in contrast to countries such as India and Germany where a majority of their billionaires originated from “old money” or inheriting wealth from their parents.

![Old Money vs New Money](https://github.com/hanheeds/billionaires/blob/main/images/Self-made.png)

Understanding the countries set the stage, but it was time to peel back the curtain on the how—what was the specific environment like that allowed these individuals to amass such wealth?

## Section 3: Economic Sectors and Wealth Sources

### Industries Dominated by Billionaires

Moving beyond who they were and where they hailed from, I delved into the 'how', Technology, fashion & retail, and finance & investment surface as the dominant sectors among billionaires. Conversely, construction & engineering, gambling & casinos, and sports are the least represented industries.

![Industries Dominated by Billionaires](https://github.com/hanheeds/billionaires/blob/main/images/Industries.png)

### Sources of Wealth

I drilled down further, seeking the sources of their wealth. The roots of billionaire wealth are diverse, yet real estate stands out as a primary source. Investments, diversified portfolios, pharmaceuticals, and software also emerge as significant contributors.

![Sources of Wealth](https://github.com/hanheeds/billionaires/blob/main/images/Sources.png)

With the sectors and sources of wealth laid bare, I turned my attention to the broader economic and geopolitical context, where individual wealth meets national economy.

## Section 4: Geographical and Economic Context

### Wealth and Country GDP

Contemplating the relationship between personal and national wealth, I plotted billionaires' net worth against their country's GDP. The scatterplot told a tale of correlation but with outliers like Bernard Arnault, who stood apart. Why? What did he do differently?

![Wealth and Country GDP](https://github.com/hanheeds/billionaires/blob/main/images/Sources.png)

## Section 4.5: Bernard Arnault

### A tangent into Bernard Arnault…

Could it be that Bernard Arnault's exceptional rise among his fellow billionaires in nations with a GDP cap of $5 million unveils a secret formula for success? When we zoom into the sectors thriving within these economies, it's fascinating to note that Fashion & Retail emerges as the go-to industry for the ultra-wealthy.

![Bernard Arnault](https://github.com/hanheeds/billionaires/blob/main/images/Industry%20Arnault.png)

France commands the stage as a global fashion powerhouse (according to the Brands Countries IPX by IFDAQ). It’s no surprise then that even within France, billionaires and high fashion are a match made in luxury heaven. Does this mean Arnault's staggering success was just a stroke of genius in playing the game better than anyone else? What really distinguishes him if not the glittering industry he dominates?

![Bernard Arnault2](https://github.com/hanheeds/billionaires/blob/main/images/Industry%20France.png)

Zeroing in on France seemed like the logical next step. Peeling away the layers of national data, I honed in on the distinctions that spotlight the individual brilliance of Arnault. It’s striking to see that the crème de la crème of French brands are sewn from the fabric of Fashion & Retail. While it's impossible to pinpoint the exact threads of Arnault's net worth towering over his peers just based on this dataset, it's unmistakably evident that a flair for fashion in France can weave a tapestry of immense wealth. 

![Bernard Arnault2](https://github.com/hanheeds/billionaires/blob/main/images/France.png)

Now back to the main picture…

## Life Expectancy and Billionaire Presence

For my final analysis, I probed into how the health of a nation might reflect its wealth. Life expectancy surfaced as a positive correlation to billionaires' fortunes. Each additional year of expected life corresponded to a $59 million rise in a billionaire's net worth. Could this observed correlation imply a causal relationship, or is it simply a coincidental association?

![Life Expectancy and Billionaire Presence](https://github.com/hanheeds/billionaires/blob/main/images/Life%20Expectancy.png)

# Conclusion: Understanding the World of Billionaires

This investigation has revealed that billionaires are typically male, middle-aged or older, and hail predominantly from countries with strong GDPs and higher life expectancies. They frequently emerge from industries like technology and finance and often rely on real estate and diversified investments to build their fortunes.

## Appendices

### Data Sources

The dataset was obtained from Kaggle under the name Billionaires Statistics Dataset (2023) which was compiled by Nidula Elgiriyewithana.
[https://www.kaggle.com/datasets/nelgiriyewithana/billionaires-statistics-dataset/data](https://www.kaggle.com/datasets/nelgiriyewithana/billionaires-statistics-dataset/data)

### Insights

This article displays how France is the leading country in fashion. Please feel free to check it out.
[https://www.statista.com/statistics/1202694/fashion-industry-leading-countries-worldwide/](https://www.statista.com/statistics/1202694/fashion-industry-leading-countries-worldwide/)
