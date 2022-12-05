# Events Creation and Management guidelines
## „Events im Open Data Hub”
The first thing to do is to go on the (databrowser)[insert link]
(insert image homepage and specific interface)
-> show edit interface
![image](https://user-images.githubusercontent.com/101118017/205593258-9d809208-a930-416c-9324-632aef9a2de8.png)
![image](https://user-images.githubusercontent.com/101118017/205593295-35839a0e-d1a0-4df6-b2b7-82dba051af5a.png)

### workflow
![image](https://user-images.githubusercontent.com/101118017/205593353-8ae09249-0fe3-45fa-a322-eb59a06cd788.png)

The **event manager** and, if necessary, the **community manager** of NOI AG enter the events into the Open Data Hub. In addition, events via a
Interface adopted from the **Meeting Management** program.

WHAT IS THE ADDITIONAL INTERFACE? IS IT RELEVANT TO THE WORKFLOW?

#### Mandatory fields
Each event must have a title, a short description and an image. If these minimum criteria are not met, it will not appear on the noi.bz.it site, nor on the
NOI Community App played out.

By default, the images should be uploaded as jpg or png in landscape format, with a max size of 4MB and in the format of 1170x780px.

#### The active flags
There are three active flags in total:
- **Active** stands for the visualization of the event on today.noi.bz.it.
- **noi.bz.it Active** represents the visualization on the noi.bz.it website.
- **NOI-Community App Active** stands for the visualization on the NOI-Community App.

The flags are set manually when entering the events. 
The event manager decides which event is played on the website. Usually it's for all of the Events that NOI Techpark is the organizer of, that take place here and are open to the public. Exceptionally, events from external hosts can also be visualized. In this case, the appropriate box must be selected. Which events on the app
are played out, however, is decided by the Community Manager. The criteria is the opportunity for community members to take part in the event.

#### Additional fields
**WEB PAGE** <br>
If registration is required, then the corresponding link under "Web Page" must be used.<br>
**FILTERS** <br>
There are two filters: Technology Field and Tagging Field.
- The corresponding **technology field** can be selected for Technology Field
(Green, Food, Digital or Automotive/Automation). This filter function is based on the
App taken over and displayed on the website. If the event falls in none of the
mentioned technology fields, this field remains empty.
- The **tagging field** specifies the type/series of an event. For the site, a
Tagging Field must be selected, but does not have to. The selected term will appear as
supercategory displayed. On the app, on the other hand, there must always be a difference between "Public" and
"NOI Community" must be selected, because these two filter functions are
taken directly and are highly relevant to the community.

![image](https://user-images.githubusercontent.com/101118017/205593964-97b190ae-0d07-4017-9831-d7f9757fa2fc.png)


### Rooms and time management
Particular attention is paid when entering the time period of an event.

#### one day events

Events that extend over a maximum of one day are given a start and end date
entered and thus visualized on all channels. If the total time of an event
incl. construction and dismantling work differs from the official times of the event, e.g.
starts an hour earlier and ends half an hour later, then you have to make for it
a separate room can be booked with the corresponding time and a
Comments "x". Comment "x" means that the room is booked internally in the system,
but does not appear as booked on the channels. makes this possible
Optimizeddates parameter. If this parameter is set to "optimizedates=true"
passed, additional checks are made by the endpoint: All
Room bookings with comment "x" are filtered out and it is filtered out again
checks whether the start and end date of the event match the start and end date of the
rooms match. If there is no match, the time is taken from the system
adjusted automatically. Here is an example: An event has the start date of November 1st. at 9:00 a.m., because the hall has to be made available beforehand. The first room (without
Comment "x") is only booked from 10:00 a.m., which means that the event
officially begins at 10:00 a.m. The start time is set with the "optimizedates" parameter
automatically set to 10:00.

WHERE SHOULD YOU PUT THE COMMENT 'X' AND SET THE PARAMETER TO TRUE

#### multiple day events

Events that extend over several days can be entered over several days
be, e.g. from 1.11.-3.11. from 9.00 a.m. to 4.00 p.m. In the details, however, a
separate room can be created for each day, bswp. Day 1 – room booking 1.11. from
9:00 a.m. - 5:00 p.m.; Day 2 – room booking 2.11. from 9.00 a.m. to 5.00 p.m.; Day 3 – Room booking
3.11. from 10.00 a.m. to 4.00 p.m. This guarantees that the participants have the exact times
find for each event day. 

The channel today.noi.bz.it shows the events
room-based, website and app on the other hand event-based. If an event over
If there is more than one day, only the date from will appear in the event tile on the website and app
to are displayed, in the detailed view, however, the individual days are included
respective start and end time (the times of the rooms are displayed here
taken, excluding those with comment "x", just like on today.noi.bz.it).

(insert image of example)

### Technical point of view

THE ENDPOINT
THE CREATION OF AN EVENT 
THE MANAGEMENT / EDIT
ROOM AND TIME MANAGEMENT
- PARAMAETER
- COMMENT X
