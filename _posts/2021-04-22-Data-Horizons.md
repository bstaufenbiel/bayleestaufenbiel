---
layout: post
title: Data Horizons
Date: 2021-04-22
---

**Data Horizons**

What potential does this data set have for future scholarship? 

The purpose of using the <em>Old Bailey Proceedings</em> was to investigate how women were treated as both defendants and witnesses in criminal trials. What type of knowledge did midwife expert witnesses possess, and was it surprising? Did female criminals get charged with infanticide because they actually committed the crime or for other reasons? The files that I downloaded from the OBP allowed me to answer these questions.

More questions can be asked using the OBP database. The 191 files that I downloaded are barely scraping the surface of what the archive has to offer. Per the files that I worked with, the use of computational methods allowed me to visualize the proceedings in a limited way by the categories that the developers chose to log the files. 

For example, the OBP API allows individuals to download XML files in batches of ten after sorting them by:  
- Keyword(s)	
- Defendant Gender	
- Offence Category	
- Offence Subcategory	
- Victim Gender	
- Verdict Category	
- Verdict Subcategory	
- Punishment Category	
- Punishment Subcategory	
- Date 

After parsing the XML files, I used Open Refine and Tableau to see the women accused of the crimes. An exciting result of tracking the locations is that all of the cases come from Greater London. The Old Bailey never tried any cases from outside of the area. This means that the quality of life was substantially different in the urban environment than in rural settings. It would be interesting to see court cases from less populated areas in the UK or other comparable countries in Europe. 

One issue with the OBP database is the limited number of XML files that can be downloaded in one batch. If downloading with the API, only ten cases can be downloaded. For a researcher trying to gather large amounts of data, it is tedious to have to download 10, 11, 12, or more zip files for ten cases just to begin processing data. The database setup does not allow for Automated Downloading using Wget, so that option is out as well. 

If someone wanted to view the original documents, they would have to do so one by one on the OBP website. The image scans are not great, which makes OCR difficult. 

The API and parsing using OXYGEN XML is the best method. 

The information that came from my computation of the court cases, the most interesting line of inquiry is the correspondence between the year and the number of guilty or innocent verdicts. As seen in the Verdict Visualization posts, the more guilty verdicts were handed out earlier in time. As Ted Underwood noted in <em> Distant Horizons </em> computational methods are not without error. I do not know if the year's events have a causal relationship with the court verdicts, but they are definitely correlated.

London in the late 1600s saw the Great Plague and the Fire of London. It makes sense that there would be increased infant mortality. In terms of midwife knowledge, the professionalization of obstetrics and gynaecology was occurring, making sense that the midwives were secondary witnesses to male surgeons, doctors, and others. 

I would be very interested in seeing court cases without the midwife tag involving homicide, murder, or other bodily harm and looking at the guilty vs. innocent outcomes. I believe that the closer the trials are to the end of the plague and other disasters, the more likely the result will be guilty. 

Though this project is not directly linked to my dissertation project, I believe that computational methods and the tools used to publish data sets on the OBP site or on my website are invaluable. The labor behind such computation must be appreciated and recognized while simultaneously data is evaluated for the domains of power embedded within mathematical and statistical information. 

As called for by Catherine D’Ignazio and Lauren Klein in <em>Data Feminism</em>, I hope to be a scholar that engages in these broader discussions about data science and continues to be interdisciplinary in my future research endeavors.