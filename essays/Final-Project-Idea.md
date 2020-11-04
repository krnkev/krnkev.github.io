---
layout: essay
type: essay
title: "Final Project Idea"
image: images/javascripTB.jpg
# All dates must be YYYY-MM-DD format!
date: 2020-11-01
labels:
  - Software Engineering
  - Meteor
---
### Overview:
*The problem*: With the second wave of COVID-19 cases expected to arrive any day now, UHM needs to be prepared to handle an increase in positive COVID-19 cases on campus while still remaining operational. To maximize safety, UHM had launched a user-friendly and simple check-in app called LumiSight UH for students, faculty, and staff to fill out in order to get clearance to come to campus. However, there currently does not exist an app to see the COVID hotspots on campus, self report a positive covid test, or for people who get tested positive to get clearance to come back to campus. 

*The solution*: The Get Back To Campus app enables you to login to your phone and: 
* See a list of highly frequented locations on campus from people who ended up testing positive
* Self report your positive covid test, upload documentation, and report your schedule and areas frequented 
* Upload your medical clearance documents if you tested positive
* See the progress (accepted, received, in review, rejected) of your medical clearance documents if you tested positive and want to get back to campus

### Approach:

This app will basically be a database for COVID cases on campus, as well as a tracking system of sorts. Users who have tested positive can self report with documentation, as well as establish what classes they were going to, and what areas they frequented. There will also be a section of the app that allows users to upload documentation clearing them to return to school, which will show the status of the documents. The main landing page of the app will contain general information, list certified medical testing centers that are accepted by UHM, and list the highly frequented places on campus from those who tested positive.

Possible Pages include
* A Landing page on how to maintain a clean educational environment, contact information if one feels sick,and accepted testing centers, and highly frequented places on campus of people who tested positive
* "I tested positive" page where users can self report their positive COVID test, give documentation, and enter detailed information on their whereabouts on campus
* A "Get me back to campus" page where users can upload clearance documentation
* A "Check status of my medical clearance" page where the user can view the status (accepted, received, in review, rejected) of their forms
* A user profile page
* Admin home page to see database of all COVID cases reported on campus and edit the status of medical clearance forms 

### Use Case Ideas
* New user goes to landing page, logs in, gets home page, sets up profile
* Admin goes to landing page, logs in, gets home page, sees database of all people who tested positive and edits the progress of the medical clearance documents
* User goes to landing page, logs in, looks at list of covid hotspots on campus
* User goes to landing page, logs in, goes to “I tested positive” tab, uploads medical documentation of positive covid-test, self reports ones schedule and location 
* User goes to landing page, logs in, goes to “Get me back to campus” tab, uploads medical clearance documents
* User goes to landing page, logs in, goes to “Check status of my medical clearance” tab, checks the progress (accepted, received, in review, rejected) of the medical clearance documents

### Beyond the Basics:

After implementing the basic functionality, here are ideas for more advanced features:
* Have a map page, which shows a map of the "hot zones" on campus (places and buildings that have seen a surge in cases)
* Provide important news regarding Covid, and Covid cases in Oahu
* Notify users when and where "hot zones" have developed on campus via e-mail, twitter, or SMS
