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
*The problem*: With the second wave of COVID-19 cases expected to arrive any day now, UHM needs to be prepared to handle an increase in positive COVID-19 cases on campus while still remaining operational. To maximize safety, UHM had launched a user-friendly and simple check-in app called LumiSight UH for students, faculty, and staff to fill out in order to get clearance to come to campus. However, there currently does not exist an app to see the COVID hotspots on campus or for people who get tested positive to get clearance to come back to campus. 

*The solution*: The Get Back To Campus app enables you to login to your phone and determine: 
* See a list of highly frequented locations on campus from people who ended up testing positive
* Self report your positive covid test, upload documentation, report your schedule 
* Upload your medical clearance documents if you tested positive
* See the progress (accepted, received, in review, rejected) of your medical clearance documents if you tested positive and want to get back to campus

### Approach:

This app will basically be a database for Covid cases on campus,as well as a tracking system of sorts. Students who have tested positive can self report with documentation, as well as establish what classes they were going to, and what areas they frequented. There will also be a section of the app that allows students to upload documentation clearing them to return to school, which will show the students pending status. The main landing page of the app will be contain general information, as well as have listed certified medical testing centers that are accepted by UH manoa.

Possible Pages include:
* A Landing page on how to maintain a clean educational environment, contact information if one feels sick,and accepted testing centers, and highly frequented places on campus of people who tested positive
* Upload page form where students can self report their positive COVID test and give documentation and enter detailed information on their whereabouts on campus
* A status page where students can upload clearance documentation and view their status (accepted, received, in review, rejected)
* A user profile page
* Admin home page to see database of all COVID cases reported on campus and their medical clearance forms progress

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
* Notify students when and where "hot zones" have developed on campus via e-mail, twitter, or SMS
