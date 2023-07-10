---
title: Lewis's record breaking year
summary: Challenging season, Covid-19 limiting spectators, Hamilton's seventh title.
tags:
- lewis-hamilton
- formula1
date: "2020-12-14T00:00:00Z"

image:
  caption: ""
  focal_point: Smart

url_code: "https://github.com/mpalaourg/F1_DataAnalysis/blob/main/2020-Season/Season%20Analysis.ipynb"
url_pdf: ""
url_slides: ""
url_video: ""
---

The 2020 Formula 1 season was significantly impacted by the global spread of the Covid-19 virus. The season, originally scheduled to begin in March, was postponed for several months until July. The first eight rounds of the Championship were held without spectators, and the remaining races were either run with limited capacity or behind closed doors due to the second wave of the Covid-19 pandemic.

# Race Calendar
---
The 2020 Formula 1 season witnessed several significant developments. The **Australian Grand Prix**, scheduled to be the season opener, was canceled just hours before the 1st FP session. Other notable cancellations included the **Vietnam Grand Prix at Hanoi Street Circuit** and the **Netherlands Grand Prix at Zandvoort**, which was set to return after a long hiatus of over 30 years.

Initially, the calendar featured eight European tracks, but as time progressed, more circuits were added. This included the inclusion of new tracks like **Mugello for the Tuscany Grand Prix** and **Algarve for the Portugal Grand Prix**. Additionally, iconic circuits such as **Nurburgring for the Eifel Grand Prix**, **Imola for the Emilia Romagna Grand Prix**, and **Istanbul Park for the Turkey Grand Prix** were brought back.

An interesting aspect of the season was the hosting of multiple Grands Prix on the same track. This included **Red Bull Ring** hosting the **Austria Grand Prix** and **Styria Grand Prix**, **Silverstone** hosting the **Great Britain Grand Prix** and **70th Anniversary Grand Prix**, and **Bahrain** hosting the **Bahrain Grand Prix** and **Sakhir Grand Prix**.

Overall, the 2020 season comprised 17 Grands Prix, each with their details given below:
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2020-Season/imgs/calendar.png" alt="2020_calendar" class="center">

# Drivers and Constructors
---
The grid consisted of 10 Teams and 23 Drivers, including 3 Reserve Drivers. In comparison to the 2019 season, there have been several notable alterations:

- In **Renault**, **Esteban Ocon** replaced **Nico Hülkenberg**.
- In **Williams**, **Nicholas Latifi** replaced **Robert Kubica**. Then, **Kubica** became the reserve driver for **Alfa Romeo**.
- **Toro Rosso** was re-branded as **AlphaTauri** with white and navy blue livery, and still using Honda Power Unit.
- **Mercedes AMG Petronas** adopted a black livery in 2020, deviating from their well-known silver one.

Throughout the season, **Nico Hülkenberg** was called by **Racing Point** three times during the season as a replacement for drivers who contracted Covid-19. Finally, **Jack Aitken** and **Pietro Fittipaldi** got their chances for their debuts in Formula 1.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2020-Season/imgs/drivers.png" alt="2020_drivers" class="center">

# 2020 Season analysis
---
Among the 17 tracks, **Lewis Hamilton** stands out with the highest number of wins, including an impressive 5-win streak from the **Eifel GP** to the **Bahrain GP**. His teammate **Valtteri Bottas** has also crossed the finish line in first place twice, contributing to **Mercedes AMG Petronas**' total of 13 wins. **Red Bull Racing's Max Verstappen** achieved 2 victories, while **Pierre Gasly** secured a memorable win for **AlphaTauri** in the **Monza GP** and **Sergio Perez** clinched a win for **Racing Point** in the **Sakhir GP**.

Furthermore, pole-sitters successfully defended their positions in 10 different tracks, with **Hamilton** leading the way with 8 successful defenses. Additionally, in 5 tracks, the race winners also set the fastest lap, earning the maximum available points. Notably, **Pierre Gasly**'s victory came from the 10th position on the starting grid, following a red flag and a penalty that reshuffled the field. Finally, the **Bahrain GP** saw an extraordinary moment when [**Romain Grosjean**'s horrific accident](https://www.youtube.com/watch?v=7YMjw2sjXqU) occurred on lap 1, leading to a red flag that halted the race for more than 1 hour before eventually resuming and reaching the chequered flag after nearly 3 hours.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2020-Season/imgs/race_winners.png" alt="2020_race-winners" class="center">

In addition to the race winner, the second and third-place drivers complete the podium. As shown below, a total of 13 different drivers from 7 teams achieved podium finishes. **Scuderia Ferrari** had a challenging season with 3 podium finishes, reflecting a below-par performance compared to their historical standards. Moreover, it is worth mentioning that **Albon, Norris, Gasly**, and **Ocon** celebrated their first Formula 1 podium achievements.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2020-Season/imgs/podium_finishes.png" alt="2020_podium-finishes" class="center">

Finishing inside the top 10 secures points for a racing weekend. As indicated below, 20 different drivers scored at least one point-finish. **Hamilton** achieved an impressive 16 point-finishes in 17 races (excluding the **Sakhir GP**), where **George Russell**'s point finish for **Mercedes AMG Petronas** made **Williams** the only non-scoring team in the 2020 Constructor grid. Additionally, **Nico Hülkenberg** secured top 10 finishes in two out of the three races he competed in for **Racing Point**, but his pursuit of a podium continues, holding the record for the most Grand Prix starts without a podium.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2020-Season/imgs/point_finishes.png" alt="2020_point-finishes" class="center">

One additional point is awarded to the driver who sets the fastest lap while finishing within the top 10 positions. All the drivers mentioned below deserved this accolade by maintaining their position within the required range. Once again, **Hamilton** takes the top spot with an impressive six fastest laps to his name. Following closely behind, **Verstappen** achieved this feat in three different races, showcasing his exceptional speed and skill on the track.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2020-Season/imgs/fastest_laps.png" alt="2020_fastest-lap" class="center">

In Formula 1, retirements due to mistakes or mechanical issues are inevitable. Throughout the 2020 season, a total of DNFs was noted, with 6 being attributed to accidents, 12 to collisions between drivers, and the remaining retirements stemming from mechanical issues, particularly power unit or engine failures. Notably, **Kevin Magnussen** experienced the highest number of retirements, with 7 in total. **Stroll** and **Verstappen** shared the second spot with 5 DNFs each. It is worth highlighting **Verstappen**'s exceptional performance, as he achieved 11 podium finishes in 12 completed races, showcasing his consistent top-three results whenever he completed a race.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2020-Season/imgs/dnfs.png" alt="2020_dnfs" class="center">

## Point Progression
---
Analyzing the drivers' points throughout the season, it is evident that **Lewis Hamilton**'s remarkable consistency propelled him to secure the World Championship for the 7th time with three races remaining, as he never looked back after the third race. **Valtteri Bottas** emerged as the winner in the battle for the 2nd place, while **Max Verstappen** faced setbacks with multiple retirements. Beyond these three drivers, a fierce rivalry unfolded for the 4th place, with several drivers vying for the position. In the first half of the season, **Charles Leclerc** and **Lando Norris** occupied the spot most frequently. **Daniel Ricciardo** then made strides, thanks to his two podium finishes. However, **Sergio Perez** ultimately clinched the 4th place, aided significantly by his victory at the Sakhir GP.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2020-Season/imgs/points_progression_drivers.png" alt="2020_point-progression-drivers" class="center">

Directing our attention to the Constructors' points throughout the season, it is undeniable that the **Mercedes** team dominated the 2020 season from the very first race. They consistently extended the gap between them and **Red Bull Racing** with each subsequent race, eventually securing the Constructors' championship title with four races to spare. **Red Bull**, propelled by **Verstappen**'s strong performances, maintained a firm grip on the 2nd place for the majority of the season, with the exception of the first two races. The real battle unfolded for the coveted 3rd place, with **Racing Point, McLaren**, and **Renault** experiencing frequent shifts in the standings. It is worth noting that **Ferrari** dropped out of contention in the second half of the season. Ultimately, **McLaren**, sporting their iconic papaya orange livery, clinched the 3rd position, marking a significant achievement for the team considering their performance in recent years.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2020-Season/imgs/points_progression_constructors.png" alt="2020_point-progression-constructors" class="center">

# Conclusions and Final Standings
---
The final standings are as follows: **Lewis Hamilton** secured another championship title, surpassing his teammate **Valtteri Bottas** by over 100 points, achieving his 7th title to match **Michael Schumacher**'s record. **Max Verstappen** had a strong and consistent season, finishing 3rd overall. **Alexander Albon** struggled to keep up with his teammate's pace, displaying a noticeable performance gap within **Red Bull**. **Sergio Perez** had a solid season, deserving his 4th place finish, particularly highlighted by his victory in the **Sakhir GP**. **Daniel Ricciardo** also had a commendable season, securing his position right behind **Perez** with the help of two podium finishes. The Monegasque driver, **Charles Leclerc**, struggled to be competitive for race wins, hindered by **Ferrari**'s underperforming SF1000 car. **Sebastian Vettel**'s season was even more disappointing, as he only managed to gather 33 points. Interestingly, **Nico Hülkenberg**, who was called upon three times by **Racing Point**, scored 10 points, surpassing several drivers in the standings despite mostly driving for backmarker teams. Lastly, regarding **George Russell**, it's important to note that his points were not earned with the team name you might expect. As mentioned earlier, he achieved his points while substituting for **Mercedes** in the **Sakhir GP** (a one-time opportunity), but officially he was registered with the **Williams** for the 2020 season.

In the Constructors' Championship, **Mercedes** dominated once again, establishing a massive 200-point lead over **Red Bull Racing**. This marks their 7th consecutive title and continues their unbeaten streak since the introduction of the 1.6 liter V6 Turbo Hybrid engine era in 2014. **McLaren** had a remarkable season, engaging in a close battle with **Racing Point** and **Renault**, ultimately securing 3rd place in the standings. It is important to note that **Racing Point** had 15 points deducted in August due to the stewards' discovery that their brake ducts were directly copied from the 2019 **Mercedes** car, following **Renault**'s protest regarding the legality of the RP20's design. Without this deduction, **Racing Point** could have finished ahead of **McLaren**. **Ferrari** had a disappointing season, failing to achieve their usual top-three positions and settling for 6th place with 131 points. Additionally, it was unfortunate for **Williams** as they were unable to score any points in 2020, despite coming close on several occasions. One notable moment was **George Russell**'s 10th place position in **Imola**, which ended in a crash into the wall during a Safety Car period.

<div class="row"> <div class="column">
    <img src="https://github.com/mpalaourg/F1_DataAnalysis/blob/main/2020-Season/imgs/drivers_standings.png" alt="2020_driver-standings" style="width:100%"> </div>
  <div class="column">
    <img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2020-Season/imgs/constructor_standings.png" alt="2020_constructor-standings" style="width:100%"> </div> </div>

_Note: The data is compiled from the F1 Developer API: http://ergast.com/mrd/. Formula One retains all rights to the data used in this analysis. The analysis is intended solely for educational purposes and not for commercial use._
