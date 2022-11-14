This mirrors an enterprise web based application I worked on. 
Build performed using the maven plugin on jenkins after pulling source code and dependencies from Github.
Several builds are done and scheduled on Jenkins, after which it is sent to Sonarqube for code coverage tests.
Backup is done on Nexus and deployment on Apache Tomcat 9
