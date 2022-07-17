# JenkinsDemo2
Git+Maven+Jenkins Integration demo with parameters passed through Jenkins

Major Updates from Jenkins Demo project :
  1. Updated browser and url selection using system.getproperty() to get the data during runtime from POM.xml
  2. Updated the plugins section in POM.xml to get browser and url values in pom.xml during runtime from Jenkins.
  3. In Build section of the Jenkins we are giving the POM.xml path from github.
  
  Part 1 - Hardcoding of browser and url details in "Goals and options":
  4. In Goals and option we are hardcoding the browser and url detail like below:
     clean install -DxmlFiles=testng1.xml -Dbrowser=Chrome -Durl=https://www.google.com/

  Part 2 - Passing the values from the Parameters section and passing the keys in the goals and options
  5. clean install -DxmlFiles=$xmlFiles -Dbrowser=$browser -Durl=$url
