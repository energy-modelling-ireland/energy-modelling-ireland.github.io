---
title: "How to create a BER County Map Dashboard in Tableau"
author: Jason McGuire
date: 2021-07-15
categories:
  - blog
tags:
  - Tableau
  - Dashboard
  - Mapping
---

1.	Download the free version of [Tableau Public](https://public.tableau.com/en-us/s/) or subsciption-based [Tableau Desktop](https://www.tableau.com/en-gb/trial/tableau-software)

> All of the following steps should be possible on the free version of Tableau Public

2.	Download a zip file of the [BER Public Database](https://ndber.seai.ie/BERResearchTool/ber/search.aspx)

3.	Unzip file ( ~ 1 Gb file size )

4.	Open Tableau, on the left pane under Connect to a file, click text file, now find the unzipped BER file and click open.

![TableauStep4.png](/assets/images/2021-07-15-how-to-create-a-ber-county-map-dashboard-in-tableau/TableauStep4.png)

5.	Click Update in Tableau and file will go into Tableau. Filtering the data is recommend, this can be done on the top right corner of the Data Source tab !

![TableauStep5.png](/assets/images/2021-07-15-how-to-create-a-ber-county-map-dashboard-in-tableau/TableauStep5.png)

6.	In Sheet 1 or any new worksheet, find "CountyName" ( search function available ),drag and drop this onto middle of screen.

![TableauStep6.png](/assets/images/2021-07-15-how-to-create-a-ber-county-map-dashboard-in-tableau/TableauStep6.png)

7.	There will be errors, to remove errors right Click CountyName and select Geographic role , then select State/Province.

![TableauStep7.png](/assets/images/2021-07-15-how-to-create-a-ber-county-map-dashboard-in-tableau/TableauStep7.png)
  
8.	There will be some errors left, to remove the remaining errors, click on the bottom right of the map click on the errors and select edit location ( or right click on Map and select edit location ). Then map the BER area name ( Dublin Postcode, City or County ) to the Tableau recognized county. Once complete all errors disappear.

![TableauStep8.png](/assets/images/2021-07-15-how-to-create-a-ber-county-map-dashboard-in-tableau/TableauStep8.png)

9.	On the top right of the screen select Show Me and then select Maps.

![TableauStep9.png](/assets/images/2021-07-15-how-to-create-a-ber-county-map-dashboard-in-tableau/TableauStep9.png)

10.	Now the Map is complete and all the data is ready to be explored, An example below selects the BER rating ( kWh/m2/yr) drags and drops to color under marks and then right click and change from sum to average.

![TableauStep10.png](/assets/images/2021-07-15-how-to-create-a-ber-county-map-dashboard-in-tableau/TableauStep10.png)

11.	Result, showing county and average BER value for that county:

![TableauStep11.png](/assets/images/2021-07-15-how-to-create-a-ber-county-map-dashboard-in-tableau/TableauStep11.png)

12.	And now for the cherry on top! Edit color on top right, to make the differences stand out. Colored Result:

![TableauStep12.png](/assets/images/2021-07-15-how-to-create-a-ber-county-map-dashboard-in-tableau/TableauStep12.png)
