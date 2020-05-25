## Interdisciplinary Health Data Competition
### Project Introduction
In the Spring of 2020, I had the opporunity to compete in the first University of Minnesota's [Interdisciplinary Health Data Competition.](https://carlsonschool.umn.edu/health-data-competition?fbclid=IwAR0foNkWPUXqJEMhUNhHtqJcPVDDV5edGg6ZUDWNARXOW20xh-t6JaP24r0) I recruited a team consisting of my classmates and medical students, and though my team did not advance to the final rounds, it was still a good learning experience. The data we had provided a good look into the world of pharmaceuticals and drug prescriptions.

Most of our work was done in Google Drive and Hangouts, and I'm writing this GitHub as a project retrospective. In this repository, I'll be talking through our project's process as we navigated through the project and our findings we used to make our recommendations. You can find the high level summary in our Final Presentation Powerpoint.


### Datasets and Data Cleaning
The data we used came from the Minnesota Department of Health's All Payer Claims Database. The data came in the form of two spreadsheets: Prescription Summary and Drug Detail. These two datasets contain fairly similar information, with both of them having information like number of prescriptions, cost to the user, amount paid by insurance and member, and the type of insurer that covered the prescription. The drug detail table broke this information down to the brand and labeler name, while the prescription dataset added demographic information: percentage of people in x age group, gender, and location type specifically.




### Initial Exploration
The dataset we had was fairly rich containing several thousand rows with a good mix of attributes we could start looking into. However, there were a couple issues that prevented us from applying some of the more advanced analytics topics that we were itching to try after we learned them in class. The main one is that the dataset only spans the 2 disconnected years: 2012 and 2016. Without a continuous dataset across the 4 years, there was little we could do in regards to time series and causal inference. It's nearly impossible to establish any types of trends or causal relationships with only 2 data points

So we started simple. The first thing we did was create as many graphs, charts, tables and views as we possibly could, hoping that we'd run into some kind of pattern into which we could perform a deeper dive. This method fortunately yielded some results in the form of this chart. 

(Insert Chart here)

We found that Cardiovascular Drugs contained a significant disparity in terms of prevalence and the amount of it covered by insurance.


(Summary Still in Progress, Please see Final Presentation Powerpoint)
