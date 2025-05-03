---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: custom_home
title: Election Exploration 
hero_title: Election Trends Over Time
hero_subtitle: How Election Results Have Changed Across Copenhagen’s Districts 
---

## <a id="elections"></a>Introduction

The dive into elections data.


## <a id="elections"></a> How Copenhagen Votes: Mapping the Left and Right Over Time

> 🎵 *In Copenhagen’s twelve domains*\
> 🎵 *Did left-wing rise? Did right-wing wane?*


To understand how Copenhagen votes, we first need to ask a big question: What kind of political city is it? Is the Danish capital a stronghold of the left, a quiet supporter of the right, or a patchwork of political preferences that vary by neighborhood?

To find out, we take a closer look at the distribution of votes for the left-wing and right-wing blocs across constituencies in Copenhagen over the last six elections.

Before we can analyze voting patterns, we need to draw the political boundaries. The table below shows how we’ve grouped Danish parties into left- and right-wing categories.

<p style="margin-bottom: 0.5rem; text-align: center;"><strong>Table 1:</strong> Classification of Danish political parties into left-wing and right-wing.</p>
<table style="width:100%; border-collapse: collapse; margin-bottom: 2rem; margin-left: auto; margin-right: auto;">
  <thead>
    <tr>
      <th scope="col" style="border: 1px solid #ccc; padding: 8px; background-color: #f0f0f0;">Left-Wing Parties</th>
      <th scope="col" style="border: 1px solid #ccc; padding: 8px; background-color: #f0f0f0;">Right-Wing Parties</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border: 1px solid #ccc; padding: 8px;">A. Socialdemokratiet</td>
      <td style="border: 1px solid #ccc; padding: 8px;">V. Venstre, Danmarks Liberale Parti</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 8px;">F. SF – Socialistisk Folkeparti</td>
      <td style="border: 1px solid #ccc; padding: 8px;">C. Det Konservative Folkeparti</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 8px;">Ø. Enhedslisten – De Rød-Grønne</td>
      <td style="border: 1px solid #ccc; padding: 8px;">O. Dansk Folkeparti</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 8px;">B. Det Radikale Venstre</td>
      <td style="border: 1px solid #ccc; padding: 8px;">I. Liberal Alliance</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 8px;">M.Minoritetspartiet</td>
      <td style="border: 1px solid #ccc; padding: 8px;">K. Kristendemokraterne</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 8px;">Å. Alternativet</td>
      <td style="border: 1px solid #ccc; padding: 8px;">P. Stram Kurs</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 8px;">Q. Frie Grønne, Danmarks Nye Venstrefløjsparti</td>
      <td style="border: 1px solid #ccc; padding: 8px;">D.Centrum-Demokraterne</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 8px;"></td>
      <td style="border: 1px solid #ccc; padding: 8px;">E. Klaus Riskær Pedersen</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 8px;"></td>
      <td style="border: 1px solid #ccc; padding: 8px;">D. Nye Borgerlige</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 8px;"></td>
      <td style="border: 1px solid #ccc; padding: 8px;">Æ. Danmarksdemokraterne – Inger Støjberg</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 8px;"></td>
      <td style="border: 1px solid #ccc; padding: 8px;">M. Moderaterne</td>
    </tr>
  </tbody>
</table>


Most Danish parties have clear ideological leanings and are easy to group, while some define themselves as centrist and are more difficult to place. One example is Centrum Demokraterne (CD), a centrist party that broke away from Socialdemokratiet in 1973. While they collaborated with both political blocs during their time in Parliament, we’ve chosen to place them in the right-wing category. This decision reflects their ideological origins and the general rightward tilt of their policies. (*Source: [danmarkshistorien.dk](https://danmarkshistorien.lex.dk/Centrum-Demokraterne_1973-2008)*) Another tricky case is the Moderaterne (M), a relatively new party founded in 2021 by former Prime Minister Lars Løkke Rasmussen. Although their first time in government (in 2022) involved a centrist coalition, we’ve chosen to classify them as right-leaning, based on their political stance and liberal-centrist identity, which places them closer to the center-right in Denmark’s political spectrum. (*Source: [moderaterne.dk](https://moderaterne.dk/moderaterne-mener/)*)

With these classifications in place, we can now explore how each of Copenhagen’s neighborhoods aligns politically — and whether the city speaks with one voice or many. To do so, we visualize the left-wing vote shares across the city’s twelve constituencies in the map below. 

<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
  <iframe src="assets/map_wing_share.html" 
          title="Interactive Map of Copenhagen Constituencies"
          style="display: block; margin: auto; border: none; width: 100%; max-width: 900px;" 
          height="600">
  </iframe>
  <figcaption style="margin-top: 0.75rem; font-style: italic;">
    <strong>Map 2:</strong> Left-wing vote shares across Copenhagen constituencies from 2005 to 2022. The map shows the percentage of votes received by left-wing parties in each constituency, with colors ranging from blue (indicating stronger right-wing support) to red (indicating stronger left-wing support). The redder the district, the stronger its tilt to the left; the bluer, the more it leaned right. The map is interactive — hover over a constituency to see its exact left-wing vote share, and use the radio button group to switch between election years and observe how political preferences have changed over time.
  </figcaption>
</figure>

Starting in 2005, Copenhagen’s political identity was already leaning left - but still relatively moderate. There were, however, some noticeable exceptions. The *Tårnby* constituency stood out with only 45% of votes going to left-wing parties, placing it in right-wing territory. Meanwhile, districts like *Slots* and *Falkoner* hovered near the center with 53% and 54% left-wing support, respectively. On the other end of the spectrum, *Nørrebro* and *Vesterbro* stood as strongholds of the left, each boasting 72% of the vote for left-wing parties.

By 2007, not much had changed. The city’s political map held steady, and the national government remained right-wing as in 2005. But things started taking a turn in 2011.

In the 2011 election, left-wing parties won nationally, bringing Denmark its first female Prime Minister, Helle Thorning-Schmidt. (*Source: [danmarkshistorien.dk/Folketingsvalget2011](https://danmarkshistorien.lex.dk/Folketingsvalget_2011)*) This political shift was echoed in Copenhagen’s core. *Nørrebro* saw its left-wing support rise to 79%, with *Vesterbro* close behind at 74%. *Bispebjerg* increased to 70%, up from 65% in 2007. Even *Falkoner* and *Slots* moved leftward to 59% and 54%. Yet *Tårnby* remained the lone holdout, still tilting right with just 47% support for the left.

The left-wing trend continued in 2015, though nationally, the tide turned again, with a right-wing Parliament. Still, Copenhagen kept drifting left. *Nørrebro* hit 81% in left-wing support — its highest yet — while *Vesterbro* remained steady at 74%. 

In 2019, the city completed its leftward journey. *Tårnby*, long the only right-leaning district in the capital, shifted to the left — making every Copenhagen constituency part of the left-wing bloc. This shift can be largely attributed to a new dominant topic in the election: *climate change*, which made left-wing parties more appealing to voters. (*Source: [danmarkshistorien.dk/Folketingsvalget2019](https://danmarkshistorien.lex.dk/Folketingsvalget_2019)*) Right-wing parties struggled to respond to this shift. In fact, the former leader of *Dansk Folkeparti*, Pia Kjærsgaard, famously mocked the climate movement by calling the left-wing activists *klimatosser* — roughly translated to *climate nuts* in English. This caused massive criticism and outrage, and she later had to apologize for her statements. (*Source: [da.wikipedia.org/wiki/Klimatosse](https://da.wikipedia.org/wiki/Klimatosse)*) The term *klimatosse* became a symbol of the right-wing’s struggle to connect with the climate movement. 

<div style="text-align: center;">
  <img src="assets/climatenuts.png" 
       alt="Climate Nuts" 
       style="width: 75%; height: auto; display: block; margin: auto;" />
  <p style="font-size: 0.85em; color: #555; margin-top: 0.5em;">
    Source: <a href="https://www.facebook.com/profile.php?id=100064848514652" target="_blank" rel="noopener noreferrer">
      Klimatosser (Facebook)
    </a>
  </p>
</div>


Then came 2022 - a more nuanced election year. While all constituencies remained left-leaning, the deep red of 2019 began to fade slightly, especially in central neighborhoods. The reason? A push toward the political middle. The newly formed Moderaterne entered Parliament for the first time and joined a historic coalition government alongside Socialdemokratiet and Venstre. The idea of a broad, centrist SVM government captured attention - and it is shown on the map, with central districts like *Indre By* and *Østerbro* becoming more balaned between left and right.

From 2005 to 2022, Copenhagen has moved decisively to the left. While the urban core — *Nørrebro*, *Vesterbro*, and *Bispebjerg* — consistently shows strong left-wing dominance, other neighborhoods like *Tårnby*, *Falkoner*, and *Slots* have followed a more balanced path, often hovering between 45% and 63% support for the left. This raises an important question: what drives these differences? Is it the parties reshaping the political landscape and influencing people to shift their votes? Or is it the population itself — with different districts home to different kinds of people, whose backgrounds and lifestyles shape their political preferences? Or perhaps it’s a combination of both? In the next section, we explore how each party performs across Copenhagen’s districts — and later, in the [Demographics](/demographics) section, we turn our attention to the people themselves: who lives where, and how might that shape the political map?

## <a id="elections"></a>Winners, Losers, and Loyalists: Party Shifts Across Copenhagen

> 🎵 *With parties shifting left and right*\
> 🎵 *Do neighborhoods still match the hype?*\
> 🎵 *We map the changes, district-wide*\
> 🎵 *To see where loyalties reside*

We explored the share of left-wing and right-wing voters in Copenhagen over the years. Now, let’s take a closer look at individual parties and their performance across the city’s constituencies. To do so, we focus on the most popular parties, this of course changes over time and over constituencies and to have a fair comparison, we will select the top 5 parties in each election year across all constituencies. The set of parties in the top 5 is different for each election year per constituency will be classified as the most popular parties in Copenhagen. In total, that gave us 10 parties to focus on. The figure below shows a interactive barplot of the top 10 parties in Copenhagen over the years. In the dropdown menu, you can select the constituency you want to focus on. In the legend you can disselect some of the parties and you can also choose to zoom in on a specific time period. 

We’ve explored the share of left-wing and right-wing voters in Copenhagen over the years. Now, let’s take a closer look at individual parties and how they’ve performed across the city’s constituencies.

We focus on the most popular parties — though these naturally vary over time and across constituencies. To ensure fair comparison, for each election year we identify the top five parties based on vote share across all constituencies. Altogether, this gives us a total of ten key parties to analyze.

The figure below presents an interactive bar chart showing how these ten parties have performed in Copenhagen over time. 

<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
        <iframe src="assets/party_vote_share_const_dropdown.html" 
                title="Interactive Bar Chart of Party Vote Shares"
                style="display: block; margin: auto; border: none; width: 100%; max-width: 900px;" 
                height="475">
        </iframe>
        <figcaption style="margin-top: 0.75rem; font-style: italic;">
        <strong>Figure 3:</strong> Party vote shares by constituency from 2005 to 2022. This interactive chart allows you to explore how each party has performed over time across different districts in Copenhagen. Use the dropdown menu to switch between constituencies. You can also toggle parties on and off in the legend or zoom in on specific election years to examine trends more closely.
        </figcaption>
</figure>

Starting in *Indre By*, we see that *Radikale Venstre* (B) has often been one of the most popular parties — leading every other election year. *Socialdemokratiet* (A), in contrast, only emerged as the leading party once, in 2015. Since 2011, *Enhedslisten* (Ø) has steadily gained support here, eventually becoming the most popular party in 2022. Interestingly, *Venstre* (V) also performed strongly in *Indre By*, securing a top-two position in both 2005 and 2019. The 2022 election in this district was particularly fragmented, with several parties receiving similar vote shares — reflecting the broader rise of centrist influence during that year.

Moving to *Østerbro*, we observe a similar pattern to *Indre By*, but with *Socialdemokratiet* (A) being more popular. Unlike *Indre By*, where the 2022 race was closely contested, *Østerbro* had a clear winner: *Socialdemokratiet* emerged as the district’s most popular party.

In *Vesterbro*, the story changes. Since 2011, *Enhedslisten* (Ø) has dominated the district, with *Alternativet* (Å) and *Radikale Venstre* (B) also performing well. This trend continues in *Nørrebro*, where *Enhedslisten* is even stronger — achieving 28.7% of the vote in 2019. *Socialdemokratiet*, by contrast, has never won *Nørrebro*, while they win in many other districts in Copenhagen. 

In *Bispebjerg*, we see a more dynamic evolution. *Socialdemokratiet* was clearly dominant in 2005 and 2007, but from 2011 onward, *Enhedslisten* began to rise. Today, the district appears evenly split between the two parties, highlighting a political tug-of-war between traditional center-left and more progressive voters.

In the suburban districts — *Brønshøj*, *Valby*, *Sundbyvester*, and *Sundbyøster* — *Socialdemokratiet* (A) maintains a stronghold. However, another notable trend emerges: the rise (and fall) of *Dansk Folkeparti* (O). In 2015, the party received around 14% of the vote in these areas, riding a national wave of focus on asylum and immigration policy. Their anti-immigration stance resonated with many voters. But their popularity sharply declined in the following years. By 2022, they were on the brink of losing parliamentary representation altogether.

This sharp decline wasn’t only due to diminished public concern over immigration, but rather because other parties adopted more restrictive immigration policies themselves as *Socialdemokratiet* (A). Additionally, new far - right parties emerged — *Nye Borgerlige* in 2015 and *Stram Kurs* in 2017 — offering even harder-line alternatives. This fractured the right-wing vote and undercut *Dansk Folkeparti*'s position in the political landscape.

*Tårnby* is a clear example of this shift. In 2015, *Dansk Folkeparti* nearly topped the vote here with 27%, but by 2019, their support had dropped to just 11%. Much of that lost support appears to have shifted to *Venstre* (V), as well as to *Nye Borgerlige* (D), which received 2.9% of the vote, and *Stram Kurs* (P), which received 2.1% in *Tårnby*.(*Source: [danmarkshistorien.dk/Folketingsvalget2015](https://danmarkshistorien.lex.dk/Folketingsvalget_2015)*), (*Source: [danmarkshistorien.dk/Folketingsvalget2011](https://danmarkshistorien.lex.dk/Folketingsvalget_2019)*).  

Finally, looking at *Slots* and *Falkoner*, we see yet another unique pattern. *Det Konservative Folkeparti* (C) performs particularly well in these districts, alongside *Radikale Venstre* (B), *Venstre* (V), and *Socialdemokratiet* (A). Here, the “green wave” seen in more central areas is far less prominent. Instead, these constituencies reflect a more balanced political environment — where centrist and center-right parties remain highly competitive, contributing to the overall balanced political landscape in these constituencies.

In the map below, we provide a visual overview of the winning party in each constituency across the election years. 

<figure style="text-align: center; margin: 2rem auto; max-width: 900px;">
  <iframe src="assets/map_winning_party.html" 
          title="Interactive Map of Copenhagen Constituencies"
          style="display: block; margin: auto; border: none; width: 100%; max-width: 900px;" 
          height="600">
  </iframe>
  <figcaption style="margin-top: 0.75rem; font-style: italic;">
    <strong>Map 3:</strong> Winning party in each constituency from 2005 to 2022. This interactive map shows the winning party in each constituency for each election year. The map is interactive — hover over a constituency to see the winning party and the percentage of votes it received. Use the radio button group to switch between election years and observe how political control has shifted over time.
  </figcaption>
</figure>

A quick walk through the years give a clear picture of Copenhagen’s evolving political landscape. While *Socialdemokratiet* (A) has often been the largest party overall, its dominance has been increasingly challenged. In recent years, *Enhedslisten* (Ø) has taken over many of the central districts, signaling a progressive shift in the city’s political heart.

Some districts, like *Slots* and *Tårnby*, are more prone to right-wing parties, where parties like *Venstre* (V) have been the wining party in 2011. Meanwhile, central Copenhagen — including *Indre By* and *Østerbro* — seems to be more socially liberal occasionally leaned toward *Radikale Venstre* (B), reflecting a nuanced political identity in those neighborhoods.

The 2011 election, which brought a national left-wing government after two terms of right-wing rule, is particularly telling. In Copenhagen, the winning parties weren’t always *Socialdemokratiet* — instead, their coalition partners like *Radikale Venstre* and *Enhedslisten* claimed victories in key constituencies. At the same time, *Venstre* won in *Tårnby* and *Slots*. This reveals just how crucial support parties are for *Socialdemokratiet* in forming a majority in Copenhagen. 

It is interesting to see how *Socialdemokratiet* managed to maintain a strong share of the vote in 2022, despite several scandals during the COVID-19 pandemic as the Mink and deleted messages. Most notably, Prime Minister Mette Frederiksen was pressured to call an early election after the *Mink Commission* released its report, leading *Radikale Venstre* to push the government to dissolve Parliament. (*Source: [danmarkshistorien.dk/Folketingsvalget2022](https://danmarkshistorien.lex.dk/Folketingsvalget_2022)*)

This outcome suggests that the party has a solid base of loyal voters in Copenhagen — voters who remained supportive despite the controversies. In fact, *Socialdemokratiet* continued to win in many of its traditional strongholds, including suburban districts like *Brønshøj*, *Valby*, *Sundbyvester*, and *Sundbyøster*, as well as in *Tårnby*, *Falkoner*, and *Slots*.

The timing of the election may also have worked in the party’s favor. Europe was facing significant uncertainty due to the war in Ukraine and an escalating energy crisis. In this context, *Socialdemokratiet* positioned itself as a unifying force — a party that could lead through crisis — which may have resonated with voters. (*Source: [TV2 Nyheder](https://nyheder.tv2.dk/politik/2022-10-05-derfor-gaar-mette-frederiksen-til-valg-paa-en-regering-henover-midten)*)


<div style="display: flex; justify-content: center; gap: 40px; flex-wrap: wrap;">

  <div style="text-align: center; max-width: 45%;">
    <img src="assets/slette_mette.png" 
         alt="Climate Nuts" 
         style="width: 100%; height: 400;" />
    <p style="font-size: 0.85em; color: #555; margin-top: 0.5em;">
      Source: 
      <a href="https://politiken.dk/danmark/politik/folketingsvalg_2022/art8938209/Sådan-har-Politikens-tegnere-set-Mette-Frederiksens-tre-år-som-statsminister" 
         target="_blank" rel="noopener noreferrer">
        Poliken
      </a>
    </p>
  </div>

  <div style="text-align: center; max-width: 45%;">
    <img src="assets/midten.png" 
         alt="District Map" 
         style="width: 100%; height: 300;" />
    <p style="font-size: 0.85em; color: #555; margin-top: 0.5em;">
      Source: 
      <a href="hhttps://www.berlingske.dk/til-stregen/i-den-sorte-gryde" 
         target="_blank" rel="noopener noreferrer">
         Berlingske
      </a>
    </p>
  </div>

</div>


varm op til næste afsnit! skriv om hvilke partier der har loyal   e vælgere og hvilke partier der har skiftende vælgere.
