---
title: Max Verstappen a double F1 World Champion
summary: Red Bull dominance, Ferrari mistakes, Max secures his second championship.
tags:
- max-verstappen
- charles-leclerc
- formula1
date: "2022-11-21T00:00:00Z"

image:
  caption: ""
  focal_point: Smart

url_code: "https://github.com/mpalaourg/F1_DataAnalysis/blob/main/2022-Season/Season%20Analysis.ipynb"
url_pdf: ""
url_slides: ""
url_video: ""
---

The 2022 Formula 1 season brought significant changes with the introduction of new cars under the revised technical regulations. Surprisingly, **Mercedes** failed to meet expectations, struggling to maintain their dominant form. As a result, the battle for supremacy shifted between **Red Bull** and **Scuderia Ferrari**. However, **Ferrari**'s performance was marred by numerous mistakes, particularly in terms of strategy, revealing an area of weakness for the team. This allowed **Red Bull** and their driver **Max Verstappen** to seize control and secure both the Constructors' and Driver World Championship titles with relative ease in the second half of the season.

# Race Calendar
---
As displayed below, the 2022 Formula 1 season boasted an exhilarating race calendar comprising 22 races in 20 countries. Noteworthy inclusions were the return of the **Australian, Canadian, Japanese**, and **Singapore Grands Prix** after a two-year hiatus caused by the COVID-19 pandemic. However, certain races, such as the **Portuguese, Styrian**, and **Turkish Grands Prix**, were not part of the 2022 lineup. The **Qatar Grand Prix** also did not feature, with plans for its return in 2023. COVID-19 restrictions led to the cancellation of the **Chinese Grand Prix** for another year. The **Russian Grand Prix** faced initial suspension due to the Russian invasion of Ukraine and was subsequently canceled. On a more positive note, the debut of the **Miami Grand Prix** added further excitement to the championship, offering fans a fresh and thrilling addition to the race calendar.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/calendar.png" alt="2022_calendar" class="center">

# Drivers and Constructors
---
The 2022 Formula 1 grid featured 10 teams and 22 drivers, including 2 reserve drivers. Notable changes from the previous season include:

- **Valtteri Bottas** made a move to **Alfa Romeo**, taking the seat left vacant by the retirement of **Kimi Räikkönen**.
- **George Russell**, previously with **Williams**, joined **Mercedes**, replacing **Bottas**.
- **Alexander Albon** joined **Williams** to fill **Russell**'s seat.
- **Zhou Guanyu** joined **Alfa Romeo**, replacing **Antonio Giovinazzi**.
- **Nikita Mazepin** was dropped by **Haas**, and his seat was filled by **Kevin Magnussen**.

**Nico Hülkenberg** competed in two races for **Aston Martin**, replacing **Sebastian Vettel** who tested positive for Covid-19. **Nyck de Vries** made his Formula One debut, competing for **Williams** in place of **Alexander Albon**, who was unable to participate due to appendicitis.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/drivers.png" alt="2022_drivers" class="center">

# 2022 Season analysis
---
This season showcased a variety of winners, with five different drivers claiming victories, many of them starting from favorable grid positions. Notable triumphs included **George Russell**'s first win at the **Brazilian Grand Prix**, which was also the only win for **Mercedes** this year, and **Carlos Sainz**'s maiden Formula 1 victory in **Silverstone**. **Max Verstappen** stood out with an impressive 15 wins, including remarkable performances such as starting from P14 in the **Belgian Grand Prix**, P10 in **Hungary**, and P7 in **Monza**. **Charles Leclerc** secured three wins, two of which came in the opening three races of the season. **Sergio Perez** celebrated two wins, both on street circuits, at the **Monaco** and **Singapore** Grand Prix, showcasing his skill in navigating challenging tracks.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/race_winners.png" alt="2022_race-winners" class="center">

Standing on the podium is a rewarding moment for drivers and their teams, symbolizing their hard work and achievements. It is evident from the image below that **Max Verstappen** secured the most podium finishes with 17, showcasing his consistent performances throughout the season. **Charles Leclerc** and **Sergio Perez** followed behind with 11 podiums each. **Carlos Sainz, Lewis Hamilton**, and **George Russell** also featured prominently in the standings, demonstrating their strong performances. Notably, **Lando Norris** stood out with a podium finish at the **Emilia Romagna Grand Prix**, capitalizing on a late-race mistake from **Charles Leclerc** that cost him the third-place position. 
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/podium_finishes.png" alt="2022_podium-finishes" class="center">

Upon examining the point finishes, it becomes clear that **Max Verstappen** and **George Russell** were the most consistent drivers, both securing 20 point finishes. They were closely followed by their respective teammates, **Sergio Perez** and **Lewis Hamilton**, as well as **Charles Leclerc**. **Lando Norris** had an exceptional season with 17 point finishes, showcasing his strong performances while his teammate **Daniel Ricciardo** faced struggles. **Alpine**'s **Esteban Ocon** and **Fernando Alonso** capitalized on the team's well-designed car, establishing themselves as the best from the second-tier teams in 2022. Notably, **Mick Schumacher** achieved his first points in his Formula 1 career at **Silverstone**, a significant milestone. **Nyck de Vries** also scored points on his Formula 1 debut, finishing ninth at **Monza**. Another driver to score points in their debut race was **Zhou Guanyu** for **Alfa Romeo** in the **Bahrain Grand Prix**, adding two more point finishes to his tally throughout the 2022 season.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/point_finishes.png" alt="2022_point-finishes" class="center">

The F1 Sprint format made its return for the 2022 championship, maintaining the same weekend structure as in 2021. The sprints were held at **Imola**, the **Red Bull Ring**, and **Interlagos**, with a notable change being the awarding of points to the top eight finishers instead of just the top three as in the previous year. As depicted below, this new scoring system allowed more drivers to benefit from the F1 Sprint sessions. **Max Verstappen** continued to excel, topping the charts with an additional 21 points from the sprint races. **Carlos Sainz** and **Charles Leclerc** put in strong performances, closely following **Verstappen**. **Sergio Perez** and **George Russell** also secured extra points through the sprint sessions, showcasing their abilities in these shorter races. The increased number of point-earning opportunities in the F1 Sprint format added an extra dynamic to the championship.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/sprint_points.png" alt="2022_sprint-points" class="center">

The opportunity to score an extra point for the fastest lap during a race session was once again present in the 2022 season, provided the driver finished inside the top 10. **Max Verstappen** continued to showcase his speed and skill, topping the charts with 5 points for the fastest laps. In **Singapore**, **George Russell** finished in P14, missing out on the additional point, while **Zhou Guanyu** in **Japan** finished in 16th place, also unable to secure the fastest lap point. Notably, **Verstappen** and **Russell** achieved a maximum of 34 points in a race weekend at the **Emilia Romagna** and **São Paulo Grand Prix**. This exceptional feat was accomplished by winning the F1 Sprint session, the race itself, and scoring the fastest lap, further highlighting their outstanding performances and ability to maximize their points haul.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/fastest_laps.png" alt="2022_fastest-lap" class="center">

In the realm of Formula 1, retirements are an inevitable aspect of the sport, resulting from mistakes or mechanical issues. Throughout the 2022 season, a total of 74 DNFs were recorded. Among these, eight were attributed to accidents, while ten stemmed from collisions between drivers. The remaining retirements were a consequence of various mechanical issues, notably involving gearboxes, hydraulics, power units, or engine failures. **Carlos Sainz** endured the highest number of retirements with six, a notable contrast to his flawless record of completing all races in the 2021 season. **Valtteri Bottas, Fernando Alonso**, and **Yuki Tsunoda** also faced six retirements each, revealing reliability issues for **Alfa Romeo, Alpine**, and **AlphaTauri**. Both **Williams** drivers, as well as **Zhou Guanyu** and **Kevin Magnussen**, also encountered challenges leading to retirements, exposing issues within their respective teams. One of **Zhou**'s retirements was a [horrific accident at **Silverstone**](https://www.youtube.com/watch?v=T7kjjkh2lmM) following contact with **George Russell**'s **Mercedes**, serving as a stark reminder of the risks and incidents that can occur on the track.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/dnfs.png" alt="2022_dnfs" class="center">

## Point Progression
---
Upon closer examination of the drivers' points throughout the season, it becomes evident that **Charles Leclerc** initially led the World Championship until the 6th race, where **Max Verstappen** overtook him in the standings and went on to secure his second consecutive World Championship title. **Leclerc**'s hopes for the championship dwindled as the season progressed, hampered by strategic mistakes from **Ferrari** and personal errors on track. In the latter half of the season, **Leclerc** found himself locked in a battle for second place with **Sergio Perez**, ultimately emerging victorious in the final race of the season. **George Russell** had an impressive debut year with **Mercedes**, even managing to outperform **Lewis Hamilton** on the standings. Notably, **Hamilton** attempted a late-season comeback, but it was **Carlos Sainz** from **Ferrari** who claimed the fifth-place position in the championship standings.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/points_progression_drivers.png" alt="2022_point-progression-drivers" class="center">

Shifting our focus to the Constructors' Championship, **Red Bull Racing** continued to extend their lead with each race, ultimately securing their 5th overall Constructors' World Championship and their first since 2013. While **Mercedes** remained close to **Ferrari** throughout the season, they were unable to surpass the Italian team, resulting in **Ferrari** securing second place. A captivating battle unfolded for the fourth place in the standings, with **Alpine** and **McLaren** fiercely competing. Ultimately, the combined efforts of the **Alpine** drivers proved to be enough to secure them the 4th place, triumphing over **Lando Norris**'s heroic performances for **McLaren**.
<img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/points_progression_constructors.png" alt="2022_point-progression-constructors" class="center">

# Conclusions and Final Standings
---
**Max Verstappen** claimed his second consecutive World Championship title, finishing with a commanding lead of nearly 150 points over his closest rival. **Leclerc** secured second place, narrowly edging out **Sergio Perez**, who settled for third. **George Russell** had a remarkable season, earning his maiden Formula 1 victory in **São Paulo** and outperforming his **Mercedes** teammate, **Lewis Hamilton**, in the standings. **Hamilton** faced difficulties throughout the year, failing to secure a race win or pole position for the first time in his Formula 1 career, ultimately finishing in sixth place. **Carlos Sainz** achieved his maiden Formula 1 victory at **Silverstone** and positioned himself between the two **Mercedes** drivers in the final standings. **Lando Norris** enjoyed an exceptional season, finishing in seventh place with 122 points and showcasing his impressive performances, while his **McLaren** teammate, **Daniel Ricciardo**, faced challenges and ended the season in eleventh. **Sebastian Vettel** struggled with the **Aston Martin** car in what would be his final year in Formula 1. **Kevin Magnussen**'s standout moment was securing his maiden pole position in **São Paulo**, a first for the **Haas** team. **Mick Schumacher, Guanyu Zhou**, and **Nyck de Vries** all scored their first points in their Formula 1 careers, while **Alexander Albon** exceeded expectations in his F1 comeback with **Williams**.

In the Constructors' Championship, **Red Bull Racing** celebrated their triumph as they secured their 5th overall Constructors' World Championship and their first since 2013, following the introduction of the V6 Turbo Hybrid engine era. **Ferrari** secured second place, despite numerous strategical mistakes that ultimately led to the resignation of **Mattia Binotto** as the team's principal. **Mercedes**, endured a catastrophic season and finished in third place. An intense battle unfolded for fourth place between **Alpine** and **McLaren**, with the combined efforts of the **Alpine** drivers proving enough to secure them the 4th place, triumphing over the heroic performances of **McLaren**'s **Lando Norris**. Notably, all the teams managed to score points this season, with **Williams** finishing in last place but the other backmarkers not far ahead, grappling with their own reliability issues.
<div class="row"> <div class="column">
    <img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/drivers_standings.png" alt="2022_driver-standings" style="width:100%"> </div>
  <div class="column">
    <img src="https://raw.githubusercontent.com/mpalaourg/F1_DataAnalysis/main/2022-Season/imgs/constructor_standings.png" alt="2022_constructor-standings" style="width:100%"> </div> </div>

_Note: The data is compiled from the F1 Developer API: http://ergast.com/mrd/. Formula One retains all rights to the data used in this analysis. The analysis is intended solely for educational purposes and not for commercial use._
