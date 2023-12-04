# REPORT-ON-SHARK-ATTACKS

## Table of Content
- [Business Objective](#business-objective)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [THE DASHBOARD](#the-dashboard)
- [Result and Findings](#result-and-findings)
- [Recommendation](#recommendation)
- [Limitation](#limitation)
- [Reference](#reference)

### Business Objective 

It’s time to attack the Sharks that attacked most countries over the past 100 years including location, activity, victim information like name, gender, age, shark species, etc., as part of my project as an internship with Quantum Analytics NG.

 - To find out the number of shark attacks annually over time since 1900 as well as the trends.

 - To know the countries, areas, and locations that report the most shark attacks and to know the most dangerous attacks within these countries, areas, and locations.

 - To know the body parts that are most often injured.

 - To know the attacks that are more common during certain parts of the day.

and finally…

 - To discover the species of shark that are attacking most often.

### Data Source

The dataset was provided by the Company's client in csv file format

### Tools Used

Power BI — Data Cleaning, Transformation, Analysis, and Creating Reports.

### Data Cleaning and Preparation

The Dataset has 22 Columns and over 1000 rows and it’s very, very dirty. From the screenshot above you will see how dirty the first column “Case Number” is, which is supposed to be a date column. The “Date” Column, Year, Type, Country, Area, Location, etc, are to test the cleaning and transforming knowledge of every Data Analyst.

Transformation and Cleaning:

The first thing I did was to make all the Column's validity 100% by removing blank spaces and empty fields.

I added a conditional Column to “Sex” by Changing M — Male and F-Female to have “Sex_1” as the Column header. Another Conditional Column to the “Injury” Column to determine the most injured part of the body with Column header as “Injury_1”.

I also added another Conditional Column shark “Species_1” to differentiate the different types of sharks. I extracted the “Day Name” from the “Year” Column.

These and many other Transformation processes took place to ascertain and maintain Data standardization before Visualization.

### Exploratory Data Analysis (EDA)

#### KPIs:

 - No. OF CASES = COUNT(attacks[Type Of Injury]) = 4947
 - No. OF COUNTRY = DISTINCTCOUNT(attacks[Country]) =155
 - TOTAL FATAL CASES = DISTINCTCOUNT(attacks[Name]) = 4275
 - FATAL CASES = DISTINCTCOUNT(attacks[Fatal (Y/N)]) =4
 - Activities Leading to Attack
 - Shark Attack by Year
 - Attack by Country
 - Most Injured Parts of the Body
 - Weekly Attack Trend
 - Monthly Fatal Cases
 - Fatal Cases by Location
 - The sum of Age by Fatal

### Data Analysis

Here is the analysis of the insights generated that you can see in the dashboard.

- **Activities Leading to Attack:** This insight focuses on identifying the activities that were being carried out when the shark attacks occurred. It helps to understand if certain activities are more prone to shark encounters, enabling better safety recommendations for specific water-related activities.
- **Shark Attack by Year:** Analyzing the number of shark attacks by year provides a temporal perspective on trends and patterns. It helps to identify whether there are any increases or decreases in shark attacks over time, offering insights into potential environmental or human behavior changes.
- **Attack by Country:** This insight provides a geographical perspective on shark attacks, helping to identify regions or countries with a higher incidence of shark encounters. It aids in tailoring safety measures and awareness campaigns to specific locations.
- **Most Injured Parts of the Body:** Understanding which body parts are most commonly injured in shark attacks provides insights into the severity of the incidents. This information can guide safety precautions and first aid training to address the most vulnerable areas.
- **Weekly Attack Trend:** Analyzing the weekly trend of shark attacks helps identify if there are certain days of the week when incidents are more likely to occur. This could be related to human behavior, tidal patterns, or other factors influencing shark activity.
- **Monthly Fatal Cases:** Focusing on the number of fatal cases each month helps identify if there are particular months with a higher incidence of fatal attacks. This information can contribute to understanding seasonal variations in shark behavior or human activities.
- **Fatal Cases by Location:** This insight examines the geographical distribution of fatal shark attacks. It helps pinpoint specific locations with a higher risk of fatal incidents, enabling targeted safety measures and public awareness campaigns.
- **Sum of Age by Fatal:** Summing the ages of victims in fatal cases provides an aggregate measure. This insight helps in understanding the age demographics of those most vulnerable to fatal shark attacks. It can contribute to tailored safety recommendations for specific age groups.

### THE DASHBOARD

![Screenshot_138](https://github.com/Solution92/ANALYSIS-ON-SHARK-ATTACKS/assets/144762124/aa9b36fa-80ad-453c-a1a4-1314121a542c)

### Result and Findings

Based on the provided table of shark attack cases, here are some results and findings:

- Date and Location: The cases span from May to June 2017.
Incidents occurred in various countries, including Australia, USA, Bahamas, United Kingdom, and Mexico.
- Type of Incident: Most incidents are categorized as "Unprovoked," indicating that the shark initiated the interaction.
There is one "Provoked" incident where the shark's reaction was provoked, such as during fishing or attempting to lasso a shark.
- Severity of Injuries: Injuries range from no injury (board bitten) to fatal.
Fatal incidents occurred in Mexico and involved a 33-year-old male named Andres Rozada.
- Activities During Attacks: Common activities during attacks include surfing, bodyboarding, spearfishing, snorkeling, and feeding sharks.
Some incidents involved unusual activities like attempting to lasso a shark.
- Shark Species: The species involved in the attacks include a 4m white shark, 7 gill shark, 3m shark (probably a smooth hound), tiger shark, and a 9' shark.
In one case, the shark species was not specified.
- Sex and Age of Victims: Victims include both males and females.
Ages range from 19 to 73 years old.
- Time of Day: Attacks happened at different times of the day, including morning, afternoon, and shortly before 12:00.
- Reporting and Sources: The incidents were reported by various sources such as news articles and official reports.
- Invalid Incident: One incident is labeled as "Invalid" with shark involvement highly doubtful. This case involved a laceration to the thigh likely caused by a surfboard fin.

### Recommendation

Based on the analysis of the shark attack cases, here are some general recommendations:

- Be Informed: Stay informed about shark activity in areas where water activities are common.
Be aware of local shark warnings, advisories, and regulations.
- Follow Safety Guidelines: Adhere to safety guidelines and recommendations provided by local authorities, beach patrols, and marine experts.
Follow posted signs and warnings at beaches regarding shark sightings.
- Avoid High-Risk Activities: Exercise caution during activities that may attract sharks, such as spearfishing, feeding sharks, or engaging in unusual interactions with marine life.
- Time of Day: Be mindful of the time of day when engaging in water activities. Some attacks occurred in the morning, while others happened in the afternoon.
- Proper Equipment: Use proper equipment, such as shark repellents or protective gear, if available and recommended by experts.
- Emergency Preparedness: Be prepared for emergencies by having a basic understanding of first aid for shark bites and knowing the location of the nearest medical facilities.
- Reporting Incidents: Promptly report any shark sightings or incidents to local authorities and relevant organizations to contribute to ongoing research and public safety efforts.
- Education and Awareness: Increase public awareness through educational campaigns about shark behavior, their role in ecosystems, and the importance of coexisting with marine life.
- Be Cautious in Unfamiliar Waters: Exercise extra caution when engaging in water activities in unfamiliar or remote areas where shark encounters may be more likely.
- Research and Conservation: Support and participate in shark research and conservation efforts to better understand shark behavior and contribute to the preservation of marine ecosystems.
- Stay Updated: Stay updated on the latest developments in shark research, technologies, and safety measures to make informed decisions.

### Limitation

While the table provides valuable information on shark attack cases, it also has some limitations:

- Incomplete Information: Some entries lack complete data, such as missing age, sex, or species information. Incomplete details can limit the analysis and understanding of the incidents.
- Limited Timeframe: The table covers a specific timeframe (May to June 2017), and conclusions drawn are based on this limited period. It may not represent long-term trends or patterns.
- Inconsistency in Reporting: Reporting practices may vary across countries, regions, or sources. Inconsistencies in reporting styles or criteria for categorizing incidents can affect the accuracy and comparability of data.
- Limited Demographic Information: The table provides limited demographic information about the victims. A more detailed analysis could explore factors like experience level, local residency, and activity patterns, which might contribute to a more nuanced understanding of the incidents.
- No Follow-up Information: The table lacks follow-up information on the victims' recovery, rehabilitation, or any subsequent incidents related to the reported cases.
- Potential Bias in Reporting: The data may be subject to reporting bias, where more severe incidents or those attracting media attention are more likely to be documented. Less severe incidents may go unreported.

### Reference.

PDF and Source Links: Each case has associated PDF links and sources for further reference.

 - [Flinders](http://sharkattackfile.net/spreadsheets/pdf_directory/2017.06.10.b-Flinders.pdf)

- [Beloushi](http://sharkattackfile.net/spreadsheets/pdf_directory/2017.05.12-Beloushi.pdf)

- [Perry](http://sharkattackfile.net/spreadsheets/pdf_directory/2017.04.13-Perry.pdf)

- [Brazil](http://sharkattackfile.net/spreadsheets/pdf_directory/2017.02.06.b-Brazil.pdf)

- [Brevard](http://sharkattackfile.net/spreadsheets/pdf_directory/2017.01.05-Brevard.pdf)





























