===========================================
About Selenium Project
===========================================

1) This Framework using Java 1.7, Selenium Standalone server-2.53, Maven and TestNG
2) Framework follows the concept of Page Object Modelling
3) user.properties file used to pass the data to the application
4) environment.properties file contains URL to be tested.
5) firefox_tests.xml(testNG file) contains information for two test cases.
6) Pdf report is generated using the class(JyperionListener). This file placed under src/test/java/tests/JyperionListener.java
7) The Pdf report generated after execution of firefox_tests.xml file
8) The report generated under /EdurekaSeleniumProject/Automation Test Report.pdf
9) Selenium Standalone server-2.53 needs to be started before execution using the command
	java -jar selenium-server-standalone-*.jar -port 4444
	
