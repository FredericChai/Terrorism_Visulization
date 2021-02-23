# Terrorism_Visulization
 
This repo is for course 5048 Visual Analytics mid-term assignment (USYD, Schoold of Computer Science) 

The range of visualisations generated tell a compelling and concise story of the evolution of global terrorism over the last 47 years. It also shows some hidden trends and patterns within the recorded incidents and unexpected relationships between different terrorist attacks for readers of the report and provide answers to several specific terrorism related questions.


![image](https://github.com/FredericChai/Terrorism_Visulization/blob/master/scr/1.jpg)
This visualisation aims to identify the temporal patterns as well as the relative importance of each value . Figure 1 shows all deadly terrorist attacks, by location, with the size of the bubble depicting the number of fatalities and the red vs yellow colour depicting whether any of the attackers suicided in the process. The top left graph shows the five years leading up to 9/11 and top right graph shows the five years immediately following 9/11. It is striking to see how the method of attack shifted to the inclusion of suicide as a key element in many attacks after 9/11; how the deadliness of attacks increased and also how the concentration of attacks diminished in the Americas, whilst increasing in the middle-east.

![image](https://github.com/FredericChai/Terrorism_Visulization/blob/master/scr/scr/4.png)
This visualisation aims to detect geospatially clustered attacks. This animated visualization shows severe terrorist attacks (> 100 fatalities) plotted geographically over the 4 decades time frame. At the same time, through its dynamic effects, it can also explain the frequency of terrorist attacks over periods. The animation shows the time lapse of attacks at two-year intervals at known terrorist attack locations. Each node represents a terrorist attack site with at least 100 deaths. Color and size indicates the extent of the deaths tools with red used for the deadliest attacks and cyan (light blue) the lowest.

![image](https://github.com/FredericChai/Terrorism_Visulization/blob/master/scr/2.png)
This visualisation aims to detect network relations using vertex-edge visualisations. The vertices are the various terrorist organisations or factions and the vertices are the links between them. The relationship is constructed by linking the perpetrator group to its subfactions and is further extended to other groups and subfactions that are associated with the respective event by the “related events” field. Using the perpetrators’ group names and ranking the count of relationship, the above graphs compare two different algorithms drawn from the same data to show the intricate network between terrorists groups. See Implementation section for the detailed algorithm.

![image](https://github.com/FredericChai/Terrorism_Visulization/blob/master/scr/3.png)
This visualisation aims to address the advance analysis between property damage, suicide attacks and different US presidents. The double stacked bar chart shows the very uneven distribution of terrorism incidents and suicide attacks within different US administrations. The overall number of attacks are shown by the first bar within each presidency whilst suicide attacks are shown by the second bar within each presidency. The colour sections within each bar represents the severity of the property damage caused ranging from negligible (blue) to catastrophic (red).
