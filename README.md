=================================================================================================
Data Visualization for RSVPs made in meetup community using PubNub JavaScript API and Eon gio map
=================================================================================================

This is a simple application which displays RSVPs made for any event by members of meetup groups from all over the world. 

Meetup (https://www.meetup.com/) is a community where everyone posts their events and people who are interested can RSVP to those events and participate. Meet API provide stream of data of RSVPs which are made by their members to all their events. I collect those RSVPs and using PubNub JavaScript API and Eon gio maps, I publish them as dropped pins in the world map. 

When you click on a pin, the member who RSVP to the event, Event name and Event city is displayed in a pop-up.  

-----------------------------
Steps to run the application:
-----------------------------
1. Clone or download the application
2. Run the index.html file in any of the browser. (I have entered my publish key and subscribekey in the html page)


Note: 
Since for the test purpose I directly entered my publishkey and subscribekey in the github which is usually wrong. Always the keys should be private. 
