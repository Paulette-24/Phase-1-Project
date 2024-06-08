## Introduction
In this notebook, I will walk you through the comprehensive analysis and recommendations for purchasing and operating aircraft with the lowest risk. This initiative is part of our strategic move to diversify into new industries, and we aim to provide you with data-driven insights to make informed decisions.
## Business Understanding
As our company diversifies into new industries, we explore the potential of purchasing and operating aircraft for commercial and private enterprises. This strategic move requires a deep understanding of the risks to ensure informed decision-making. 

Our goal is to select aircraft that meet our operational needs and have a proven track record of safety.
### Main Objective
Our main objective is to identify the aircraft models with the lowest risk profiles based on historical accident data.

In our endeavor to diversify our company's portfolio by venturing into the aviation industry, it is crucial to base our investment decisions on solid, data-driven insights. 

The aviation sector, while promising, involves significant risks due to the nature of air travel and the complexities involved in operating aircraft. Therefore, understanding and mitigating these risks is essential for the success and safety of our operations.
### Specific Objective
- Which aircraft models have the lowest accident rates?
- How do the total fatalities and serious injuries vary across the aircraft models?
- What impact do weather conditions have on the accident rates of various aircraft models?
- How have accident rates for specific aircraft models changed over the past 20 years?
- Which aircraft models demonstrate the best safety records and reliability based on historical data?
- Are there certain aircraft models that consistently perform better in terms of safety across different conditions?
  
## Data Understanding

**Description**

The data was sourced from [Kaggle](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) and includes detailed information on aviation accidents from 1962 to 2023. This dataset contains critical information that can help us analyze and understand the risks associated with different aircraft models.

**Attributes**

The dataset has 9 key attributes. Here's a breakdown of the attributes and what they represent:

- Accident and incident dates - The date of the accident or incident occurred.
- Aircraft manufacturer(make) and model - The manufacturer(make) and model of the aircraft involved in the accident.
- Injury severities - The number of fatalities and serious injuries resulting from the accident.
- Weather conditions - The weather conditions at the time of the accident.
- Locations - The geographical location where the accident occurred.
- Investigation Type - Indicates whether the record is an accident or incident.
- Accident Number - An internal identifier used by the reporting authority.
- Airport Code - The details about the airport involved.
- Purpose of Flight - The intended purpose of the flight (e.g., personal, commercial).

**Source of Data**

The data used for this analysis was sourced from the National Transportation Safety Board (NTSB). It covers aviation accident data from 1962 to 2023, including detailed records of civil aviation accidents and selected incidents in the United States.

**Description of Data**

The dataset includes a wide range of variables essential for understanding aviation safety and risk factors. Key variables include the aircraft make and model, injury data (fatal, serious, minor injuries, and uninjured), weather conditions (e.g., Visual Meteorological Conditions (VMC), Instrument Meteorological Conditions (IMC)), the phase of flight during the accident (e.g., takeoff, cruise, landing), the date of the accident, and the geographical location of each incident. This comprehensive data allows for an in-depth analysis of aviation safety and risk factors, facilitating informed decision-making.

![aircraft Makes](https://github.com/Paulette-24/Phase-1-Project/assets/170407562/6ca41bdb-5aca-4674-9531-86f7cdad6e1b)

This bar chart illustrates the frequency of accidents involving the top 10 aircraft makes. The chart shows that Cessna aircraft have the highest frequency of accidents, with over 20,000 incidents. This is significantly higher than the next most frequent make, Piper, which has approximately half the number of accidents as Cessna. Other aircraft makes in the top 10 include Beech, Bell, Boeing, Grumman, and Mooney. The presence of different spellings for the same manufacturer suggests a need for data cleaning to consolidate entries.

![Scatter Plot](https://github.com/Paulette-24/Phase-1-Project/assets/170407562/db21c2c8-cc56-4563-84f3-6a02c7015b00)

This scatter plot visualizes the relationship between total fatal injuries and total serious injuries, with data points color-coded by weather conditions (UNK, IMC, VMC, Unk). The majority of incidents involve fewer than 50 total fatal injuries and 20 total serious injuries. Incidents in Visual Meteorological Conditions (VMC) are more frequent and spread across a wider range of injury counts, suggesting that a significant number of accidents occur under generally favorable weather conditions. Conversely, incidents under Instrument Meteorological Conditions (IMC) tend to cluster at lower injury counts but still highlight critical risk areas.

![Screenshot_7](https://github.com/Paulette-24/Phase-1-Project/assets/170407562/7168ec4e-0b2a-4963-a687-18116e0881d7)

The bar chart illustrates the accident frequency for the top 10 aircraft models. The Cessna 172 model has the highest accident count, approaching 500 incidents, followed by the Boeing 737 with slightly over 400 accidents. The Cessna 152 and Cessna 182 models each have around 200 accidents, while the Cessna 172S, Piper PA-28, and Cessna 172N models each report just under 200 incidents. The Robinson R44 model has the lowest count among the top 10, with around 100 accidents. This data highlights that Cessna models, particularly the 172, dominate the accident statistics, suggesting a high operational volume or potential safety concerns. The consistent presence of Cessna models among the highest accident counts indicates a need for focused safety reviews and potential improvements in operational protocols for these aircraft.

## Conclusion
In conclusion, we have discovered key aircraft models that demonstrate lower accident frequencies and minimal severe injuries. This information is crucial in guiding our purchase decisions to ensure we select the safest and most reliable aircraft.

**Observation 1**: By analyzing the dataset, we identified aircraft models that are involved in fewer accidents compared to others. These models consistently show lower numbers of recorded incidents over the years. Aircraft with lower accident frequencies are safer, reducing the likelihood of future incidents. This is critical for operational safety and maintaining the company’s reputation.

**Observation 2**: We also focused on the severity of injuries in the accidents. Some aircraft models not only have fewer accidents but also result in fewer severe injuries when accidents do occur. Choosing an aircraft that has a track record of minimal severe injuries ensures higher safety standards for passengers and crew. This translates to greater confidence and trust in the airline’s safety measures.

## Recommendations
1. Choose an Aircraft with the Lowest Accident Rates i.e. prioritize aircraft models like the G103 and Kitfox II, which show lower accident frequencies.
     - Reason: Lower accident rates translate to reduced operational risks and potentially lower insurance premiums.
  
2. Focus on models like the EPIC LT and PITTS MODEL 12, which have reported no fatalities and minimal serious injuries.
     - Reason: Aircraft with fewer severe injuries are indicative of better safety records and robust engineering, ensuring passenger safety and confidence.

3. Develop and implement rigorous training programs and enhanced safety protocols to mitigate risks.
     - Reason: Proactive measures in training and safety can mitigate risks and enhance the overall safety record of the aviation division.


