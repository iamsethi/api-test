HelloFresh Web-Test
=====


##### Configurator:

* Run tests 

```java
mvn clean test
```

##### Logging [Sample Output](https://web-test-hellofresh.s3-eu-west-1.amazonaws.com/application.html)

* Using log4j for logging 
* log4j.properties file under "src/test/resources"
* Sample output will be under "log" folder
* Output will be on Console,File.txt and .html file


##### Taking screenshot on failed tests [Sample Output](https://web-test-hellofresh.s3-eu-west-1.amazonaws.com/ExtentReportResults_Failed_Sample.html)
* Screenshot will get attached in report if any test case fails  


##### Generation human readable report e.g [Sample Output](https://web-test-hellofresh.s3-eu-west-1.amazonaws.com/ExtentReportResults.html)
* Integrated framework with Extent Reports
* Ouput report has two tabs at left top corner to view the report in sequential format or graph format






















