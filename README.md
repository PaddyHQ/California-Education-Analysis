# California-School-Success

### Quick Reference

* ELA- English Language Arts (Subject taught in school comprising of phonics, reading, reading comprehension, spelling, writing)
* SBAC- Part of Smarter Balanced Summative Assessments, a standardized test based on Common Core State Standards
* FRL- Free and Reduced Lunch, part of a national initiative to provide meals to children of diverse socio-economic backgrounds

## Google Slide Presentation Draft

<https://docs.google.com/presentation/d/1F3YFfgeGMhiJDUFC4spqUofL4Du3HyZ9O8j708NnECc/edit?usp=sharing>

# California-School-Success

In our study, will be looking at the ~1027 school districts in California. We will be using two sources for our data.

* <https://www.cde.ca.gov/schooldirectory> a directory of all of the districts and schools in California with basic details about each.
  
* <https://www.cde.ca.gov/ds/ad/ceffingertipfacts.asp> this is our primary dataset. It gives relatively clean, detailed information about each district. California school systems capture robust data allowing for our data to be extracted and loaded easily. From this database, we are primarily looking at data from 2019. Data from 2019 represents the California school system pre-SARS-COV-2 outbreak. We believe there are many challenges to analyzing data from during the SARS-COV-2 pandemic. Therefore, data from this time period does not suit the goals for our analysis.

## ML Model Overview

Extracted District Data from cde.ca.gov, click [here](https://docs.google.com/spreadsheets/d/1L-_kRhlbA8bhKE99NOrL8IEGfn16WN_a/edit#gid=1976575567).

### Model 1: Linear Regression

**Overview:**

#### Topic: Educational research

Increasing the effectiveness of our public schools has long been a strong desire for tax payers, legislators, regulators, and community stakeholders. Effectively using collected tax revenue to increase our public school performance is a strong desire of all the citizenry.

Public education reform has been the subject of ongoing legislation for decades. In California, a push for a comprehensive system to hold schools and districts accountable for their students' performance began in earnest with the passing of the Public Schools Accountability Act (PSAA)  in 1999. Similarly, in 2001 federal law known as No Child Left Behind (NCLB).

In fall 2004, the California Department of Education introduced a yearly “Academic Progress Report” (APR) which combines state and federal reporting requirements.

As a group, we are deeply interested in what sorts of measurable data correlates with student success. If so, are any of those correlations predictive? Finally, what can we suggest in regards to re-structuring current districts or setting up successful ones in the future based on our findings.

**Research Question:**

* What is the association between per pupil spending and achievement, holding constant district size and %FRL?
* How is per pupil spending distributed across California school districts? By region? NorCal, SoCal, CV, etc.
* Option: How can we cluster districts based on:
  * %Free and Reduced Lunch?
  * Per pupil spending?
* How do school districts break down by size? / How can we classify district size in a way that makes sense? (What is big / medium / small?)

**Variables:**

* Outcome/target:

  * Smarter Balanced Summative Assessments (SBAC) scores (one for ELA and one for Math)
  * Smarter Balanced Summative Assessments (SBAC) scores (for both subjects, combined)

* Predictors/features:
  * Free/reduced lunch %
  * Per pupil spending
  * District size
  * Teacher pay (average)

### Initial Findings and Free and Reduced Lunch

Since per pupil spending is one of the most commonly-used indicators to analyze correlations between K-12 education spending and student learning. We began by exploring how per pupil spending in California might predict student achievement while holding constant district size and the percentage of students who qualify for free/reduced price lunch.

Although per pupil spending is an indicator of student success, a cursory look through visualizations of our data showed that other variables such as the percentage of students enrolled in "free and reduced lunch" (FRL), part of the National School Lunch Program (NSLP). The program NSLP was established under the National School Lunch Act, signed by President Harry Truman in 1946. More information on NSLP can be found [here](https://fns-prod.azureedge.net/sites/default/files/resource-files/NSLPFactSheet.pdf). The percentage of students in a given district receiving FRL can be looked as one indicator of the socio-economic status of that district.

### Indicators of Success and SBAC Testing

Smarter Balanced Summative Assessments or

## Tableau Visualizations

<https://public.tableau.com/app/profile/patrick.holmquist/viz/CaliforniaSuccessAnalysis/TeacherSalaryvsAchievement>

(cursory look through original dataset, created

* average teaching salary summary
* FRLP vs Achievement and FRLP heatmap
* Disadvantage % vs Achievement and heatmap
* Teacher to Student Ratio vs Achievement and heatmap

### Model 2: Clustering Algorithm

**Overview:**
We’d also like to create a classification system that is more substantive than the standard way of categorizing districts based on spending and family income, which is to split them into quartiles or quintiles.

**Research Question:**
How can we cluster districts based on district size and percentage FRL?

**Variables:**

* Free/reduced lunch %
* Per pupil spending

## Communication Protocols

* Primary communication on Slack group 9
* Sensitive communication on Slack private message group
* Exchanged phone numbers to be used as added layer of communication. Everyone agreed that text messaging would be an acceptable form of communication.
* Set up zoom for team meetings
* Meetings held regularly on class days, including office hours on Saturday mornings, and on agreed upon dates/times as needed.
