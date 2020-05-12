# COVID-19 on Germany.
# Tror vi skal ændre covid til COVID 


This website has as goal to present the outbreak of COVID-19 in the country of Germany. The first case was registered on January the 28th, 2020 in the state of Bavaria and has since spread across all of Germany. The government has, as many other, added new laws to try and contain the virus, which the effectiveness of these will be looked at further down the site.
These are
* <b> 13-03-2020 </b> - 14 of the 16 states closes their schools and nurseries
* <b> 15-03-2020 </b> - Germany closes the borders
* <b> 22-03-2020 </b> - The governement and the federal states forbids gatherings of more than two people for two weeks and require a minimum distance of 1.5 meters between everyone

The graphs and visualisations presented in this report are based on data obtained from this [site](https://www.kaggle.com/headsortails/covid19-tracking-germany?fbclid=IwAR2ouNxb53Z-Mk4emTUpdZog9Uhm02krlCW0yC4woPArAbeF2lt5HyraS-4#covid_de.csv).
<br>
Many visuals include userfriendly navigation, which involves zoomability by marking an area and toggling values on and off in the legend. The most important icons are <img width="20" src="resetzoom.PNG">, which resets the zoom of the graph and <img width="40" src="choirce.PNG"> which respectively shows single value of the line hovered or all values for the date hovered. 


<h3 align="center">
Key Numbers
</h3>
<h2 align="center">
Total
</h2>
<p align="center">
  <img width="700" src="BAN1.png">
</p>
<h2 align="center">
Per one milion inhabitant
</h2>
<p align="center">
  <img width="700" src="BAN2.png">
</p>

<h3 align="center">
Development of total cases, deaths and recoveries
</h3>

Germany saw a very low number of cases from the first registered case on the 28th of January and till early March. Here the spread of Covid-19 started to take place and the numbers increased quite rapidly over the following weeks. It appears that from mid April to 2nd of May the growth in cases has decreased.

<iframe src="https://theisgregersen.github.io/Covid-19-DE/overview_cum.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>

<h3 align="center">
Cases are not evenly distributed between age groups and gender.
</h3>

Indsæt tekst

<iframe src="https://theisgregersen.github.io/Covid-19-DE/Pyramid.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>

<iframe src="https://theisgregersen.github.io/Covid-19-DE/deaths_bars.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>

<h3 align="center">
Case development per State
</h3>

The first case was as mentioned in the state of Bayern and it took almost a month for the other states to register more than a few cases. Bayern is together with Nordrhein-Westfallen and Baden-Wuerttenberg the three states with majority of registered cases. 

<figure>
  <img src="animation.gif" alt="my alt text"/>
  <figcaption align="center" style="font-size:11px"> Number of Cases per State over Time.</figcaption>
</figure>

As seen from the heatmap below, the highest number of registered cases are located in the south and western part of Germany. These all include the three mentioned states with the highest case-count, of which Bayern and Baden-Wuerttenberg are adjacent. The centrered spead could be explained by the measures taken by the government, of which the first was implemented on the 13th of March. Reduced mobility of citizens between states reduces the cross-state spread. This is also apparent from the race bar chart above, where we do not see any of the other states increasing as rapidly as Bayern, Nordrhein-Westfallen and Baden-Wuerttenberg.

<figure>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/heatmap_DE.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
  <figcaption align="center" style="font-size:12px"> Distrubution of cases, recoveries and deaths.</figcaption>
</figure>



<h3 align="center">
Registered cases over time - County-level
</h3>
Tjek om index=dato virker (Victor). Fiks hvordan interaktiv bar ser ud. <br>

Hvad pokker skal vi skrive her?

<figure>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/heatmap_time.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
  <figcaption align="center" style="font-size:12px"> Indsæt caption.</figcaption>
</figure>
  

<h3 align="center">
Measurements in attempt of reducing spread
</h3>
  <p>
R0 is a term used a lot when talking about epidemics and pandemics. It is essentially a measure of spreadability of the given virus. It refers to the number of people a single infected person will infect. E.g. a R0 value of 0.8 means that a 100 infected people can be expected to infect 80 new people. This also means that a R0 below 1 means that a virus will die out eventually, whereas a R0-value of 2 means the number of infected people will double for every infection-period. <br>
  <br>
As many other nations the german government tried to prevent Covid-19 spreading out of control by enforcing some regulations. In the visual below the five most important regulations are noted by date together with the data of daily occurences of Covid-19; both new cases, deaths and recoveries. Here we around mid March see a an exponential increase in new cases for each day, which refers to an R0 value of above 1. Around end March early April the number of new cases started declining and could be seen as an outcome of the initiatives taken by the government in reducing the R0. On the 15th of April the government declared a small success in stopping the spread and immediately it can be seen there is a small increase in daily cases. This however, is not to be seen as a direct consequence of the announcement, as it usually takes more than a few days from catching the virus to showing symptons. The same pattern can be seen on the days following the 20th of April where shops again were allowed to open up. </p>

<iframe src="https://theisgregersen.github.io/Covid-19-DE/Overview_byday.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>




<h3 align="center">
See if your country is fucked (R0 plots)
</h3>
<figure>

According to <a href="https://www.imperial.ac.uk/news/196573/covid-19-one-five-over-80s-need-hospitalisation">imperial</a> 

the deathrate is 0.66 % and the hospitalisation rate is 11.8 %. This is used in the visual below to estimate the number of hospitalised and the number of deaths. Using this <a href="https://en.wikipedia.org/wiki/List_of_countries_by_hospital_beds">source</a> it has been determined that the number of available beds at hospitals for Covid-19 is 139,474.

<details>
<summary>Dropdown menu - R0-værdi 1</summary>
<br>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/test1234.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
</details>

<details>
<summary>Dropdown menu - R0-værdi 2?</summary>
<br>

<figure>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/test1234.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
 
   <figcaption align="center" style="font-size:10px"> Test of Figure Caption.</figcaption>
</figure>
  
</details>


<details>
<summary>Dropdown menu - R0-værdi 3?</summary>
<br>

<figure>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/test1234.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
 
   <figcaption align="center" style="font-size:10px"> Test of Figure Caption.</figcaption>
</figure>
  
</details>


