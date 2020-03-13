# 2020 WEEKEND1 MCM/ICM PROBLEMS AND REFERENCE

## 2020 MCM Weekend 1 Problem A: Moving North
Global ocean temperatures affect the quality ofhabitats for certain ocean-dwelling species. When temperature changes are too great for their continued thriving, these species move to seek other habitats better suited to their present and future living and reproductive success. One example of this is seen in the lobster population of Maine, USA that is slowly migrating north to Canada where the lower ocean temperatures provide a more suitable habitat. This geographic population shift can significantly disrupt the livelihood of companies who depend on the stability ofocean-dwelling species.
Your team has been hired as consultants by a Scottish North Atlantic fishery management consortium. The consortium wants to gain a better understanding ofissues related to the potential migration of Scottish herring and mackerel from their current habitats near Scotland if and when global ocean temperatures increase. These two fish species represent a significant economic contribution to the Scottish fishing industry. Changes in population locations of herring and mackerel could make it economically impractical for smaller Scotland-based fishing companies, who use fishing vessels without on-board refrigeration, to harvest and deliver fresh fish to markets in Scotland fishing ports.

Requirements
1. Build a mathematical model to identify the most likely locations for these two fish species over the next 50 years, assuming that water temperatures are going to change enough to cause the populations to move.
2. Based upon how rapidly the ocean water temperature change occurs, use your model to predict best case, worst case, and most likely elapsed time(s) until these populations will be too far away for small fishing companies to harvest ifthe small fishing companies continue to operate out of their current locations.
3. In light ofyour predictive analysis, should these small fishing companies make changes to their operations?

- a. If yes, use your model to identify and assess practical and economically attractive strategies for small fishing companies. Your strategies should consider, but not be limited to, realistic options that include:
    - Relocating some or all of a fishing company's assets from a current location in a Scottish port to closer to where both fish populations are moving;
    - Using some proportion o f small fishing vessels capable of operating without land- based support for a period oftime while still ensuring the freshness and high quality ofthe catch.
    - Other options that your team may identify and model.

- b. If your team rejects the need for any changes, justify reasons for your rejection based on your modeling results as they relate to the assumptions your team has made.

4. Use your model to address how your proposal is affected if some proportion of the fishery moves into the territorial waters(sea) of another country.

5. In addition to your technical report a one- to two-page article for Hook Line and Sinker magazine to help fishermen understand the seriousness of the problem and how your proposed solution(s) will improve their future business prospects.

Your submission should consist of:
- One-page Summary Sheet
- Table of Contents
- Two-page Memo
- Your solution of no more than 20 pages, for a maximum of 24 pages with your summary, table of contents, and two-page memo.

Note: Reference List and any appendices do not count toward the page limit and should appear after your completed solution. You should not make use of unauthorized images and materials whose use is restricted by copyright laws. Ensure you cite the sources for your ideas and the materials used in your report.

Glossary
Fishery: The collection of fish of a given species and the area that they inhabit.

Habitat: The type of the environment in whichan organism or group mormally lives or occurs.

Small Fishing Company: A company engaged in commercial fishing with limited or very limited financial resources to invest in new equipment/vessels.

Territorial Waters(sea): "as defined by the 1982 United Nations Convention on the Law of the Sea, is a belt of coastal waters extending at most 12 nautial miles (22.2 km; 13.8 mi)from the baseline (usually the mean low-water mark) of a coastal state. The territorial sea is regarded as the sovereign territory of the state, althrough foreign ships (military and civilian) are allowed innocent passages through it, or transit passage for straits; this sovereignty also extends to the airspace over and seabed below." [Territorial Waters. (n.d.). In Wikipedia. Retrieved January 28, 2020, from https://en.wikipedia.org/wiki/Territorial_waters.]

## Problem A data
1. Met Office Hadley Centre observations datasets: https://www.metoffice.gov.uk/hadobs/hadisst/index.html
2. https://www.gov.scot/publications/scottish-sea-fisheries-statistics-2016-9781788512169/pages/3/
3. [reference solution](2020美赛A提参考思路（1）.pdf)

## 2020 ICM Weekend 1 Problem D: Teaming Strategies
As societies become more interconnected, the set of challenges they face have become increasingly complex. We rely on interdisciplinary teams of people with diverse expertise and varied perspectives to address many of the most challenging problems. Our conceptual understanding of team success has advanced significantly over the past 50+ years allowing for better scientific, creative, or physical teams to address these complex issues. Researchers have reported on best strategies for assembling teams, optimal interactions among teammates, and ideal leadership styles. Strong teams across all sectors and domains are able to perform complex tasks unattainable through either individual efforts or a sequence of additive contributions of teammates.
One of the most informative settings to explore team processes is in competitive team sports. Team sports must conform to strict rules that may include, but are not limited to, the number of players, their roles, allowable contact between players, their location and movement, points earned, and consequences of violations. Team success is much more than the sum of the abilities of individual players. Rather, it is based on many other factors that involve how well the teammates play together. Such factors may include whether the team has a diversity of skills (one person may be fast, while another is precise), how well the team balances between individual versus collective performance (star players may help leverage the skills of all their teammates), and the team’s ability to effectively coordinate over time (as one player steals the ball from an opponent, another player is poised for offense).
In light of your modeling skills, the coach of the Huskies, your home soccer (known in Europe and other places as football) team, has asked your company, Intrepid Champion Modeling (ICM), to help understand the team’s dynamics. In particular, the coach has asked you to explore how the complex interactions among the players on the field impacts their success. The goal is not only to examine the interactions that lead directly to a score, but to explore team dynamics throughout the game and over the entire season, to help identify specific strategies that can improve teamwork next season. The coach has asked ICM to quantify and formalize the structural and dynamical features that have been successful (and unsuccessful) for the team. The Huskies have provided data[1] detailing information from last season, including all 38 games they played against their 19 opponents (they played each opposing team twice). Overall, the data covers 23,429 passes between 366 players (30 Huskies players, and 336 players from opposing teams), and 59,271 game events.
To respond to the Huskie coach’s requests, your team from ICM should use the provided data to address the following:
 Create a network for the ball passing between players, where each player is a node and each pass constitutes a link between players. Use your passing network to identify network patterns, such as dyadic and triadic configurations and team formations. Also consider other structural indicators and network properties across the games. You should
[1] This data set was processed from a much larger dataset covering nearly 2000 matches from five European national soccer competitions, as well as the 2018 World Cup [1].
    
explore multiple scales such as, but not limited to, micro (pairwise) to macro (all players) when looking at interactions, and time such as short (minute-to-minute) to long (entire game or entire season).
 Identify performance indicators that reflect successful teamwork (in addition to points or wins) such as diversity in the types of plays, coordination among players or distribution of contributions. You also may consider other team level processes, such as adaptability, flexibility, tempo, or flow. It may be important to clarify whether strategies are universally effective or dependent on opponents’ counter-strategies. Use the performance indicators and team level processes that you have identified to create a model that captures structural, configurational, and dynamical aspects of teamwork.
- Use the insights gained from your teamwork model to inform the coach about what kinds of structural strategies have been effective for the Huskies. Advise the coach on what changes the network analysis indicates that they should make next season to improve team success.
- Your analysis of the Huskies has allowed you to consider group dynamics in a controlled setting of a team sport. Understanding the complex set of factors that make some groups perform better than others is critical for how societies develop and innovate. As our societies increasingly solve problems involving teams, can you generalize your findings to say something about how to design more effective teams? What other aspects of teamwork would need to be captured to develop generalized models of team performance?
Your submission should consist of:
- One-page Summary Sheet
- Table of Contents
- Your solution of no more than 20 pages, for a maximum of 22 pages with your summary
and table of contents.
Note: Reference List and any appendices do not count toward the page limit and should appear after your completed solution. You should not make use of unauthorized images and materials whose use is restricted by copyright laws. Ensure you cite the sources for your ideas and the materials used in your report.
Attachment
2020_Problem_D_DATA.zip
fullevents.csv matches.csv passingevents.csv README.txt
 
Glossary
Dyadic Configurations: relationships involving pairs of players. Triadic Configurations: relationships involving groups of three players.
Cited Reference
[1] Pappalardo, L., Cintia, P., Rossi, A. et al. A public data set of spatio-temporal match events in soccer competitions. Sci Data 6, 236 (2019).
Optional Resources
Research in football (soccer) networks has led to many articles that discuss related topics. A few articles are listed below. You are not required to use any of these sample articles in your solution, nor is it a comprehensive list. We encourage teams to utilize any journal article that supports their approach to the problem.
Buldú, J.M., Busquets, J., Echegoyen, I. et al. (2019). Defining a historic football team: Using Network Science to analyze Guardiola’s F.C. Barcelona. Sci Rep, 9, 13602.
Cintia, P., Giannotti, F., Pappalardo, L., Pedreschi, D., & Malvaldi, M. (2015). The harsh rule of the goals: Data-driven performance indicators for football teams. 2015 IEEE International Conference on Data Science and Advanced Analytics (DSAA), 1-10, 7344823.
Duch J., Waitzman J.S., Amaral L.A.N. (2010). Quantifying the performance of individual players in a team activity. PLoS ONE, 5: e10937.
GÜRSAKAL, N., YILMAZ, F., ÇOBANOĞLU, H., ÇAĞLIYOR, S. (2018). Network Motifs in Football. Turkish Journal of Sport and Exercise, 20 (3), 263-272.

## Problem D data
1. [2020_Problem_D_DATA.zip](2020_Problem_D_DATA.zip)
2. [Problem D reference solution 1](2020美赛D题参考思路（1）.pdf)
3. [Problem D reference solution 2](D_.pic_hd.jpg)
4. [paper: Defning a historic football team- Using Network Science to analyze Guardiola’s F.C. Barcelona.pdf](Defning_a_historic_football_team-Using_Network_Science_to_analyze.pdf)
5. [paper: Quantifying the Performance of Individual Players in a Team Activity](Quantifying_the_Performance_of_Individual_Players_in_a_Team_Activity.pdf)
6. [A public data set of spatiotemporal match events in soccer
competitions]()


## 2020 ICM Weekend 1 Problem E: Drowning in Plastic
Since the 1950s, the manufacturing of plastics has grown exponentially because of its variety of uses, such as food packaging, consumer products, medical devices, and construction. While there are significant benefits, the negative implications associated with increased production of plastics are concerning. Plastic products do not readily break down, are difficult to dispose of, and only about 9% of plastics are recycled[1]. Effects can be seen by the approximately 4-12 million tons of plastic waste that enter the oceans each year[1,2]. Plastic waste has severe environmental consequences and it is predicted that if our current trends continue, the oceans will be filled with more plastic than fish by 2050[2]. The effect on marine life has been studied[3], but the effects on human health are not yet completely understood[4]. The rise of single-use and disposable plastic products results in entire industries dedicated to creating plastic waste. It also suggests that the amount of time the product is useful is significantly shorter than the time it takes to properly mitigate the plastic waste. Consequently, to solve the plastic waste problem, we need to slow down the flow of plastic production and improve how we manage plastic waste.
Your team has been hired by the International Council of Plastic Waste Management (ICM) to address this escalating environmental crisis. You must develop a plan to significantly reduce, if not eliminate, single-use and disposable plastic product waste.
- Develop a model to estimate the maximum levels of single-use or disposable plastic product waste that can safely be mitigated without further environmental damage. You may need to consider, among many factors, the source of this waste, the extent of the current waste problem, and the availability of resources to process the waste.
- Discuss to what extent plastic waste can be reduced to reach an environmentally safe level. This may involve considering factors impacting the levels of plastic waste to include, but not limited to, sources and uses of single-use or disposable plastics, the availability of alternatives to plastics, the impact on the lives of citizens, or policies of cities, regions, countries, and continents to decrease single-use or disposable plastic and the effectiveness of such policies. These can vary between regions, so considering regional-specific constraints may make some policies more effective than others.
- Using your model and discussion, set a target for the minimal achievable level of global waste of single-use or disposable plastic products and discuss the impacts for achieving such levels. You may consider ways in which human life is altered, the environmental impacts, or the effects on the multi-trillion-dollar plastic industry.
- While this is a global problem, the causes and effects are not equally distributed across nations or regions. Discuss the equity issues that arise from the global crisis and your intended solutions. How do you suggest ICM address these issues?
- Write a two-page memo to the ICM describing a realistic global target minimum achievable level of global single-use or disposable plastic product waste, a timeline to
   
reach this level, and any circumstances that may accelerate or hinder the achievement of your target and timeline.
Your submission should consist of:
- One-page Summary Sheet
- Table of Contents
- Two-page Memo
- Your solution of no more than 20 pages, for a maximum of 24 pages with your summary, table of contents, and two-page memo.
Note: Reference List and any appendices do not count toward the page limit and should appear after your completed solution. You should not make use of unauthorized images and materials whose use is restricted by copyright laws. Ensure you cite the sources for your ideas and the materials used in your report.
Glossary
Disposable Plastic Products: plastic materials or products that are not recyclable and become
trash.
Mitigate: To make less severe, to moderate, to alleviate.
Plastic Waste: plastic objects that have not been recycled properly or cannot be recycled; debris made of plastic.
Single-Use Plastic Products: products made of plastic intended for one time use before being discarded.
Cited References
[1] Geyer, R., Jambeck, J. R., & Law, K. L. (2017). Production, use, and fate of all plastics ever made. Science Advances, 3(7), e1700782.
[2] Jambeck, J. R., Geyer, R., Wilcox, C., Siegler, T. R., Perryman, M., Andrady, A., ... & Law, K. L. (2015). Plastic waste inputs from land into the ocean. Science, 347(6223), 768-771.
[3] Li, W. C., Tse, H. F., & Fok, L. (2016). Plastic waste in the marine environment: A review of sources, occurrence and effects. Science of the Total Environment, 566, 333-349.
[4] Galloway T.S. (2015) Micro- and Nano-plastics and Human Health. In: Bergmann M., Gutow L., Klages M. (eds) Marine Anthropogenic Litter.


## Problem E data
1. CHINA STATISTICAL YEAR BOOK http://www.stats.gov.cn/tjsj/ndsj/2018/indexeh.htm
2. https://www.zhihu.com/question/371767259
