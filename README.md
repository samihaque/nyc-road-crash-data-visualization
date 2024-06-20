# Project Description

This project delves into the complexities of NYC’s traffic landscape by analyzing police-reported motor vehicle collisions from April 2016 onwards. We meticulously dissect various data points, including crash dates, demographics, injuries, contributing factors, and more, to uncover valuable insights.

A striking trend emerges: a surge in collisions between 2016 and 2017, followed by a significant decrease. Zooming in further, the data reveals peak accident periods during rush hour, highlighting critical times for safety interventions.

The analysis also uncovers a gender disparity, with male drivers involved in a disproportionate number of accidents. Focusing on injuries, the study identifies back, neck, knee-lower leg/foot, and head injuries as common occurrences, pinpointing areas for targeted prevention efforts. Interestingly, the data suggests that seat belts and harnesses are the primary protective measures for uninjured passengers.

The project goes beyond demographics and injuries. It unveils pedestrian/bicyclist error/confusion as the leading cause of accidents, alongside driver distraction and failure to yield right-of-way.

These findings provide a powerful roadmap for improving traffic safety in NYC. By leveraging data-driven insights, we can develop evidence-based interventions to reduce collisions, protect public health, and minimize the impact on infrastructure

# Data Description
This project analyzes traffic accidents in New York City using a comprehensive dataset of police-reported collisions from April 2016 onwards. The data, available on the NYC Open Data platform [Motor Vehicle Collisions - Person Data (NYC)](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Person/f55k-p6yu/about_data), provides valuable insights into various aspects of these incidents.

**Unit of Observation:**
Each record in the dataset represents a single individual involved in a reported traffic collision. This allows us to examine the characteristics and experiences of people impacted by these accidents.

**Key Variables:**
Crash Details: CRASH_DATE and CRASH_TIME pinpoint the exact date and time of each collision, providing a temporal context for analysis.

People Involved: PERSON_TYPE (driver, occupant, pedestrian, cyclist), PERSON_AGE, BODILY_INJURY, SAFETY_EQUIPMENT, PED_ACTION, COMPLAINT, PED_ROLE, and PERSON_SEX offer detailed information on the individuals involved, including their role in the accident, injuries sustained, age, emotional state, location within the vehicle, safety equipment usage (for occupants), pedestrian actions (if applicable), reported complaints, pedestrian role (if applicable), and gender.

Contributing Factors: CONTRIBUTING_FACTOR_1 identifies the primary cause of the collision, aiding in understanding the root cause of these incidents.

# Research Question
•	Why number of Accidents are decreasing over time?

•	What are the most prevalent contributing factors (e.g., speeding, distracted driving, pedestrian errors) associated with motor vehicle collisions in NYC?

# Finding:
Pedestrian or bicyclist errors stand out as the leading cause of accidents, followed closely by distractions, failure to yield right of way, traffic control disregard, drug-alcohol influence, and risky driving. Despite progress in mitigating these factors, distractions and risky driving persist as ongoing challenges.

**Trends:** While there has been a noticeable decline in most contributing factors, distractions and risky driving have shown minimal improvement between 2017 and 2023.
Contributing Factors and Solutions: 

1. Pedestrian or Bicyclist Error: The implementation of additional traffic lights and dedicated bike lanes has significantly reduced accidents attributed to pedestrian or bicyclist errors. Moreover, replacing stop signs with traffic lights in congested areas and extending walk sign times have minimized confusion and enhanced safety.
   
3.	Traffic Control Disregard: The deployment of speed and red light cameras, coupled with increased traffic violation penalties, has effectively curbed instances of traffic control disregard.
   
5.	Drug-Alcohol Influence: A concerted effort in raising awareness about the dangers of driving under the influence, reinforced by stringent law enforcement measures and checkpoints, has contributed to a decline in drug-alcohol-related accidents.
   
# Persistent Challenges: 
1. Distractions: Despite efforts to address distractions, particularly stemming from cell phone and earphone usage, these habits persist unabated. The proliferation of mobile devices has exacerbated the problem, with individuals failing to exercise restraint even while behind the wheel.
   
3.	Risky Driving: Despite widespread photo enforcement initiatives, reckless driving behaviors remain largely unchecked. In fact, the proportion of accidents attributable to risky driving has shown an alarming increase in 2023 compared to 2017.
   
In conclusion, while commendable progress has been made in reducing accident-causing factors, sustained efforts are imperative to effectively tackle the persistent challenges posed by distractions and risky driving.

# Limitations

Beyond the primary contributing factors, it’s essential to acknowledge other elements that could significantly impact the decrease in accidents. One such factor is the evolution of safety technology within vehicles. Over time, vehicles have incorporated advanced safety features such as alerts for unsafe speeds, lane detection systems, automatic braking mechanisms, and enhanced brake capacities. However, these advancements aren’t accounted for in the dataset, limiting our ability to analyze their influence on accident reduction.
Furthermore, the dataset lacks clarity regarding its collection methodology. It’s unclear whether the criteria for reporting accidents remained consistent over time. Without this information, we cannot definitively ascertain whether the observed reduction in collision rates is solely attributable to changes in driving behaviors or if it reflects alterations in reporting standards.

Acknowledging these limitations underscores the complexity of assessing trends in accident rates and emphasizes the need for comprehensive data collection methods and consideration of technological advancements in future analyses.

## View the whole data analysis of NYC Vehicle Crash Data here: [EDA_file.docx](https://github.com/user-attachments/files/15910815/EDA_file.docx)

## View the project final presentation here: [NYC car crash analysis presentation.pdf](https://github.com/user-attachments/files/15910443/nyc-car-crash-analysis-presentation.pdf)

## View the final report of analysis here: [Final_Report.docx](https://github.com/user-attachments/files/15910864/Final_Report.docx) 
