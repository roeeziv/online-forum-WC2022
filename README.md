# World Cup 2022 Forum Simulation - Roee Ziv
![alt](https://forums.macrumors.com/attachments/1bc8ec06-3efe-421d-bdc4-ab173d6766bb-jpeg.2112597)
## About Me
- As for the time this project was created, I am a 2nd year student at Ben Gurion University for Computer Science Degree.
- This project was created by me as a fun way to incorporate my hobbies into demonstrating my knowledge in network layers, mainly focusing on:
    * TCP/UDP protocols to online data transfer, including Reactor and Thread-Per-Client patterns.  
    * Serialization, Encoding and Decoding of packets/messages.
    * C++ and Java multi-threading
* Hope you enjoy reviewing it as much as i did making it!

## About The Project
- The project's *client's side* files needs to run on a Linux based computer (because of the c++ makefile) but are obviously open to view with any OS
* The project illustrates an online forum of 2022 WC games and events
* In the forum supported actions are:
  * Sign up, Login, and Logout as a user
  * subscribe to several topics and game channels.
  * send/receive updates on a topic to/from all subscribed members online
  * request a game summary by user (all game updates received by a certain user over a certain topic)
  * All requests being handled by a Reactor/TPC pattern based server with returned feedback about success or failure with handling a request.
