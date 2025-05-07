---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: custom_home
title: Data 
hero_title: Data Insights
hero_subtitle: Discover the details behind the datasets
---

## <a id="dataset"></a>Dataset

> 🎵 *What do we need? The data’s key*\
> 🎵 *Election votes in each constituency.*\
> 🎵 *Six elections, twenty years,*\
> 🎵 *To track the shifts, the rise, the fears.*

The foundation of this study is built on data from <a href="https://valgdatabase.dst.dk/data" target="_blank" style="color: #59B6E7; font-weight: bold;">Den Danske Valgdatabase</a>, powered by **Danmarks Statistik**. This comprehensive database contains election information from Denmark spanning back to 1979. The database includes data from a variety of election types including **National parliamentary elections** (*folketingsvalg*).

For this study, we focus on **national elections** within the **Copenhagen constituency (Københavns Storkreds)**, covering two decades and a total of six elections. This includes the elections held in the years:

<div style="text-align: center; margin: 16px 0;">
  <span style="font-weight: bold; font-size: 1.2em; display: inline-flex; gap: 20px;">
    <span>2001</span>
    <span>2005</span>
    <span>2007</span>
    <span>2011</span>
    <span>2015</span>
    <span>2019</span>
  </span>
</div>

The extracted election data includes:

- Total number of votes cast
- Number of votes per political party across constituencies

We specifically filtered the data to the following constituencies within **Københavns Storkreds**:

<div style="display: flex; flex-wrap: wrap; align-items: center;">
  <ul style="flex: 1;">
    <li>Indre Bykredsen</li>
    <li>Østerbrokredsen</li>
    <li>Vesterbrokredsen</li>
    <li>Nørrebrokredsen</li>
    <li>Bispebjergkredsen</li>
    <li>Brønshøjkredsen</li>
    <li>Valbykredsen</li>
    <li>Falkonerkredsen</li>
    <li>Slotskredsen</li>
    <li>Sundbyvesterkredsen</li>
    <li>Sundbyøsterkredsen</li>
    <li>Tårnbykredsen</li>
  </ul>

  <figure style="flex: 2; margin: 0;">
    <iframe src="assets/copenhagen_districts_map.html" 
            title="Interactive Map of Copenhagen Constituencies"
            style="width: 100%; height: 250px; border: none;">
    </iframe>
    <figcaption style="margin-top: 0.75rem; font-style: italic;">
      <strong>Map 1: Copenhagen Constituencies </strong>. Hover over a district to see its name
    </figcaption>
  </figure>

</div>

While some constituencies may appear geographically larger than others, this does not reflect population size. For instance, *Indre By* looks smaller on the map than *Tårnby*, but it has a significantly larger population. Additionally, it’s important to understand how seats (mandates) in the Danish Parliament (*Folketinget*) are allocated. Of the 179 seats (mandates), 175 are elected in Denmark, while 2 come from Greenland and 2 from the Faroe Islands. Parliamentary mandates are not tied to specific constituencies. Instead, 135 of the mandates are allocated directly in the 10 multi-member constituencies (like Københavns Storkreds) based on vote counts in each multi-member constituencies, hence all the constituencies of Copenhagen together contribute to the same pool of mandates from Copenhagen Storkreds. The last 40 mandates are distributed nationally to ensure proportionality between a party’s total national vote share and the number of seats they hold (*Source: [ft.dk](https://www.ft.dk/da/folkestyret/valg-og-afstemninger/hvordan-man-stemmer)*).


### Supplementary Data: Population Insights

In addition to voting data, we incorporated **sociodemographic data** extracted from **Danmarks Statistik**, allowing deeper insights into voting patterns in context of  population characteristics. Danmarks Statistik performs a **population census every five years**, with relevant years being:

<div style="text-align: center; margin: 16px 0;">
  <span style="font-weight: bold; font-size: 1.2em; display: inline-flex; gap: 20px;">
    <span>2004</span>
    <span>2009</span>
    <span>2014</span>
    <span>2019</span>
  </span>
</div>

As Danmarks Statistic match each election year to the closest available population statistics, the election years matches the following census years:

<p style="margin-top: 0.5rem; font-style: italic; text-align: center;">
  <strong>Table 1:</strong> Mapping of election years to the nearest available population census years, as provided by Danmarks Statistik. Each election year is matched with the most recent census data available at the time.
</p>
<div style="overflow-x: auto; margin: 16px 0;">
  <table style="width: 100%; margin: 0 auto; border-collapse: collapse; font-size: 1em; text-align: center; background-color: #f9f9f9; border: 1px solid #ddd;">
    <thead style="background-color: #59B6E7; color: white;">
      <tr>
        <th style="padding: 12px; border: 1px solid #ddd;">Election Year</th>
        <th style="padding: 12px; border: 1px solid #ddd;">Population Census Year</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd;">2005, 2007</td>
        <td style="padding: 10px; border: 1px solid #ddd;">2004</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd;">2011</td>
        <td style="padding: 10px; border: 1px solid #ddd;">2009</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd;">2015</td>
        <td style="padding: 10px; border: 1px solid #ddd;">2014</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd;">2019, 2022</td>
        <td style="padding: 10px; border: 1px solid #ddd;">2019</td>
      </tr>
    </tbody>
  </table>
</div>

The sociodemographic data covers a wide range of characteristics, which we group into two main categories:

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin: 30px 0;">
  
  <div style="flex: 1 1 250px; background: #f9f9f9; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
    <h3 style="color: #59B6E7;">Demographics</h3>
    <p style="font-size: 1em; color: #555;">
      Includes gender, age, origin, and education level.
    </p>
  </div>
  
  <div style="flex: 1 1 250px; background: #f9f9f9; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
    <h3 style="color: #59B6E7;">Socioeconomic</h3>
    <p style="font-size: 1em; color: #555;">
      Includes income, types of income support received, and living area size.
    </p>
  </div>
  
</div>

#### Size of the dataset

In total, the dataset consists of 43,404 entries across 40 variables, occupying 11.4 MB of space.

## <a id="basic-stat"></a>Basic Statistics

In the following sections some basic statistics are presented in order to gain knowledge and understanding of the data.

### Vote Turnout 
To begin, we examine the election data by looking at voter turnout over time — both for Copenhagen as a whole and for each individual constituency. Voter turnout is calculated as the number of votes cast divided by the number of eligible voters, both of which are provided in the dataset.

<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
  <iframe src="assets/vote_turnout_const.html" 
          style="display: block; margin: auto; border: none; width: 100%; max-width: 900px;" 
          height="475">
  </iframe>
  <figcaption style="margin-bottom: 0.10rem; font-style: italic;">
    <strong>Figure 1: Voter turnout across years by constituency.</strong> 
    This interactive chart allows you to explore voter turnout over time across different districts in Copenhagen. Click on district names in the legend to show or hide them. To zoom in on a specific period, click and drag over the area you'd like to examine in more detail.
  </figcaption>
</figure>

The figure above illustrates voter turnout in each constituency across election years over the past two decades. Notably, the *Bispebjerg* constituency consistently shows the lowest turnout in every election, while *Falkoner* consistently has the highest. These differences become particularly interesting when we later examine population data to identify patterns that may help explain variations in voting behavior across districts.

When comparing individual constituencies to the overall average turnout in Copenhagen, we observe that *Bispebjerg*, *Valby*, *Sundbyvester*, *Sundbyøster*, and *Brønshøj* consistently fall below the citywide average. This suggests that these areas tend to have lower levels of voter engagement compared to other parts of Copenhagen.

### Population Count 

Next, we examine the population count in Copenhagen over time. The table below shows the population in the Copenhagen constituency for the years 2004, 2009, 2014, and 2019. These numbers are based on census data from Danmarks Statistik, which is collected every five years. The population for each year is as follows:

<p style="margin-top: 0.5rem; font-style: italic; text-align: center;">
  <strong>Table 2:</strong> Population count in the Copenhagen constituency over time based on census data from Danmarks Statistik. 
</p>
  <table style="width: 100%; margin: 0 auto; border-collapse: collapse; font-size: 1em; text-align: center; background-color: #f9f9f9; border: 1px solid #ddd;">
    <thead style="background-color: #59B6E7; color: white;">
    <tr>
      <th style="padding: 12px; border: 1px solid #ddd;">Year</th>
      <th style="padding: 12px; border: 1px solid #ddd;">Population count</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 10px; border: 1px solid #ddd;">2004</td>
      <td style="padding: 10px; border: 1px solid #ddd;">646,994</td>
    </tr>
    <tr>
      <td style="padding: 10px; border: 1px solid #ddd;">2009</td>
      <td style="padding: 10px; border: 1px solid #ddd;">678,873</td>
    </tr>
    <tr>
      <td style="padding: 10px; border: 1px solid #ddd;">2014</td>
      <td style="padding: 10px; border: 1px solid #ddd;">739,977</td>
    </tr>
    <tr>
      <td style="padding: 10px; border: 1px solid #ddd;">2019</td>
      <td style="padding: 10px; border: 1px solid #ddd;">794,128</td>
    </tr>
  </tbody>
</table>




We observe a steady increase in Copenhagen's population over this period, with a total growth of 22.74% from 2004 to 2019. This population growth may have implications for voting behavior, as a larger and potentially more diverse population can lead to broader variation in political preferences. It is particularly interesting to explore where in the city this growth is occurring — and how it may relate to changing voting patterns across constituencies.

### Income per Household
Finally, we examine household income levels in Copenhagen over time. This provides insight not only into the socioeconomic status of the residents but may also indicate the types of people who are moving to the city and staying in the city (*Source: [AE Rådet, 2021](https://www.ae.dk/files/dokumenter/analyse/ae_velstillede-boernefamilier-indtager-koebenhavn_0.pdf)*).

<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
  <iframe src="assets/income_dist_over_time.html" 
          style="display: block; margin: auto; border: none; width: 100%; max-width: 900px;" 
          height="475">
  </iframe>
  <figcaption style="margin-bottom: 0.10rem; font-style: italic;">
    <strong>Figure 2: Household income distribution over time.</strong> 
    This interactive chart allows you to explore how household income has developed over time in Copenhagen. Click on income metric in the legend to show or hide them. To zoom in on a specific period, click and drag over the area you'd like to examine in more detail.
  </figcaption>
</figure>

It is striking to see how average household income in Copenhagen has risen significantly over the past decade. In 2009, only 12.5% of households had an annual income of 750,000 DKK or more. By 2019, that figure had more than doubled to 27.8%, making it the largest income group — with an 8.6 percentage point lead over the second-largest group (500,000–749,999 DKK). At the same time, the share of households earning less than 149,999 DKK dropped from 19.5% in 2009 to just 6.6% in 2019, reflecting a clear shift toward a more affluent urban population.

The broader socioeconomic shift is also evident in long-term changes among families. In the 1990s, one in three children in Copenhagen came from working-class households. Today, that number has been cut in half, while the proportion of children from upper-class and upper-middle-class families has tripled. As one report puts it: *“Copenhagen is becoming less of a city that all families can afford to live in — and more of a city for the well-off.”* (*Source: [AE Rådet, 2021](https://www.ae.dk/files/dokumenter/analyse/ae_velstillede-boernefamilier-indtager-koebenhavn_0.pdf)*)




### Now, please continue to the [next page](../elections#elections), ELECTIONS, where we dive further into the elections data.