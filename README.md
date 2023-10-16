# How-to-deploy-a-war-file-in-Tomcat-
means: we have to do copied the sample.war file into the webapps directory of Tomcat, and I can access localhost:8080.
Introduction 
---------------------------------------------------------------------------------------------------------------------------------------------------------------------

Directories and Files
These are some of the key tomcat directories:
1) /bin - Startup, shutdown, and other scripts. 
The *.sh files (for Unix systems) are functional duplicates of the *.bat files (for Windows systems).
The bin directory with the setenv.sh, setenv.bat, and tomcat-juli.jar files. 
3) /conf - Configuration files and related DTDs.
   The most important file in here is server.xml.
   It is the main configuration file for the container.
    -conf/server.xml
    -conf/web.xml
5) /logs - Log files are here by default.
    The logs directory for instance-specific log files. 
6) /webapps - This is where your webapps go.
   The webapps directory for automatically loaded web applications. 
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
Unix daemon
