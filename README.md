
Steps jenkins in docker

step: 1 Download Docker from official docker website

step: 2  pull jenkins image

docker pull nginx jenkins/jenkins;lts

step: 3 run the jenkins image

docker run nginx

step: 4 install jenkins

step: 5 configure jenkins files

step: 6 create the initialadminpassword ,install suggested plugins and create admin user .

step: 7 create new pipeline job

-select New item
-select pipeline
-click ok

step: 8  configure jenkins file 

-select Git as SCM and enter the git hub repository url.

step: 9 click Build Now and monitor log

-click on Build Now and console output
