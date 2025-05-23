---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: custom_home
title: Sociodemographics 
hero_title: Sociodemographics
hero_subtitle: Exploring the Demographics and Socioeconomic data of the People in Copenhagen
---

## <a id="Sociodemographics"></a>Beyond the Ballot: The People Behind the Votes

> 🎵 *Did demographics play a role?*  
> 🎵 *Did new arrivals change the poll?*  

Having explored how election results have evolved across the last six national elections, we now turn our attention to the people behind the votes. Shifts in political outcomes may reflect changes in party landscapes — with new parties emerging and others declining — but they may also reflect changes in the population itself.

In this section, we take a closer look at Copenhagen’s demographics to better understand these underlying shifts. The city of Copenhagen has seen continuous population and wealth growth over the last 20 years, driven by both natural increase and migration (see [DATA](../data#dataset)). This growth provides crucial context for understanding electoral changes: more people means more voters — and possibly a shifting voter base.  
Where does the population increase stem from? Who lives in the different neighborhoods of Copenhagen? How has that changed over time? And how might these trends relate to what we observe politically?

We explore the age and educational background of residents in different neighborhoods, and then dive into key socioeconomic factors like income and support types.

<br>

### From Boomers to Zoomers: Who Lives Where?

First, we zoom in on age. What is the age distribution like in the different neighorhoods of Copenhagen? And has this changed over the two decades?  
To find out, take a look at the Figure below. 


<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
        <iframe src="assets/age_stacked_line_plot.html" 
                title="Interactive Bar Chart of Age Distribution Trends for Constituencies"
                style="display: block; margin: auto; border: none; width: 110%; max-width: 920px;" 
                height="550">
        </iframe>
        <figcaption style="margin-top: 0.75rem; font-style: italic;">
        <strong>Figure 4: Population distribution by age groups for each districts from 2004 to 2019.</strong> Each color band shows an age group’s share of the total population. Use the dropdown to change district, the legend to filter age groups, and click-drag to zoom. Double-click to reset axes.
        </figcaption>
</figure>

From the figure, one can investigate the age distribution in Copenhagens districts over time. It is evident, that most districts are dominated by the young adults of age 20–39 years olds. This tendency is the clearest in *Nørrebro* and *Vesterbro*, where nearly 70% of the population is under the age of 40. An exception is *Tårnby*, where we see the opoosite - that the 20-29 year olds is the smallest group, and older age groups are more prominent.

Some areas, like *Bispebjerg*, are getting younger over time. Others, like *Vesterbro*, are seeing a shift toward older age groups. But in general, most districts stay surprisingly stable - perhaps this suggest that people move to places that match their demographics?

These age patterns may help explain voting differences. Younger areas tend to vote more green (*Source: [DR 2022](https://www.dr.dk/nyheder/politik/folketingsvalg/de-unge-har-talt-intet-valgtema-slaar-klimaet)*) and less traditionally (*Source: [Altinget 2019](https://www.altinget.dk/artikel/farvel-til-magtpartierne-saadan-stemte-de-unge-til-valget)*). This lines up with what we see in places like *Nørrebro* and *Vesterbro*, where green, untraditional parties like *Enhedslisten* and *Alternativet* are very popular, and the people, generally younger.



<br>

### Districts and Degrees: A City of Academics?

Copenhagen’s population has changed notably over the past two decades in terms of a rising number of highly educated citizens. This becomes evident, when investigating the visual below. However, there are also big district wide differences - can you spot them?


<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
        <iframe src="assets/education_stacked_line_plot.html" 
                title="Interactive Bar Chart of Education Distribution Trends for Constituencies"
                style="display: block; margin: auto; border: none; width: 110%; max-width: 920px;" 
                height="550">
        </iframe>
        <figcaption style="margin-top: 0.75rem; font-style: italic;">
        <strong>Figure 5: Population distribution of adults on highest achieved education level by district from 2004 to 2019.</strong> Each color band shows an education level's share of the total population. Use the dropdown to change district, the legend to filter education level groups, and click-drag to zoom. Double-click to reset axes.
        </figcaption>
</figure>


This plot looks quite different from the age one — here, we see clear changes over time in every district.
In central areas like *Indre By*, *Østerbro*, and *Nørrebro*, Master’s degrees are now the most common education level, and over half the population holds a university degree. Outer districts like *Brønshøj*, *Valby*, and *Sundbyøster* show a more mixed distribution, but still follow the same overall trend: more higher education, less vocational and primary education.

Then there’s *Tårnby*, which stands out. Its shift is much less pronounced — and fewer than 30% have higher education. Most of the population still hold vocational or primary school degrees, setting it apart from the rest of the city.

Then the question just remains - do social background affect how we vote? According to *[Berlingske](https://cvap.polsci.ku.dk/forskning/valgkamp/presse/Social_baggrund_afg_r_igen_partivalg_-_CVAP_i_Berlingske.pdf)*, it does. Lower education level tends to more often result in right wing votes *["De Kortuddannede trækker mod blå blok"](https://www.mm.dk/artikel/de-kortuddannede-traekker-mod-blaa-blok)*. Within the blocks, there are also differences. For example, *Radikale Venstre* is one of the most popular left-wing parties among the highest educated. *SF* and *Enhedslisten*'s voter base is stronger among the higher educated, whereas *Socialdemokratiet* is stronger among the lower education levels *(Source: [Finans.dk](https://finans.dk/politik/ECE7776519/S%C3%A5dan-stemmer-danskerne-efter-indkomst-og-uddannelse/))*.

These trends can also be seen from the data. Districts with higher education levels (like *Indre By* and *Østerbro*) tend to vote more for *Radikale Venstre* and other progressive parties.  
*Tårnby*, with lower education levels, leans more right-wing. But not all trends align perfectly — Frederiksberg (*Slots* and *Falkoner*) has high education levels but still votes more to the right (compared to other districts of Copenhagen), showing how nuanced district-level dynamics can be.

<br>

## Socioeconomic Divides: From Paychecks to Pensions

>🎵 *Is Nørrebro all red and bold?*\
>🎵 *Does Frederiksberg stay rich and cold?*  

Now, let us examine income support and income across the districts. We aim to explore whether economic disparities align with voting preferences and whether we can say someting about stereotypes and neighborhoods.

The data regarding the socioeconomic factors do not include year 2004, due to a change in how the population cencus was carried out. Hence, the data span over three reference years (2009, 2014, 2019), capturing a decade marked by financial crises, migration waves, and evolving policy priorities. 
Existing narratives suggest that income can significantly shape political preferences (*Source: [Kristeligt Dagblad](https://www.kristeligt-dagblad.dk/danmark/betyder-indkomsten-noget-stemmeafgivningen)*). Especially if there is a large income variation in the population, as higher income inequality has been found to create complex dynamics within electorates (*Source: [Science Direct](https://www.sciencedirect.com/science/article/abs/pii/S0176268020301142)*).

<br>

### Income Support Patterns

The income support distribution provide a lens through which we can better understand the socioeconomic composition of Copenhagen’s constituencies. By examining the distribution of various support types — such as unemployment benefits, state pensions, and social assistance — we can gain insight into the structural economic differences that demographic measures alone cannot show.

In the plot below, we present the average distribution of support types across the three reference years. Despite an initial expectation about very fluctuating ratios of support types over the years, the initial analysis revealed a relatively stable support composition within all districts. Therefore, to highlight differences between districts more clearly, the data is averaged over the years, steering the focus toward inter-district variability rather than temporal changes. 
This stability is observed even as approximately 10,000 residents moved to the respective districts within the time period and household numbers increased for all districts. This suggests that new residents tend to reflect existing socioeconomic patterns rather than alter them (*Source: [RUC Diversitet eller Ensretning](https://ruc.dk/diversitet-eller-ensretning-er-kobenhavn-stadig-alle-om-10-ar)*).

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

The interactive plot reveals distinct differences in income support distribution across Copenhagen’s districts for the averaged period for the elections. The most notable difference between districts is the relative high share of residents receiving state pension in *Tårnby*, *Slots* and *Falkoner*. This aligns with the previously observed age distribution in these areas, where a higher proportion of older residents is concentrated. *Tårnby* also stands out with a relatively higher share of residents receiving early retirement benefits, further emphasizing its older demographic profile. 
In *Nørrebro*, *Vesterbro*, and *Bispebjerg*, unemployment benefits constitute the largest share of support, potentially reflecting a younger, more vulnerable population with limited financial stability.
This pattern reinforces the narrative that people tend to move into areas with similar socioeconomic profiles, thereby maintaining existing support compositions. A noteworthy exclusion in the dataset is the SU (student support), which is not included in the current visualizations as it is not present in the data. Given the concentration of student populations in districts such as *Nørrebro* and *Vesterbro*, this omission may partially obscure the socioeconomic dynamics in these areas. (*Source: [KBH Bolig](https://www.kbh-bolig.dk/hvordan-prioriterer-studerende-deres-boligoensker-i-kbh/)*)

Social assistance is perhaps the most debated type of income support and often leveraged by politicians, as public opinions on the topic are highly polarized (*Source: [Berlingske](https://www.berlingske.dk/politik/et-besoeg-hos-en-kontanthjaelpsmodtager-har-gjort-stort-indtryk-paa-las)*). From the plot, we can observe differences in the share of residents receiving social assistance across districts. *Bispebjerg* has the highest average share of residents receiving social assistance. However, further examination of support types over the years reveals that this is primarily driven by a spike in 2014, where approximately 7% of residents received social assistance. By 2019, this figure had reduced to around 4% - still the highest among the districts. All districts, however, experienced a noticeable increase in social assistance in 2014, likely due to the lingering effects of the financial crisis, which led to increased unemployment. Additionally, governmental initiatives, such as the introduction of arbejdsmarkedsydelse (labour market allowance), aimed to reduce the state’s financial burden by encouraging employment and limiting the years during which citizens were eligible for benefits. (*Sources: [Avisen.dk and Ritzau](https://www.avisen.dk/staten-faar-lavere-regning-for-flere-paa-kontanthjae_322727.aspx)* and *[Danmarks Statistik](https://www.dst.dk/da/Statistik/nyheder-analyser-publ/nyt/NytHtml?cid=19305)*). Despite *Bispebjerg* having a relatively high share of residents receiving social assistance, they still represent a small portion in the district. Nevertheless, the district consistently supports left-leaning parties like *Enhedslisten*, aligning with their advocacy for increased social support (*Source: [Rød+Grøn](https://rg.enhedslisten.dk/kontanthjaelpen-ville-vaere-30-hoejere-hvis-den-fulgte-den-lave-loenudvikling/)*).

<br>

### Wealth Gaps and Rising Incomes

Now, we shift focus to household income, a key indicator of socioeconomic status that reveals disparities across Copenhagen’s districts. From 2009 to 2019, household income rose citywide, but not to the same extent in all districts. The interactive plot below shows how income distribution has shifted, with a growing share of households earning 500,000–749,999 DKK and over 750,000 DKK, reflecting broader economic changes.

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
For all districts we see an overall rise in income levels and a doubling in households earning over 750,000 DKK annually from 2009 to 2019. The most pronounced increase occurs in *Bispebjerg* and *Nørrebro*, where the share of households earning over 500,000 DKK rose from 18.7% to 35.9% and 20% to 40%, respectively. In *Tårnby*, the share of households earning above 500,000 DKK annually increased from 43% to 55%, further solidifying its profile as a higher-income district. However, this increase is less dramatic compared to the steeper rises in *Nørrebro* and *Bispebjerg*. 

Another notable trend is the sharp decline in households earning 100,000–149,999 DKK annually, a pattern consistent across all districts. This decline suggests a broader economic uplift, but it also raises questions about the affordability of living in Copenhagen for lower-income residents (*Source: [RUC Diversitet eller Ensretning](https://ruc.dk/diversitet-eller-ensretning-er-kobenhavn-stadig-alle-om-10-ar)*). As these lower-income brackets steadily diminish, the question arises: Will the city’s diversity persist if lower-income households are increasingly priced out? The observed trends suggest that Copenhagen is becoming increasingly affluent across all districts, with rising income levels and a growing share of high-income households. However, since the data does not track individuals over time, it is unclear whether these trends are driven by current residents earning more or by the arrival of wealthier newcomers. (*Source: [AE Rådet](https://www.ae.dk/files/dokumenter/analyse/ae_velstillede-boernefamilier-indtager-koebenhavn_0.pdf)*)

Rising incomes may indicate economic growth but also signal economic polarization, particularly in districts like *Nørrebro* and *Bispebjerg*, where income diversity may influence political dynamics. As living costs rise, some residents may be priced out, shifting the population toward higher-income groups — a trend that requires future attention and planning
(*Source: [Via Ritzau](https://via.ritzau.dk/pressemeddelelse/13726689/ny-undersogelse-derfor-flytter-tusindvis-hvert-ar-til-og-fra-kobenhavn?lang=da)*). 
Additionally, this income polarization trend may also contribute to higher voter turnout in some areas. For instance, *Falkoner* — with 56.6% of households earning more than 500,000 DKK annually — also has the highest voter turnout (Figure 1, [DATA](../data#dataset)), and this could potentially lead to higher voter turnout (*Source: [Science Direct](https://www.sciencedirect.com/science/article/abs/pii/S0176268020301142)*). However, as *Tårnby* show the same income pattern as *Falkoner* with more than a third of households earning above 750,000 DKK annually, it does not exhibit the same high voter turnout. So high income might not directly influence voter turnout. Meanwhile, the income could still have an influence on the left- and right-wing dynamics of the votes, as *Tårnby* shows a different voting pattern from the rest of the districts voting primarily for *Socialdemokratiet*, *Venstre* and *Dansk Folkeparti*. Some of this might be explained by *Tårnby* actually earning slightly more than *Falkoner*, but there is a factor of how many people per household and whether these people are children or adults, which could also be expected to influence election dynamic.

Overall, while the income distributions across districts are evolving, with rising affluence and a shrinking share of lower-income households, the relationship between income and political preferences remains complex. Similar income profiles do not necessarily translate into similar voting patterns, as demonstrated by the contrasting political landscapes in districts like *Falkoner* and *Tårnby*, where comparable income levels are associated with distinctly different electoral outcomes. 

<br>

*Now, please continue to the [next page](../beyond#beyond), BEYOND, where we wrap up.*



<div style="display: flex; justify-content: center; gap: 40px; flex-wrap: wrap;">

  <div style="text-align: center; max-width: 40%;">
    <img src="assets/bolig_market.png" 
         alt="increasing rent" 
         style="width: 100%; height: 400;" />
    <p style="font-size: 0.85em; color: #555; margin-top: 0.5em;">
      Source: 
      <a href="https://politiken.dk/debat/debatindlaeg/art8467266/Vi-kan-ikke-bygge-os-ud-af-sk%C3%A6vhederne-p%C3%A5-boligmarkedet" 
         target="_blank" rel="noopener noreferrer">
        Politiken
      </a>
    </p>
  </div>

  <div style="text-align: center; max-width: 45%;">
    <img src="assets/polstret_til_fremtiden.png" 
         alt="til krisetider" 
         style="width: 100%; height: 300;" />
    <p style="font-size: 0.85em; color: #555; margin-top: 0.5em;">
      Source: 
      <a href="https://www.weekendavisen.dk/2018-34/samfund/krisen-ingen-glemmer?fbclid=IwZXh0bgNhZW0CMTEAAR7z41BsBj1CKBxtsA4OegXZgitt6HVMBhR20cNEWf2yigG-yOF1g5TdljZBkw_aem_ed8BRE05CmO8yPwTJStw-A" 
         target="_blank" rel="noopener noreferrer">
         Weekendavisen
      </a>
    </p>
  </div>

</div>

<br>






