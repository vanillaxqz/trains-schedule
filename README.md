# Trains Schedule

## Description

Client-Server CLI app in C/C++ to check the trains timetable for the current day, see arrivals/departures in the next hour, signal a train being late with real-time updates to all clients.

The server is pre-threaded, meaning you will give it a number of threads to create and manage on start-up.
It will then check for a backup xml or open the default one ("timetable.xml") and then create the threadpool
that will handle the clients.
