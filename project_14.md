# Project 14
---
*The following steps and screenshot will show how project 14 was achieved. Poject 14 is mainly automation based using Ansible to deploy and set up resources*
  
  - Screenshot below show the following
  a. My repository
  b. Shows each of the config files needed to complete this tasks
<img src="./images1/Cloned Repo proj14.png" width="300" height="115">
- Screenshot2
<img src="./images1/Playbooks for apps proj14.png" width="300" height="115">
c. This shows the config for site.yml which the playbook pick to trigger an action when we un comment

- Screenshot3
<img src="./images1/Jenkins view proj 14.png" width="300" height="115">
d. This shows the repo created on Jenkins
   
- Screenshot4 
<img src="./images1/Jenkins file config pro14.png" width="300" height="115">

e. This shows different pipeline stages with the Jenkins file

*One of the task also stated we run a pipeline starting from the build- -> test -> package -> deploy*
- Screenshot5
  <img src="./images1/First-Test.png" width="450" height="100">
  f. This shows success from the build stage to cleanup

- Screenshot6
  <img src="./images1/Yaml-setup DB.png" width="450" height="500">
  g. Yaml configuration for DB setup

- Screenshot7
  <img src="./images1/Setting up DB with Ansible01.png" width="450" height="400">
  <img src="./images1/Seeting up DB with Ansible.png" width="450" height="400">
  h. Setting up the MSQL using Ansible.
- Screenshot8
  <img src="./images1/Ansibl:yum to install Artifact 14.png" width="450" height="400">
i. Yaml scritp for installing Artifactiory using Ansible

- Screenshot9
  <img src="./images1/Instal artifact with Ansible.png" width="450" height="400">
  <img src="./images1/Artifact UI.png" width="400" height="350">
  j. Showing artactory installing via ansible and Artifactory UI
- Screenshot10
<img src="./images1/Setting up Artifact from Jenkin.png" width="400" height="350">
<img src="./images1/Artifactory tested Ok from Jenkins.png" width="400" height="350">
k. Setting up artifactory from Jenkins and tested connection to be successful
- Screenshot11
<img src="./images1/Sonarqube-yaml.png" width="300" height="600">
<img src="./images1/Live sonarqueb.png" width="400" height="200">
l. Setting up sonarqube yaml file and UI showing burg sneeped

- Screenshot12
<img src="./images1/Start to finish pipeline.png" width="500" height="180">
m. This shows a successful pipeline from satrt to finish