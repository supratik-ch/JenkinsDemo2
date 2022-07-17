# JenkinsDemo2
Git+Maven+Jenkins Integration demo with parameters passed through Jenkins

Major Updates from Jenkins Demo project :
1. Updated browser and url selection using system.getproperty() to get the data during runtime from POM.xml
2. Updated the plugins section in POM.xml to get browser and url values in pom.xml during runtime from Jenkins.
3. In Build section of the Jenkins we are giving the POM.xml path from github. In Goal and option we are passing the browser and url details
