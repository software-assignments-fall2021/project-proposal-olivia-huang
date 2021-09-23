Team Members: Olivia Huang and Frank Weng

# Project title
Q: Give your project a nice title.

# What and why?
The software system that we would like to build this semester is an app that tracks NYC subways in real time and alerts the user when to leave in order to catch their subway on time. Subways are often delayed and while there are MTA apps that allow one to see subway schedules, we would like to facilitate the process of calculating the correct time to depart in order not to be late to one's destination.

# For whom?
This software will be for anyone that uses the NYC subway system regularly.

# How?
The software will serve as a route planning system that integrates realtime bus and subway schedules provided by the MTA with a calculated average walking pace. The user can also specify custom alarm preferences on how many minutes "X" they'd like to be alerted prior to leaving, in order to arrive at a specific destination by a specific time. The system will of course take into consideration delays, and possibly also weather conditions and other emergencies that may alter the estimated time of arrival to a destination. To explain the process of how a user would use the app:

1) Define Starting Point & Destination Point - The user defines a specific starting location and a specific destination, as well as a time for when they wish to arrive at their destination. The user will be able to save these starting location - destination - time presets for repeated use. The software will request access to the user's Current Location, in which the user can opt into, for optimized location and tracking accuracy. 

2) Calculate Walking Speed - If the user enables the software to access their Current Location, there will be a feature that can track each user's walking speed idiosyncratically, if the software is left open for the duration of the commute. As walking-speed data is accumilated after the gradual use of the software, it will be able to apply the user's unique walking-speed for more precise calculations. If the user does not allow access to Current Location, the software will alternatively ask the user if they are a "slow", "average", or "fast" paced walker, and use a statically set "mph" to calculate the user's walking pace. 

3) Importing real-time MTA data - The software will access New York City's real-time subway, train, and alert data via the MTA's API gateway. The data for train and bus schedules will be displayed in a designated screen. It will additionally be utilized for calculating the alert on to leave by, which will be pushed to the user's device.

4) During the commute - While the user is on their commute, the software will display a mapping system that features the most efficient route to take, as well as directions

5) Commute Log - Users will be able to access their commute log, displaying past trips and releavant commute history

# Scope
The software will be using multiple third party resources, such as the MTA API and requesting permissions to the user's third party data. It will be importing that data and manipulating it, to calculate the walking-speed and time to leave. If the project is too easy, we can additionally implement a mapping system functionality that compares the best trains/busses to take, while considering transfers at stations. 
