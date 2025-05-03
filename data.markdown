---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: custom_home
title: Data 
hero_title: Data Insights
hero_subtitle: Discover the details behind the datasets
---

## <a id="dataset"></a>Dataset

The foundation of this study is built on data from <a href="https://valgdatabase.dst.dk/data" target="_blank" style="color: #59B6E7; font-weight: bold;">Den Danske Valgdatabase</a>, powered by **Danmarks Statistik**. This comprehensive database contains election information from Denmark spanning back to 1979. The database includes data from a variety of election types:

- **National parliamentary elections** (*folketingsvalg*)
- **European Parliament elections** (*europaparlamentsvalg*)
- **Referendums** (*folkeafstemninger*)
- **Municipal and regional elections** (*kommunalvalg* and *regionsrådsvalg*)
- **Parliamentary elections in Greenland and the Faroe Islands**

For this study, we focus on **national elections** within the **Copenhagen constituency (Københavns Storkreds)**, covering two decades and a total of six elections. This includes the elections held in the years:

<div style="text-align: center; margin: 16px 0;">
  <span style="color: #59B6E7; font-weight: bold; font-size: 1.2em; display: inline-flex; gap: 20px;">
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

<iframe src="assets/copenhagen_districts_map.html" 
        title="Interactive Map of Copenhagen Constituencies"
        style="width: 75%; height: 250px; border: none;">
</iframe>

</div>

In addition to election data, **population data** has also been extracted.  
This supplementary data allows for a deeper analysis of voting trends by investigating voting patterns in the context of population characteristics.  
Danmarks Statistik conducts a new population inventory every five years, with the most recent inventory completed in 2024. Previous inventories were conducted in 2019, 2014, 2009, and 2004, and these are aligned with the elections we are analyzing.

The election data is matched to the closest population inventory available at the time. This means:

- The 2005 and 2007 elections reference the 2004 inventory
- The 2011 election references the 2009 inventory
- The 2015 election references the 2014 inventory
- The 2019 and 2022 elections reference the 2019 inventory

As a result, the six elections in our study are connected to four different population inventories, which serve as the population reference points for our analysis.


### Supplementary Data: Population Insights

In addition to voting data, we incorporated **population data** extracted from **Danmarks Statistik**, allowing deeper insights into voting behaviors in relation to demographic shifts.

Danmarks Statistik performs a **population census every five years**, with relevant years being:

- **2004, 2009, 2014, 2019, and 2024**

For the analysis, each election year is matched to the closest available population statistics:

<div style="overflow-x: auto; margin: 14px 0;">
  <table style="width: 80%; margin: 0 auto; border-collapse: collapse; font-size: 1em; text-align: center; background-color: #f9f9f9; border: 1px solid #ddd;">
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

The population data covers a wide range of characteristics, which we group into three main categories:


<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin: 30px 0;">
  
  <div style="flex: 1 1 250px; background: #f9f9f9; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
    <h3 style="color: #59B6E7;">Demographics</h3>
    <p style="font-size: 1em; color: #555;">
      Covers gender, age, origin, and citizenship.
    </p>
  </div>
  
  <div style="flex: 1 1 250px; background: #f9f9f9; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
    <h3 style="color: #59B6E7;">Socioeconomic Factors</h3>
    <p style="font-size: 1em; color: #555;">
      Includes education level, employment status, income, types of support received, and employment sectors.
    </p>
  </div>
  
  <div style="flex: 1 1 250px; background: #f9f9f9; padding: 20px; border: 1px solid #ddd; border-radius: 10px; text-align: center;">
    <h3 style="color: #59B6E7;">Housing</h3>
    <p style="font-size: 1em; color: #555;">
      Encompasses type of housing, ownership status, and household size.
    </p>
  </div>

</div>

#### Size of the dataset

In total, the dataset consists of 45,984 entries across 46 variables, occupying 13.5 MB of space.

## <a id="basic-stat"></a>Basic Statistics