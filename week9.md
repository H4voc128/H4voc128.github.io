---
layout: post
title: Week 9
---

Entry: #072624

Alright! RLR and Jaywalking detection has been working for a bit. Many bugs have been squashed and the frame work has evolved a bit. Also, I want the coe to be nice and pretty in the case someone asks to see it. This week has been focused on querying the data collected by the framework created. My mentor asked on numerous occasions why there are "loose ends" in my frame work for they sacrifice process power but THIS is what I need them for... Oh I didn't say it yet my bad. These loose ends should allow me to seamlessly tie them to my chosen SQL database method (I chose SQLite for this project). Sending the data collected 1 dictionary row at a time holding: {'Frame':(frame#), 'RunTime':(Seconds passed),  'Obj_Id':(Object tracker ID), 'Obj_Class':(Object Type), 'Dashing':(RLR true or false), 'Jaywalking':(Jaywalking true or false)}. With these I can query SQLite on the amount of jaywalkers, or the tracking IDs of RLRs. We even experimented with more advanced queries, asking the start and end times of traffic violation detection. For example:


Obj_ID ||  Start_time  ||  End_time  ||<br /> 
''19'''||___05:40:15___||  05:40:23  ||<br />
''32___||___05:45:34___||  05:45:45  ||<br />
  etc...


We also have our final presentation to arrange, our technical paper to write and mor code bugs to squash. So far, our presentation and rough draft are about 80% complete. We need to run our code a bit more for conclusive results in accuracy, limitations, and potential evolutions. 

Adios!!!

[Back](./)
