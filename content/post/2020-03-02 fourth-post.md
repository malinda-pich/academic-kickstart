---
date: 2020-01-20
title: Devlog 4 - Meeting for Next Steps 
summary: Understanding out how to digitize data and create an API

# optional header image (relative to 'static/img/' folder).
header:
  caption: ""
  image: ""
tags:
  - devlog
  - API
  - news
---
**Meeting with Professor Graham for Next Steps** 

On March 2nd, our group set an appointment to meet with Professor Graham to ensure that we were moving in the right direction with regards to digitizing our collection. Before this meeting, we had gone as a group to the Nature Museum and taken pictures of the information corresponding to one site: Place Royale Latrine. At the meeting on March 2nd we devised how the tasks were going to be split up. I took some notes during the meeting outlining the procedures we should take to build our API.

At first we were confused as to what to do with the pictures that were taken. Professor Graham walked us through by drawing this diagram in order to help us process how our final product would take form. This helped us to understand how to group the information into an excel spreadsheet once the information in the photographs after being transcribed and spit out as a text file.  

{{< figure library="true" src="20200302_1106190.jpg" title="Thinking through a data model" lightbox="true" >}}

From this meeting, and from what I understood, this is the process that we should be taking to ultimately create our API.
1. Take photos
2. Put them in folder
3. Type command
4. Feeds folder to AZURE
5. AZURE spits out results
6. Take text file that results and clean it up and put it in excel spreadsheet
7. Convert CSV file into SQI file
8. Publish database 
