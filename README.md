# COVID-19 in Germany.
# test1

This website has as goal to present the outbreak of COVID-19 in the country of Germany. The first case was registered on January the 28th, 2020 in the state of Bavaria and has since spread across all of Germany. The government has, as many other, added new laws to try and contain the virus, which the effectiveness of these will be looked at further down the site.
The most important being the three following:
* <b> 13-03-2020 </b> - 14 of the 16 states closes their schools and nurseries.
* <b> 15-03-2020 </b> - Germany closes the borders.
* <b> 22-03-2020 </b> - The governement and the federal states forbids gatherings of more than two people for two weeks and require a minimum distance of 1.5 meters between everyone.

The graphs and visualisations presented in this report are based on data obtained from this [site](https://www.kaggle.com/headsortails/covid19-tracking-germany?fbclid=IwAR2ouNxb53Z-Mk4emTUpdZog9Uhm02krlCW0yC4woPArAbeF2lt5HyraS-4#covid_de.csv).
<br>
Many visuals include userfriendly navigation, which involves zoomability by marking an area and toggling values on and off in the legend. The most important icons are <img width="20" src="resetzoom.PNG">, which resets the zoom of the graph and <img width="40" src="choirce.PNG"> which respectively shows single value of the line hovered or all values for the date hovered. 


<h2 align="center">
  General Overview
</h2>
<h4 align="center">
Total Occurences
</h4>
<p align="center">
  <img width="700" src="BAN1.png">
</p>
<h4 align="center">
Per One Milion Inhabitant
</h4>
<p align="center">
  <img width="700" src="BAN2.png">
</p>

As seen from the heatmap below, the highest number of registered cases are located in the south and western part of Germany. The three states with the highest case-coun are Bayern, Baden-Wuerttenberg and Nordrhein-Westfallen. The centrered spead could be explained by the measures taken by the government, of which the first was implemented on the 13th of March. Reduced mobility of citizens between states reduces the cross-state spread. 

<figure>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/heatmap_DE.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
  <figcaption align="center" style="font-size:16px"> Distrubution of cases, recoveries and deaths.</figcaption>
</figure>

<h3 align="center">
COVID-19 has different impact depending on age and gender.
</h3>

Looking into how the different age groups and gender are affected by COVID 19 it is present that female have a higher number of cases than men. It can also be seen that people in the age between 35 and 59 are the most present in the statistic. This is not to be mistaken has the hardest hit age group, as this age group also has the biggest population in Germany (<a target="_blank" rel="noopener noreferrer" href="https://www.statista.com/statistics/454349/population-by-age-group-germany/">source</a>).

<figure>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/Pyramid.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
  <figcaption align="center" style="font-size:16px"> Cases and Recoveries by Gender and Age Group.</figcaption>
</figure>

From both the visual above and below, it is apparent that the probability of COVID-19 having a fatal outcome increases the elder the person being infected is. Due to the high difference in number of deaths between the age groups the y-axis has been log-scaled. To get the original values please hover the bars. <br>

<p align="center">
<b> OBS - Log Scaled Y-Axis </b>
</p>
<figure>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/deaths_bars.html" sandbox="allow-same-origin allow-scripts" width="100%"  height="300" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
  <figcaption align="center" style="font-size:16px"> Number of Deaths per Age Group - Log Scaled.</figcaption>
</figure>



<h2 align="center">
Development over Time
</h2>

Germany saw a very low number of cases from the first registered case on the 28th of January and till early March. Here the spread of Covid-19 started to take place and the numbers increased quite rapidly over the following weeks. It appears that from mid April to 2nd of May the growth in cases has decreased.

<iframe src="https://theisgregersen.github.io/Covid-19-DE/overview_cum.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>

The first case was as mentioned in the state of Bayern and it took almost a month for the other states to register more than a few cases. Bayern is together with Nordrhein-Westfallen and Baden-Wuerttenberg the three states with majority of registered cases. 

<figure>
  <img src="animation.gif" alt="my alt text" width="120%"/>
  <figcaption align="center" style="font-size:16px"> Number of Cases per State over Time.</figcaption>
</figure>

The heatmap below shows the daily occurences across all Germany. <a target="_blank" rel="noopener noreferrer" href="https://theisgregersen.github.io/Covid-19-DE/heatmap_time.html">Link to Original.</a>

<figure>
  <img src="Time_HeatMap.gif" alt="my alt text" width="100%"/>
  <figcaption align="center" style="font-size:16px"> Heatmap of Daily Registered Cases.</figcaption>
</figure>
  

<h3 align="center">
Measurements in attempt of reducing spread
</h3>
  <p>
R0 is the basic reproduction rate. A term used a lot when talking about epidemics and pandemics. It is essentially a measure of spreadability of the given virus. It refers to the number of people a single infected person will infect. E.g. a R0 value of 0.8 means that a 100 infected people can be expected to infect 80 new people. This also means that a R0 below 1 means that a virus will die out eventually, whereas a R0-value of 2 means the number of infected people will double for every infection-period. <br>
  <br>
As many other nations the german government tried to prevent Covid-19 spreading out of control by enforcing some regulations. In the visual below the five most important regulations are noted by date together with the data of daily occurences of Covid-19; both new cases, deaths and recoveries. Around mid March an exponential increase in newly registered cases by each day is seen, which refers to an R0 value of above 1. Around end March early April the number of new cases started declining and could be seen as an outcome of the initiatives taken by the government in reducing the R0. On the 15th of April the government declared a small success in stopping the spread and immediately it can be seen there is a small increase in daily cases. This however, is not to be seen as a direct consequence of the announcement, as it usually takes more than a few days from catching the virus to showing symptons. The same pattern can be seen on the days following the 20th of April where shops again were allowed to open up. </p>

<iframe src="https://theisgregersen.github.io/Covid-19-DE/Overview_byday.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>




<h3 align="center">
See if your country is fucked (R0 plots)
</h3>
<figure>

According to <a target="_blank" rel="noopener noreferrer" href="https://www.imperial.ac.uk/news/196573/covid-19-one-five-over-80s-need-hospitalisation">imperial</a>
the deathrate is 0.66 % and the hospitalisation rate is 11.8 %. This is used in the visual below to estimate the number of hospitalised and the number of deaths. Using this <a target="_blank" rel="noopener noreferrer" href="https://en.wikipedia.org/wiki/List_of_countries_by_hospital_beds">source</a> it has been determined that the number of available beds at hospitals for Covid-19 is 139,474. <br>
The following visualisations are based on the known epidemic-simulation formula, SEIR. This takes a number of inputs which have been determined to have the following values:

<ul>
  <li> <b> Infection Period </b> - 14 days (Number of days infected) </li>
  <li> <b> Incubation Period </b> - 14 days (Number of days in incubation if virus caught) </li>
  <li> <b> DeathRate </b> - 0.66 % (Probability of dying to the virus) </li>
  <li> <b> R0 </b> - The basic reproduction rate. </li>
</ul>

The visual show five lines which are:
<ul>
  <li> <b> Suspectible </b> - number of people who can still catch the virus </li>
  <li> <b> Infected </b> - Number of people infected by the virus </li>
  <li> <b> Recovered </b> - Number of people recovered from the virus </li>
  <li> <b> Deaths </b> - Number of people killed by the virus </li>
  <li> <b> Hospitalised </b> - 11.8 % of the infected </li>
</ul>

The initial values for the five above mentioned are set to be the registered values of May the 2nd 2020.<br>
<br>
The simulations are of course under the assumption that no progression within medical treatment or no new regulations are enforced. This also means that this should not be seen as representative of the future, but mostly as a visual understanding of R0 and how a reduction in this can have a big impact on the spread of the virus. As greatly visualised by <a target="_blank" rel="noopener noreferrer" href="https://2oqz471sa19h3vbwa53m33yj-wpengine.netdna-ssl.com/wp-content/uploads/2020/03/The-Math-Behind-Social-Distancing.jpg">Visual Capitalist</a> social distancing has a massive effect on the spread of a virus (R0), thus this can be used as an understanding of how social distancing and other measures taken by each individual can have a big impact on the impact of a virus. <br>
<br>
Below three different scenarios are presented. Try toggling off different lines. (<b>Click </b> each scenario to expand).

<details>
<summary> <b>Scenario 1</b> The first is the current state of Germany with an R0 value of 0.9 (<a target="_blank" rel="noopener noreferrer" href="https://edition.cnn.com/world/live-news/coronavirus-pandemic-04-24-20-intl/h_1b76ae623f01f30c03601354511236c9">source</a>)</summary>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/R0_09.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
     <figcaption align="center" style="font-size:16px"> COVID-19 spread with R0 value of 0.9.</figcaption>
</details>


<details>
<summary> <b>Scenario 2</b> Italy has been one of, if not, the hardest hit coutries in Europe. According to this (<a target="_blank" rel="noopener noreferrer" href="https://www.ecdc.europa.eu/sites/default/files/documents/covid-19-rapid-risk-assessment-coronavirus-disease-2019-eighth-update-8-april-2020.pdf">source</a>) the R0 rate when worst in Italy was between 2.76 and 3.25. The second example will be a simulation of how Germany will be affected by having an R0 value of 3.</summary>
<figure>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/R0_3.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
   <figcaption align="center" style="font-size:16px"> COVID-19 spread with R0 value of 3.</figcaption>
</figure>
</details>


<details>
<summary> <b>Scenario 3</b> The last is to demonstrate the maximum value of R0 where the number of available hospital beds will not be exceeded. This is calculated to be approximately 1.38. </summary>
<figure>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/R0_138.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
   <figcaption align="center" style="font-size:16px"> COVID-19 spread with R0 value of 1.38.</figcaption>
</figure>
</details>



