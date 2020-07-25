# Sonarqube git jenkins maven
# Sonarqube with posrgres
https://techexpert.tips/sonarqube/sonarqube-installation-on-the-cloud-aws-ec2/
# Jenkins installation
https://dvops.cloud/2019/03/12/setup-jenkins-on-ubuntu-on-aws/
# Jenkins configuration
1) Download https://binaries.sonarsource.com/Distribution/sonar-scanner-cli/sonar-scanner-cli-4.4.0.2170-linux.zip into /opt
 2) apt-get install unzip
 3) cd /opt 
 4)unzip sonar-scanner-cli-4.4.0.2170-linux.zip 
 5) vi /opt/sonar-scanner-4.4.0.2170-linux/conf/sonar-scanner.properties
  add the below value.
  sonar.host.url=http://ec2-13-233-148-69.ap-south-1.compute.amazonaws.com:9000
6) Install sonarscanner plugin.
7) configure sonarscanner in globaltool configuaration.
8) configure sonarqube serverdetails in configure system.
9) Add ananlysis properties in job.
http://ec2-13-232-101-207.ap-south-1.compute.amazonaws.com:8080/
http://ec2-13-233-148-69.ap-south-1.compute.amazonaws.com:9000/
