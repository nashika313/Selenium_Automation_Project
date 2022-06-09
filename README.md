# README Guide for Selenium_Automation_Project
>Developed by Nashika Sivakumar

**DESCRIPTION**
This project is used to automate certain tasks using selenium web driver.

Sample Rest Endpoint & results.
````
 1) 
 Request: http://localhost:8080/romannumeral?query?=10
 Response : 
        { 
            “input” : “1”, “output” : “X” 
        }
        
 2)
 Request : http://localhost:8080/romannumeral?min=1&max=3
 Response: 
        {
            “conversions”:[
                            { “input” : “1”, “output” : “I” },
                            { “input” : “2”, “output” : “II” },
                            { “input” : “3”, “output” : “III” }
                          ]
         }
    
    
````

##PROJECT PRE-REQUISTES

Based on the operating System, download and install the following softwares

* Java 1.8 or greater (https://www.java.com/en/download/)
* Intellji (https://www.jetbrains.com/idea/download/#section=mac)
* maven 3 or greater (https://maven.apache.org/download.cgi)
* git (https://git-scm.com/downloads)*
* Docker
* Following ports are used by different microservices from this application.Please make sure these port are NOT used by other processes.
* **"8080" , "5000" , "9600" , "9200", "9300", "5601"**

**Set Class path for these softwares and verify each of the commands are successfull**
````
java -version
mvn -v
git --version
```` 


### Testing


#### Technologies Used
* Java
* Maven
* Selenium

