# Person-counter

  A project Which keeps track of count of people in public places,follows covid protocols,
reduces unnecessary wastage of electricity in public places by giving alerts through email
to registered person of authority whenever room is full or empty.
Arduino code for this project is in person_counter.ino

# Why our project?

-In many public places irrespective of occupancy of room,electrical appliances will often be working
-With the help of our project,concerned authority of room can know when the room is completely unoccupied and they can turn OFF the list of electrical appliances provided to them through mail.This really avoids the unnecessary wastage of electricity.
-In recent times,it’s necessary that a place won’t get overcrowded i.e.,it is necessary to maintain covid protocol in a public place and hence this is included in our project.
 when the room’s capacity exceeds the fixed limit,the authority of the place could know that

# Objective

To provide the following information to authority of a public place:
-When the room is completely unoccupied
-When the capacity exceeds the limit by covid protocol
-And allowing the people to know when they could enter the room

# Features

-When the visitors count is less than  capacity,red LED glows at entrance of room which indicates a person that he could enter the room
-When the visitors count exceeds capacity of room,a buzzer will be given alerting the people inside that room’s capacity is exceeded
-An email will be sent to the gmail address of concerned person of room when the room becomes empty
-An email will be sent to  gmail address of concerned person of room when the capacity of room exceeds limit
-Visitors count will always be plotted in a graph in ThingSpeak,OM2M
  
# Required Hardware:

-PIR Sensors(2)
-Buzzer
-LEDs
-ESP32
-Jumper wires
-Breadboard
