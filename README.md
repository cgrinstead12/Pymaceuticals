# Pymaceuticals

![alt text](https://github.com/cgrinstead12/Pymaceuticals/blob/master/Images/Laboratory.jpg)

**Assignment Description**
While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've since joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego, CA. Pymaceuticals specializes in drug-based, anti-cancer pharmaceuticals. In their most recent efforts, they've since begun screening for potential treatments to squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As their Chief Data Analyst, you've been given access to the complete data from their most recent animal study. In this study, 250 mice were treated through a variety of drug regimes over the course of 45 days. Their physiological responses were then monitored over the course of that time. Your objective is to analyze the data to show how four treatments (Capomulin, Infubinol, Ketapril, and Placebo) compare.

To do this you are tasked with:


Creating a scatter plot that shows how the tumor volume changes over time for each treatment.
Creating a scatter plot that shows how the number of metastatic (cancer spreading) sites changes over time for each treatment.
Creating a scatter plot that shows the number of mice still alive through the course of treatment (Survival Rate)
Creating a bar graph that compares the total % tumor volume change for each drug across the full 45 days.


As final considerations:


You must use the Pandas Library and the Jupyter Notebook.
You must use the Matplotlib library.
You must include a written description of three observable trends based on the data.
You must use proper labeling of your plots, including aspects like: Plot Titles, Axes Labels, Legend Labels, X and Y Axis Limits, etc.
Your scatter plots must include error bars. This will allow the company to account for variability between mice. You may want to look into pandas.DataFrame.sem for ideas on how to calculate this.
Remember when making your plots to consider aesthetics!


Your legends should not be overlaid on top of any data.
Your bar graph should indicate tumor growth as red and tumor reduction as green.
It should also include a label with the percentage change for each bar. You may want to consult this tutorial for relevant code snippets.

**Tumor Response to Treatment**

The initial analysis was narrowed down to the drug treaments Capomulin, Infubinol, Ketapril and a placebo. Gradually over time, each drug was tested for increases in tumor volume measured in (mm3). During the 45 day trial, the only drug to show a steady decrease in tumor volume was Capomulin, where the tumor volume decrease by about 8 mm3. The other two drugs, Infubinol and Ketapril, did not show any decrease in tumor volume and when compared to the placebo suggest they did not have any effect on the mice they were tested on.

![alt text](https://github.com/cgrinstead12/Pymaceuticals/blob/master/Images/TumorResonsetoTreatment.png)

**Metastic Spread During Treatment**

The drugs were then analyzed for metastic spread. The metastic sites identified during the trial show Capomulin as the only succcessful treament and the other two performing the same if not worse as the placebo. Capomulin's results also show a lower margin of error which indicates its ability to perform more consistently. 

![alt text](https://github.com/cgrinstead12/Pymaceuticals/blob/master/Images/Metastic%20Spread%20During%20Treatment.png)

**Survival During Treatment**

Each drug was administered to 25 mice over the trial which was previously stated of 45 days. The results indiciate that the only successful drug at preventing deaths was the drug Capomulin where only three mice did not survive until the end of the trial. The other drugs Infubinol and Ketapril performed much worse and roughly 10 mice did not survive until the end of the trial. 

![alt text](https://github.com/cgrinstead12/Pymaceuticals/blob/master/Images/Survival%20During%20Treatment.png)

**Change Over 45 Day Treatment**

The final analysis perform visualizes in a bar chart the volume percentage change over the 45 day trial. Again, the drug Capomulin performed signficantly better and helped reduce tumor volume by about 19%. The other two drugs and the placebo were unsuccessful at reducing tumor volume as tumor volumes in mice tested grew by about 50%. 

![alt text](https://github.com/cgrinstead12/Pymaceuticals/blob/master/Images/Tumor%20Change%20Over%2045%20Day%20Treatment.png)


