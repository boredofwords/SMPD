# SMPD Arrest Data Project

*QUESTIONS I WANT DATA TO ANSWER*
---

* What is the black arrest rate for SMPD? (adjusted for demographics?) 
* How does that compare to other races? 
* What is the individual black arrest rate per officer? 

*BACKGROUND*
---

>An analysis of arrest data voluntarily reported to the FBI by thousands of city and county police departments around the country reveals that, in 800 jurisdictions, black people were arrested at a rate five times higher than white people in 2018, after accounting for the demographics of the cities and counties those police departments serve.

>In 250 jurisdictions, black people were 10 times more likely to be arrested than their white counterparts.

>The analysis, conducted by ABC News in collaboration with ABC-owned stations, covers a three-year period ending in 2018, from which the most recent data is available. 

[source](https://abcnews.go.com/US/abc-news-analysis-police-arrests-nationwide-reveals-stark/story?id=71188546 "Black people were arrested at a rate five times more than white people in 2018.")

SMPD Publishes arrest lists daily (See: [SMPD Media Arrest List](https://www.sanmarcostx.gov/DocumentCenter/View/5913/SMPD-Media-Arrest-List--06-23-2020-PDF?bidId= "Data Goldmine!") & [SMPD Incident List](https://www.sanmarcostx.gov/DocumentCenter/View/5875/SMPD-Incident-Blotter-06-29-2020-pdf "This one is not as detailed")) These are very useful for basic demographic information that can answer my questions about black arrest rates within SMPD. 

`<--insert screenshot of blotters here-->`

Fields from these reports:

Incident List Fields | Media Arrest List Fields |
--- | --- |
Incident # | Incident # |
Time Reported | Name |
Activity | Arrest Date | 
Disposition | Officer | 
Location | Age | 
. | Sex | 
. | Race | 
. | Officer | 
. | Charge |

In order to calculate an incident report based black arrest rate, we will need to know the badge number or identifying key for the officers, race of the arrestee, & date of the incident-- all of which is present in these daily exports. 

However, I was unable to find a folder or historical record of these reports past what is published on their [website](https://www.sanmarcostx.gov/511/Daily-Police-Blotter "Blotters"). 

I submitted an open records request on 6/1/2020 for arrest information by demographic. 
`<--insert screenshot of OG request here-->`

I received my first response on 6/10/2020 requesting clarification. 

On 6/29/2020, the records supervisor wrote, "The arrest list that I upload onto the City website are done daily and removed after a week." She requested I contact her to directly because she did not understand my request. 

As of July 1st, I still do not have data for this project so this document will continue to grow with ideas and planning. 

*QUESTIONS I STILL NEED TO ANSWER*
---
* how to account for SM demographics in my black arrest rate (should the results be adjusted to account for population?) 
* is there another reason a particular officer would over arrest a black person? (ie: scheduling? if they work more than their counterparts, area they are assigned, etc.) 

*HOW/WHERE*
---

* kaggle for coding
* this repository for file management
* potential visualization software in future for dashboards
* API to future data releases 
* invidents/arrests/convictions for full scope 

*UPDATES*
---

* Requested data from SMPD via format Open Records Request ~June 1
* Received compiled media arrest data from SMPD ~July 9/10


**PLEASE FEEL FREE TO USE THIS DATA FOR YOUR OWN ANALYSIS**

*GOAL*
---
https://www.popsci.com/story/science/implicit-bias-training-police-racism-black-lives-matter/

