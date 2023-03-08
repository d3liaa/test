# Events Creation and Management guidelines
## NOIEvents in the Open Data Hub
The first thing to do is to go on the [databrowser's NOIEvents page](https://databrowser.opendatahub.testingmachine.eu/dataset/table/tourism/v1/EventShort)

This is the page for the NOI Events. To be able to edit events and add records you will have to login first.
![SS_1_Login ](https://user-images.githubusercontent.com/101118017/223667128-db4e61f1-0828-4130-abc3-80460b87e12f.png)

Then to add a record you can click the button on the top left, or to edit an already existing record you can click on the button with the pen.
![SS_2_add_record_button](https://user-images.githubusercontent.com/101118017/223667646-f406ceb4-1871-4a43-b3c1-0115c961ad12.png)

<!-- ![image](https://user-images.githubusercontent.com/101118017/205593258-9d809208-a930-416c-9324-632aef9a2de8.png)
![image](https://user-images.githubusercontent.com/101118017/205593295-35839a0e-d1a0-4df6-b2b7-82dba051af5a.png) -->

### Creating or Editing a record
After clicking on the add records button this page will open.
![SS_3_add_record_main_data_view](https://user-images.githubusercontent.com/101118017/223690202-b5ea8a97-2587-460a-bbbf-62b3a86aa7ba.png)
There are multiple sections: Main Data, Event details, Images, Files, License.<br>
In the Main data you can insert: Title, Description, the organizer, the active flags and other info through the toggles.<br>
In the Event details you can insert: Web and video urls, dates, location, rooms and the filters.

Some attributes are mandatory.

#### Mandatory fields
Each event must have a title, a short description and an image. If these minimum criteria are not met, it will not appear on the noi.bz.it site, nor on the NOI Community App.

By default, the images should be uploaded as jpg or png in landscape format, with a max size of 4MB and in the format of 1170x780px.

#### The active flags
There are three active flags in total:
- **Active** stands for the visualization of the event on today.noi.bz.it.
- **noi.bz.it Active** represents the visualization on the noi.bz.it website.
- **NOI-Community App Active** stands for the visualization on the NOI-Community App.

The flags are set manually when entering the events in the Main data section. 
The event manager decides which event is played on the website. Usually it's for all of the Events that NOI Techpark is the organizer of, that take place here and are open to the public. Exceptionally, events from external hosts can also be visualized. In this case, the appropriate box must be selected. Which events on the app
are played out, however, is decided by the Community Manager. The criteria is the opportunity for community members to take part in the event.

#### Additional fields
**Web page** <br>
If registration is required, then the corresponding link under "Web Page" must be used.<br>
**Filters** <br>
There are two filters: Technology Field and Tagging Field.
- The corresponding **technology field** can be selected for Technology Field
(Green, Food, Digital or Automotive/Automation). This filter function is based on the
App taken over and displayed on the website. If the event falls in none of the
mentioned technology fields, this field remains empty.
- The **tagging field** specifies the type/series of an event. For the site, a
Tagging Field must be selected, but does not have to. The selected term will appear as
supercategory displayed. On the app, on the other hand, there must always be a difference between "Public" and "NOI Community" must be selected, because these two filter functions are taken directly and are highly relevant to the community.

![image](https://user-images.githubusercontent.com/101118017/205593964-97b190ae-0d07-4017-9831-d7f9757fa2fc.png)

### Rooms and time management
To add a room you should firstly navigate to the event detail section, and then click on the last button and the table with the rooms will show.
![SS_4_Room_Mangement](https://user-images.githubusercontent.com/101118017/223693449-d92b7b73-8751-45d5-a523-6e2eb035be8c.png)

After, to actually add information and rooms you will have to click on the button with the pen.
![SS_5](https://user-images.githubusercontent.com/101118017/223693744-0deda6de-10a6-486e-9079-7fdf8d8fadfa.png)

Finally, the view for adding the info for the room will open.
![SS_6](https://user-images.githubusercontent.com/101118017/223694329-2c024047-f1d5-49b4-a891-a066b2cb018e.png)

> Particular attention is paid when entering the time period of an event.

#### One day events

Events that extend over a maximum of one day are entered with start and end dates and thus visualized on all channels. If the total time of an event, including set-up and dismantling work, differs from the official times of the event, e.g. starts an hour earlier and ends half an hour later, then a separate room must be booked for this with the corresponding time and a comment "x". Comment "x" means that the room is booked internally in the system, but is not displayed as booked on the channels.

#### Multiple day events

Events that extend over several days can be entered for several days, e.g. from 1.11.-3.11. from 9.00-16.00 hrs. In the details, however, a separate room must then be created for each day.<br>
For example:<br>
Day 1 - room booking 1.11. from 9.00-17.00; <br>
Day 2 - room booking 2.11. from 9.00-17.00; <br>
Day 3 - room booking 3.11. from 10.00-16.00. <br>
This guarantees that participants will find the exact times for each day of the event. <br>
The today.noi.bz.it channel displays events based on rooms, while the website and app display events based on events. If an event takes place over several days, only the date from to is displayed in the event tile on the website and app, while the detailed view lists the individual days including the respective start and end times (here, the times of the rooms are used for display, excluding those with comment "x", just as on today.noi.bz.it).
