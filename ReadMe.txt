Entire framework is developed using BDD approach
API and Web UI tests are using the same framework
Used Java 8 Lambda expressions at Confirmation.java class
Webdriver class is designed using singleton design pattern. if more time has given instead of hardcoding chromedriver.exe path, it could have downloaded over run time using DriverManager API.
webElementBase Class in common package contains most of the common wrappers that make code more reusable and reduces duplicate code
In WebElementBase class, clickElement method take cares automatically for possible errors that application may face.
API part can be written in a better way if POJO classes can be introduced but owing to time contsraint couldnt do.
Test runner classes are in runner package, separtae for UI and Rest
