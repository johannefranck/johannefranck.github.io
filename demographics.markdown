---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: custom_home
title: Sociodemographics 
hero_title: Sociodemographics
hero_subtitle: Exploring the Demographics and Sociodemographic data to the People in Copenhagen
---

## <a id="Sociodemographics"></a>Sociodemographics

>🎵 *Is Nørrebro all red and bold?*\
>🎵 *Does Frederiksberg stay rich and cold?*  

Having explored how election results have evolved across the last six national elections, we now turn our attention to the people behind the votes. Shifts in political outcomes may reflect changes in party landscapes — with new parties emerging and others declining — but they may also reflect changes in the population itself.

In this section, we take a closer look at Copenhagen’s demographics to better understand these underlying shifts. Who lives in the city? How has that changed over time? And how might these trends relate to what we observe politically?

We begin by exploring how the total population has grown, followed by an examination of the age, origin, and educational background of residents. We then dive into key socioeconomic factors like income and support types, comparing patterns across districts and years. Finally, we consider how rising incomes appear to correlate with increasing housing sizes — offering a more nuanced view of life in Copenhagen over the past two decades.


### Population Growth over Time


The city of Copenhagen has seen continuous population growth over the last 20 years, driven by both natural increase and migration. This growth provides crucial context for understanding electoral changes: more people means more voters — and possibly a shifting voter base.

**Insert plot: Raw count of residents over time**


<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
        <iframe src="assets/age_stacked_line_plot.html" 
                title="Interactive Bar Chart of Age Distribution Trends for Constituencies"
                style="display: block; margin: auto; border: none; width: 100%; max-width: 900px;" 
                height="550">
        </iframe>
        <figcaption style="margin-top: 0.75rem; font-style: italic;">
        <strong>Figure X:</strong> OBS AGE! 
        </figcaption>
</figure>

The population increased steadily, especially between 2005 and 2020. This is likely influenced by both internal urbanization and international immigration. Such demographic shifts may explain part of the evolving political support observed in the Elections section.



### Diversity and Education

Copenhagen’s population has changed notably over the past two decades, both in terms of background and educational level. Two important aspects of this development are the increasing share of residents with immigrant backgrounds and the rising number of highly educated citizens.

**Insert plot: Origin (immigrant status) over time or by share**  ?

**Insert plot: Education level (e.g., primary, vocational, higher) by year**


<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
        <iframe src="assets/education_stacked_line_plot.html" 
                title="Interactive Bar Chart of Education Distribution Trends for Constituencies"
                style="display: block; margin: auto; border: none; width: 100%; max-width: 900px;" 
                height="550">
        </iframe>
        <figcaption style="margin-top: 0.75rem; font-style: italic;">
        <strong>Figure X:</strong> OBS AGE! 
        </figcaption>
</figure>

The proportion of immigrants and descendants of immigrants has grown steadily, especially in districts like Nørrebro and Bispebjerg. 

In parallel, educational attainment has increased across the city. Inner districts in particular have a high share of university-educated residents. This aligns with broader urban trends where education level correlates with support for progressive parties, especially on issues such as climate change, equality, and education policy. Nørrebro has a very high share of highly educated residents while Tårnby on the other hand has very few higher educated residents. This might also be a result of the older residents in Tårnby compared to Nørrebro. 

These developments help explain shifts in electoral patterns across Copenhagen and suggest an evolving voter base influenced by both cultural background and educational profile.







## Socioeconomic Divides - From Paychecks to Pensions

This section delves into Copenhagen’s constituencies, examining income support and income. We aim to explore whether economic disparities align with voting preferences and whether the persistent stereotypes about neighborhoods hold true.

Our data spans three reference years (2009, 2014, 2019), capturing a decade marked by financial crises, migration waves, and evolving policy priorities. This temporal scope allows us to observe how economic conditions have shifted over time. By analyzing these socioeconomic factors, we can explore how economic shifts may have influenced public opinion and political priorities across the city. Existing narratives suggest that income can significantly shape political preferences (*Source: [Kristeligt Dagblad](https://www.kristeligt-dagblad.dk/danmark/betyder-indkomsten-noget-stemmeafgivningen)*). Especially if there is a large income variation in the population, as higher income inequality has been found to both mobilize low-income voters and demobilize high-income voters, creating complex dynamics within electorates (*Source: [Science Direct](https://www.sciencedirect.com/science/article/abs/pii/S0176268020301142)*). Through this analysis, we aim to discern whether the socioeconomic data in Copenhagen’s constituencies reflects such patterns — and whether emerging trends reveal untold stories about the city’s evolving political and economic landscape.



### Income Support Patterns

The income support distribution provide a lens through which we can better understand the socioeconomic composition of Copenhagen’s constituencies. By examining the distribution of various support types — such as unemployment benefits, state pensions, and social assistance — we can gain insight into the structural economic differences that demographic measures alone cannot show.

In the plot below, we present the average distribution of support types across three reference years (2009, 2014, 2019). Despite an initial expectation about very fluctuating ratios of support types over the years, the initial analysis revealed a relatively stable support composition within all districts (the trends over the years is available in the explainer notebook but is omitted here for conciseness). To highlight differences between districts more clearly, the data is averaged over the years, steering the focus toward inter-district variability rather than temporal changes. This stability is observed even as approximately 10,000 residents moved to the respective districts within the time period as we saw in the explorative analysis and household numbers increased for all districts. This suggests that new residents tend to reflect existing socioeconomic patterns rather than alter them (*Source: [RUC Diversitet eller Ensretning](https://ruc.dk/diversitet-eller-ensretning-er-kobenhavn-stadig-alle-om-10-ar)*).



<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
        <iframe src="assets/support_type_by_district.html" 
                title="Income support per district"
                style="display: block; margin: auto; border: none; width: 100%; max-width: 900px;" 
                height="600">
        </iframe>
        <figcaption style="margin-top: 0.75rem; font-style: italic;">
        <strong>Figure 6: Interactive layered barplot of the income support type distribution by district, averaged over three reference years (2009, 2014, 2019)</strong>. The plot highlights the share of residents receiving different types of public support, emphasizing differences between districts. Click the different support types to compare the districts further. The bars represent the share of the population (in percentages) within each district, including the "No Received Benefits" category which is included to normalize other support types and includes both children and those not receiving public support. This also indicates for all districts that the working force is the largest for all districts (approximately 60%).
        </figcaption>
</figure>

The interactive plot reveals distinct differences in income support distribution across Copenhagen’s districts for the averaged period for the elections. The most notable difference between districts is the relative high share of residents receiving state pension in *Tårnby*, *Slots* and *Falkoner*. This aligns with the previously observed age distribution in these areas, where a higher proportion of older residents is concentrated. *Tårnby* also stands out with a relatively higher share of residents receiving early retirement benefits, further emphasizing its older demographic profile. In contrast, other areas seem to have a much other composition of residents as there are averagely less than 10% on the different pension supports in *Nørrebro*, *Vesterbro* and *Bispebjerg*. For these districts, unemployment benefits represent the highest relative share of support, suggesting a potentially younger and more economically vulnerable population. This pattern reinforces the narrative that people tend to move into areas with similar socioeconomic profiles, thereby maintaining existing support compositions. A noteworthy exclusion in the dataset is the SU (student support), which is not included in the current visualizations as it is not present in the data. Given the concentration of student populations in districts such as *Nørrebro* and *Vesterbro*, this omission may partially obscure the socioeconomic dynamics in these areas. 

Social assistance is perhaps the most debated type of income support and often leveraged by politicians, as public opinions on the topic are highly polarized (*Source: [Belingske](https://www.berlingske.dk/politik/et-besoeg-hos-en-kontanthjaelpsmodtager-har-gjort-stort-indtryk-paa-las)*). From the plot, we can observe differences in the share of residents receiving social assistance across districts. *Bispebjerg* has the highest average share of residents receiving social assistance. However, further examination of support types over the years (see the explainer notebook) reveals that this is primarily driven by a spike in 2014, where approximately 8% of residents received social assistance. By 2019, this figure had reduced to around 5% - still the highest among the districts. All districts, however, experienced a noticeable increase in social assistance in 2014, likely due to the lingering effects of the financial crisis, which led to increased unemployment. Additionally, governmental initiatives, such as the introduction of arbejdsmarkedsydelse (labour market allowance), aimed to reduce the state’s financial burden by encouraging employment and limiting the years during which citizens were eligible for benefits. (*Sources: [Avisen.dk and Ritzau](https://www.avisen.dk/staten-faar-lavere-regning-for-flere-paa-kontanthjae_322727.aspx)* and *[Danmarks Statistik](https://www.dst.dk/da/Statistik/nyheder-analyser-publ/nyt/NytHtml?cid=19305)*)



### Wealth Gaps and Rising Incomes

After examining income support, we now turn to household income, a critical measure of socioeconomic status that can reveal significant disparities across Copenhagen’s districts. In the exploratory analysis, we observed a notable increase in household income across all constituencies over time, suggesting a general economic uplift for all of Copenhagen from 2009 to 2019. However, while income levels have risen, the distribution is not uniform across districts. The interactive plot below highlights these disparities, showing the proportion of households in various income brackets from 2009 to 2019. Overall, the share of households earning 500,000–749,999 DKK and over 750,000 DKK has increased across all districts, reflecting broader economic growth and a changing city.


<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
        <iframe src="assets/income_districts_stacked_bar.html" 
                title="Interactive Bar Chart of Income for All of Copenhagen"
                style="display: block; margin: auto; border: none; width: 110%; max-width: 920px;" 
                height="520">
        </iframe>
        <figcaption style="margin-top: 0.75rem; font-style: italic;">
        <strong>Figure 7: Interactive plot of household income distribution in Copenhagen over three reference years (2009, 2014, 2019)</strong>. The plot shows how income levels have shifted across districts, with a noticeable increase in higher income intervals over time. Click the toggle to view other districts and observe differences in income distribution and hover the distributions to see exact share of income interval.
        </figcaption>
</figure>


*Tårnby*, *Falkoner*, and *Indre By* stand out as the wealthiest districts, with 35% or more of households in each district earning above 750,000 DKK annually by 2019. In contrast, *Nørrebro* and *Bispebjerg* maintain a more diverse income distribution, with a broader spectrum of income brackets. This broader distribution aligns with the income support patterns observed earlier, where these districts had higher shares of unemployment benefits. 
A common trend across all districts is the overall rise in income levels. The number of households earning over 750,000 DKK annually has approximately doubled from 2009 to 2019 in every district. The most pronounced increase occurs in *Bispebjerg* and *Nørrebro*, where the share of households earning over 500,000 DKK rose from 18.7% to 35.9% and 20% to 40%, respectively. In *Tårnby*, the share of households earning above 500,000 DKK annually increased from 43% to 55%, further solidifying its profile as a higher-income district. However, this increase is less dramatic compared to the steeper rises in *Nørrebro* and *Bispebjerg*. 

Another notable trend is the sharp decline in households earning 100,000–149,999 DKK annually, a pattern consistent across all districts. This decline suggests a broader economic uplift, but it also raises questions about the affordability of living in Copenhagen for lower-income residents (*Source: [RUC Diversitet eller Ensretning](https://ruc.dk/diversitet-eller-ensretning-er-kobenhavn-stadig-alle-om-10-ar)*). As these lower-income brackets steadily diminish, the question arises: Will the city’s diversity persist if lower-income households are increasingly priced out? The observed trends suggest that Copenhagen is becoming increasingly affluent across all districts, with rising income levels and a growing share of high-income households. However, since the data does not track individuals over time, it is unclear whether these trends are driven by current residents earning more or by the arrival of wealthier newcomers.

While rising incomes may signal economic growth, it could also indicate growing economic polarization. This could particularly affect districts with more uniform income distributions, such as *Nørrebro* and *Bispebjerg*, where economic diversity may foster a another spectrum of political beliefs and values as we saw in the party vote shares and winning parties in the election analysis. 
As the city becomes more expensive to live in, some residents may also be priced out, leading to a wealthier overall population which needs to be noticed and planned for in the future (*Source: [Via Ritzau](https://via.ritzau.dk/pressemeddelelse/13726689/ny-undersogelse-derfor-flytter-tusindvis-hvert-ar-til-og-fra-kobenhavn?lang=da)*). 
However, this polarization trend may also contribute to higher voter turnout in some areas. For instance, Falkoner — with 56.6% of households earning more than 500,000 DKK annually — also has the highest voter turnout (Figure 1, DATA). This could be because income disparity within the district mobilizes those earning less to make their voices heard, as suggested by research on income inequality and voter mobilization (*Source: [Science Direct](https://www.sciencedirect.com/science/article/abs/pii/S0176268020301142)*). 
On the other hand, Tårnby presents a different pattern. Despite having a similar income distribution to Falkoner, with more than a third of households earning above 750,000 DKK annually, it does not exhibit the same high voter turnout. This could be linked to the political dynamics observed in the election analysis (Figure 3, ELECTIONS), where *Socialdemokratiet*, *Venstre*, and, up until 2019, *Dansk Folkeparti* have maintained a strong presence in *Tårnby*, contrasting with the more balanced political landscape in *Falkoner*. 

Overall, while the income distributions across districts are evolving, with rising affluence and a shrinking share of lower-income households, the relationship between income and political preferences remains complex. Similar income profiles do not necessarily translate into similar voting patterns, as demonstrated by the contrasting political landscapes in districts like *Falkoner* and *Tårnby*, where comparable income levels are associated with distinctly different electoral outcomes. 



### Now, please continue to the [next page](../studycase#finalinsights), FINAL INSIGHTS, where we wrap up.






