# Selenium Test Runner

It uses mvn test to run the selenium tests and generate test reports

## How to run

* To run every test
```
mvn test -DsuiteFolderValue= -DrundeckLoginUrl=${rundeckLoginUrl}

mvn test -DsuiteFolderValue= -DrundeckLoginUrl=http://rnavarro-ubuntu:4440/user/login
```


* To run single suite test
```
mvn test -DsuiteFolderValue=${folder} -DrundeckLoginUrl=${rundeckLoginUrl}

mvn test -DsuiteFolderValue=exampleExternalTest -DrundeckLoginUrl=http://rnavarro-ubuntu:4440/user/login
```

## Reports

Generated reports can be found in "target/surefire-reports"
