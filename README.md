hms-sdp-app-development
=======================

hsenid moible solutions, sdp application development sdk with templates.

Dialog Ideamart -- Ussd static menu template application, Source Code

Following blog post is about ussd template based application written on top of Dialog ideamart api. 


Prerequisites
Ideamart Simulator
JDK 1.7
maven 3.+
Git client program


I have added a ussd static menu sample application to the git repository. To run the application follow the instructions. 
1. Update repository

If you havent already checkout the repository - Clone the project
git clone https://github.com/isuruanu/hms-sdp-app-development.git
otherwise just type
git pull from root of the downloaded source code

2. Go to 
hms-sdp-app-development/ussd/ussd-static-menu

3. Type the following command
mvn jetty:run

4. Start the simulator  and go to ussd tab
Set following value to Application Data -> URL 
http://0.0.0.0:8080/ussd-static-menu/mo-receiver

5. You can add your own ussd static menus, by editing the following file
hms-sdp-app-development/ussd/ussd-static-menu/src/main/resources/messages.properties

After setting up, will be able test via simulator.
