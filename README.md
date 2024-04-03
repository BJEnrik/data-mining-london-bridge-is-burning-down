<div><span style="background-color: #26241B; padding-top: 100px; padding-right: 20px; padding-bottom: 50px; padding-left: 20px; color: #FFFFFF; font-size: 24px; font-weight: bold">EXECUTIVE SUMMARY </span></div>

The London Fire Brigade (LFB) is one of the largest firefighting and rescue organizations in the world. In the UK, they are also the busiest fire and rescue service. Using the incident and the mobilisation datasets of London Fire Brigade (LFB), the study aims to describe the characteristics of LFB's incident response times.

Prior to the analysis, the 2022 data of the datasets were dropped since the year 2022 is still ongoing. Both incident and mobilisation datasets for 2009 to 2021 were consolidated since the data were originally separated into different year groups. The duplicate values were then dropped, and the null values were handled. Many columns from the datasets were also dropped as they were not part of the scope of the study. The dataset was then finally consolidated into a single SQLite database.

The analyses revealed that from 2009 to 2021, the LFB met the response time target of 360 seconds or 6 minutes. In addition, the peak performance (lowest mean response time) of the London Fire Brigade is observed at 9am with a response time of 330.5 seconds and at 10pm with a response time of 328.96 seconds. It was also revealed that only in 2009 and 2010 that the LFB failed to meet the turnout time standard of 90 seconds. Lastly, the lowest travel times was observed between 11am to 7pm.

<div><span style="background-color: #26241B; padding-top: 100px; padding-right: 20px; padding-bottom: 50px; padding-left: 20px; color: #FFFFFF; font-size: 24px; font-weight: bold">INTRODUCTION </span></div>

<h2 style="color:#F73718">Background</h2>

Established in 1833, the London Fire Brigade (LFB) is one of the largest firefighting and rescue organizations in the world. They are also the busiest fire and rescue service in the UK, handling around 100,000 incidents every year. This large magnitude of incident responses is made possible by employing over 5,000 people composed of the operational staff (the firefighters and rescue personnel), the control staff (the staff who take the emergency calls), and the non-uniformed and non-operational staff (support staff like those in IT and Finance). All of the operational staff are full-time, in contrast with other brigades that employ retained firefighters (on-call firefighters who live and work near the station). 

The LFB has 103 fire stations, including one river station. Scattered among these fire stations are 101 dual pump ladders (the main fire appliance of the LFB), 55 pumps, 2 fireboats, and other fire and general rescue equipment. These employees and equipment enable LFB to respond to incident calls 24 hours a day.

Every incident call received by LFB and their response characteristics since January 2009 is available on the London Datastore website, pursuant to the vision of the Greater London Authority (GLA) to make London’s data freely accessible by anyone. The aim of this study is to investigate the incident response times of LFB obtained from this dataset from 2009 up to 2021.


<h2 style="color:#F73718">Problem Statement</h2>

- What are the response time characteristics of the London Fire Brigade? Specifically:
- How did the LFB's response times to incidents differ across the years from 2009 to 2021?
- How did the response time differ by time of day?
- How are the response times distributed?
- How did the LFB's turnout times to incidents differ across the years from 2009 to 2021?
- How did the turnout time differ by time of day?
- How did the LFB's travel times to incidents differ across the years from 2009 to 2021?
- How did the travel time differ by time of day?

<h2 style="color:#F73718">Data Description</h2>

The study utilized two types of datasets from the LFB — the incident and mobilization datasets.

<h3 style="color:#03276F"><u>Incident Dataset</u></h3>

- This dataset contains the details of every incident responded by the LFB since January 2009. Data about when and where the incident happened and the type of incident dealt with are provided.
- https://data.london.gov.uk/dataset/london-fire-brigade-incident-records

<h3 style="color:#03276F"><u>Mobilisation Dataset</u></h3>

- This dataset contains the details of every fire engine (pumping appliance) sent to an incident since January 2009. Data about the appliance mobilised, where it was deployed frp, and the times recorded for arriving at the incident are provided.
- https://data.london.gov.uk/dataset/london-fire-brigade-mobilisation-records

<br />

Specifically, the following files were used in the study:
<h3 style="color:#03276F"><u>List of Datasets Used</u></h3>

- <b style="color:#03276F">LFB Incident Data from 2009 to 2021</b>

    - 'LFB Incident data from January 2009 to December 2012.xlsx'
    - 'LFB Incident data from January 2013 to December 2016.xlsx'
    - 'LFB Incident data from January 2017.xlsx'
    - 'LFB Incident data January 2019 to August 2022.xslx'
    
- <b style="color:#03276F">LFB Mobilisation Data from 2009 to 2021</b>

    - 'LFB Mobilisation data from January 2009.csv'
    - 'LFB Mobilisation data from January 2009 to 2015.csv'
    - 'LFB Mobilisation data from January 2016.csv'
    - 'LFB Mobilisation data Last 3 years January 2019 to August 2022.xlsx'

<div><span style="background-color: #26241B; padding-top: 100px; padding-right: 20px; padding-bottom: 50px; padding-left: 20px; color: #FFFFFF; font-size: 24px; font-weight: bold">Conclusion and Recommendations </span></div>

**Conclusions**
- We can conclude that the presence of people within their homes increased the number of reported incidents which is caused by the Pandemic.
- Events that will prevent people from going out of their homes should be taken into account where the fire force should be increasing their resources to deal with a sudden spike of incidents

**Recommendations**
- At times where the total response time is highest and since every second counts when it comes to first response to an incident to save lives, it is recommended to increase an alert level during longest response time to act as hot standby in case of an incident

<h1 style="color:#F73718">References and Acknowledgments</h1>

- About – London Datastore. (2011). London.gov.uk. https://data.london.gov.uk/about/

- About us. (n.d.). Www.london-Fire.gov.uk. https://www.london-fire.gov.uk/about-us/

- Incident response times – Fire Facts – London Datastore. (n.d.). Retrieved October 25, 2022, from https://data.london.gov.uk/dataset/incident-response-times-fire-facts

- London Fire Brigade. (n.d.). Firefighting Wiki. Retrieved October 25, 2022, from https://fire.fandom.com/wiki/London_Fire_Brigade

- London Fire Brigade Incident Records – London Datastore. (2011). London.gov.uk. https://data.london.gov.uk/dataset/london-fire-brigade-incident-records

- Meet London Fire Brigade. (n.d.). Www.london-Fire.gov.uk. Retrieved October 25, 2022, from https://www.london-fire.gov.uk/about-us/meet-london-fire-brigade/
