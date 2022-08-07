# Global-Terrorism-Database-EDA

# Summary:

The world has been facing the problem of terrorism for ages. The very first terrorist activity ever formally recorded in a database was the assassination of Julio Guzman in the Dominican Republic, by a group named MANO D. Since then, the agenda, objective, means, motives, and scale of the terrorist activities have varied widely. Now we are dealing with attacks with targets ranging from individuals to mass, with methods that are developing to be deadlier day by day.
The approach to tackle this problem, like any other has to begin with looking at the data. And that’s what the Study of Terrorism and Response to Terrorism (START).org has been doing for decades. They have put together a comprehensive database describing over 1.7 lakh terrorist attacks around the globe from as late as the 1970s all the way to the current day. There are over 136 different fields describing each of those attacks, which will be explored in detail duly. 

# Objective:

To perform Exploratory Data Analysis on the Global Terrorism Database made available by START.org in order to uncover underlying patterns and pieces of information that would help us to gain better insight into the problem of terrorism.

# About Dataset:

Owing to the size of the dataset, it'd not be practical to perform EDA on all the fields in the dataset. Following are the 22 fields I filtered on to perform EDA: 
1. eventid: Incidents from the GTD follow a 12-digit Event ID system. 
• First 8 numbers – date recorded “yyyymmdd”. 
• Last 4 numbers – sequential case number for the given day (0001, 0002 etc). This is “0001” unless there is more than one case occurring on the same date 
2. iyear: This field contains the year in which the incident occurred. In the case of incident(s) occurring over an extended period, the field will record the year when the incident was initiated. 
3. imonth: This field contains the number of the month in which the incident occurred. In the case of incident(s) occurring over an extended period, the field will record the month when the incident was initiated. 
4. iday: This field contains the numeric day of the month on which the incident occurred. In the case of incident(s) occurring over an extended period, the field will record the day when the incident was initiated. 
5. country_txt: This field identifies the country or location where the incident occurred. Separatist regions, such as Kashmir, Chechnya, South Ossetia, Transnistria, or Republic of Cabinda, are coded as part of the “home” country. In the case where the country in which an incident occurred cannot be identified, it is coded as “Unknown.” 
6. region_txt:This field identifies the region in which the incident occurred. The regions are divided into 12 categories, and dependent on the country coded for the case. 7. city: This field contains the name of the city, village, or town in which the incident occurred. 
8. provstate: This variable records the name (at the time of event) of the 1st order subnational administrative region in which the event occurs.
3 

9. success: Success of a terrorist strike is defined according to the tangible effects of the attack. Success is not judged in terms of the larger goals of the perpetrators. The definition of a successful attack depends on the type of attack. 1 = "Yes" The incident was successful. 0 = "No" The incident was not successful. 
10. attack_type1_txt: This field captures the general method of attack and often reflects the broad class of tactics used. It consists of nine categories.. Up to three attack types can be recorded for each incident. Typically, only one attack type is recorded for each incident unless the attack consists of a sequence of events. 
11. targtype1_txt: The target/victim type field captures the general type of target/victim. When a victim is attacked specifically because of his or her relationship to a particular person, such as a prominent figure, the target type reflects that motive. For example, if a family member of a government official is attacked because of his or her relationship to that individual, the type of target is “government.” This variable consists of 22 categories 
12. gname: This field contains the name of the group that carried out the attack. 13. weaptype1_txt: This field records the general type of weapon used in the incident. 14. nkill: This field stores the number of total confirmed fatalities for the incident. The 
number includes all victims and attackers who died as a direct result of the incident. 15. nwound: This field records the number of confirmed non-fatal injuries to both perpetrators and victims 
16. nkillter: This field records the number of perpetrators killed in the incident. 17. property: This field marks whether or not there is any property damage. 18. propvalue: This field marks the value of damaged property in dollars, if property fields marks yes. 
19. ransomamt: If a ransom was demanded, then the amount (in U.S. dollars) is listed in this field 
20. ransompaid : If a ransom amount was paid, then the amount (in U.S. dollars) is listed in this field. 
21. doubtterr: In certain cases there may be some uncertainty whether an incident meets all of the criteria for inclusion. In these ambiguous cases, where there is a strong possibility, but not certainty, that an incident represents an act of terrorism, the incident is included in GTD and is coded as “Yes” for this variable. And no when there is essentially no doubt about the nature of the attack. 
2 
22. alternative_txt: This variable applies to only those cases coded as “Yes” for “Doubt Terrorism Proper?” (above). This variable identifies the most likely categorization of the incident other than terrorism. 


# Results:

I selected 25 out of 136 fields in the Global Terrorism Database to be thoroughly analysed through Exploratory Data Analysis methodology. I started off our analysis on a global scale, and dived deeper to South Asian and Indian level to compare the standing of our home country with the rest of the world. 
Attack frequency, casualties, major groups, affected regions, comparison between regions etc, were the major components of this analysis. 
I further performed a few stand alone analysis namely, Success of Terrorism, Actions of major groups, Heat map analysis of organisations and attack types used, to gain further understanding of the situation.
13 

It is to be noted that the analysis mentioned here in the documentation are a brief version of the actual project. Detailed version of the same can be found in Google Collaboratory Notebook. 
Use cases of this EDA can be extended to educational and academical use and historical pattern analysis. 
Given the size of the data set, the possibilities to continue the analysis on other fields in the dataset are quite vast. 
Future scopes of the project may include prediction and prevention of such attacks to a good extent by integration of Machine Learning and Artificial Intelligence elements.

