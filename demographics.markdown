---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: custom_home
title: Sociodemographics 
hero_title: Sociodemographics
hero_subtitle: Exploring the Demographics and Sociodemographic data to the People in Copenhagen
---

## <a id="Sociodemographics"></a>Sociodemographics


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







## Socioeconomic Status Across Constituencies

>🎵 *Is Nørrebro all red and bold?*\
>🎵 *Does Frederiksberg stay rich and cold?*  

### Income Support

To understand economic well-being and its variation across the city, we begin by examining the types of public support residents receive. The interactive plot below visualizes the distribution of various support types across districts, providing insights into how different areas rely on state pensions, unemployment benefits, and other social support mechanisms.




<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
        <iframe src="assets/support_type_by_district.html" 
                title="Income support per district"
                style="display: block; margin: auto; border: none; width: 100%; max-width: 900px;" 
                height="600">
        </iframe>
        <figcaption style="margin-top: 0.75rem; font-style: italic;">
        <strong>Figure 6:</strong> Interactive plot of the income support type distribution by district. The proportions of residents receiving retirement, unemployment, or employment support vary significantly across the districts. Click the different support types to compare the different districts and their share of residents on that receive the various support types. Please note that the remaining share of the population receive no income support from the Danish government.
        </figcaption>
</figure>

In Tårnby and Brønshøj, for instance, the prevalence of state pensions is remarkably higher, reflecting the older age demographics in these areas. In contrast, more urbanized districts like Nørrebro and Vesterbro show a higher dependency on unemployment benefits, aligning with a younger, more transient population that is potentially more susceptible to economic fluctuations. These patterns underscore the economic diversity across the city and suggest potential links between public support reliance and local political dynamics.


### Income Development

Income serves as a primary indicator of socioeconomic status. The plot below illustrates the income distribution across districts over time, allowing us to observe shifts in economic conditions and disparities in affluence.

<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
        <iframe src="assets/income_districts_stacked_bar.html" 
                title="Interactive Bar Chart of Income for All of Copenhagen"
                style="display: block; margin: auto; border: none; width: 110%; max-width: 920px;" 
                height="520">
        </iframe>
        <figcaption style="margin-top: 0.75rem; font-style: italic;">
        <strong>Figure 7:</strong> Interactive plot of the income per household in Copenhagen for the years 2009 to 2019. Click the toggle to explore another district. Income levels in Copenhagen have risen significantly in the last 15 years for all districts. This overall increase reflects economic growth and the rising cost of living in a capital city.
        </figcaption>
</figure>


From 2009 to 2019, affluent districts like Indre By and Østerbro have seen pronounced income growth, with a larger share of households moving into the highest income brackets. Meanwhile, areas like Tårnby and Brønshøj lag behind, maintaining a higher proportion of households in lower income brackets. These trends suggest a widening income gap across districts, potentially reinforcing existing socioeconomic divides and affecting local political alignments.


Looking at the districts individually, a more nuanced picture appears. Inner districts such as Indre By and Østerbro show the steepest income growth, while others like Tårnby and Brønshøj lag behind. This increasing disparity is important for understanding the evolving class-based dimensions of political alignment in the city.


Closely tied to the income is the size of the living areas of the residents. As we saw in the notebook (source our notebook) the average housing size show a tendency of steadily increasing by the years. The trend is most pronounced in districts where income has also risen. This suggests a close relationship between rising affluence and residential expansion — possibly reflecting shifts in household structure, lifestyle, and urban planning.





<!-- Copenhagen’s demographic and socioeconomic landscape has transformed considerably over the past two decades. With a growing, increasingly diverse, and more educated population — combined with rising income and housing expansion — the city’s electorate is also changing. These demographic dynamics offer important context for understanding the evolving political landscape we explored in the election section.

How does all this tie together with the election data and is it even possible to say something about the trends and shifts of the political parties and their votes in Copenhagen? Click on the next tab [Final Insights](../studycase#finalinsights) to know more! -->


### Now, please continue to the [next page](../studycase#finalinsights), FINAL INSIGHTS, where we wrap up.






