# TestNG Metrics Report

Creates HTML report based on testng-resutl.xml

[![HitCount](http://hits.dwyl.io/adiralashiva8/testng-metrics.svg)](http://hits.dwyl.io/adiralashiva8/testng-metrics)
![Github Releases (by Release)](https://img.shields.io/github/downloads/adiralashiva8/testng-metrics/v1.1/total.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)
![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![Open Source Love png1](https://badges.frapsoft.com/os/v1/open-source.png?v=103)

---
__TesntNG Metrics Overview__

 ![COPY FILES](https://s2.gifyu.com/images/dashboard_overview.gif)

---

  - __Sample Report__ [link](https://testng-metrics.netlify.com/)
  - Download `Metrics.java` from [here](https://github.com/adiralashiva8/testng-metrics/releases/download/v1.1/Metrics.java)

---

### Key Features

 - Dashboard view of execution results
 - Top 10 test performances
 - Sort and Search Results
 - Export Results
 - Generate email (.eml) with statisitics
 - No Installation or Code changes required

---

### How it Works:

1. Read testng-result.xml file using javax.xml.parsers.DocumentBuilder
2. Get Suite, Test Case , Status, Elapsed time and Error values
3. Convert data to html report using java.lang.StringBuilder

---

### How to use in Project:

1. Download `Metrics.java` from [here](https://github.com/adiralashiva8/testng-metrics/releases/download/v1.1/Metrics.java) and include downloaded file in project

2. Make required changes like logo, path to testng-report.xml
    > Modify logo
    >  - Line no. : 10 in file
    >  - ```String logo = "customlogo.jpg";```

    > Modify testng-report.xml path
    >  - Line no. : 19 in file
    >  - ```String path = System.getProperty("mycustompath");```

3. Execute Metrics.java file
    ```
    javac Metrics.java
    java Metrics
    ```

4. TestNG Metrics report __metric-timestamp.html__ file will be created in current folder

---

Thanks for using testng-metrics!

 - What is your opinion of this report?
 - What’s the feature I should add?

If you have any questions / suggestions / comments on the report, please feel free to reach me at

 - Email: <a href="mailto:adiralashiva8@gmail.com?Subject=Robotframework%20Metrics" target="_blank">`adiralashiva8@gmail.com`</a> 
 - LinkedIn: <a href="https://www.linkedin.com/in/shivaprasadadirala/" target="_blank">`shivaprasadadirala`</a>
 - Twitter: <a href="https://twitter.com/ShivaAdirala" target="_blank">`@ShivaAdirala`</a>
 - Mailing List (google group): <a href="https://groups.google.com/forum/embed/?place=forum/testng-metrics" target="_blank">`testng-metrics`</a>

---

*Credits:*

1. TestNG [link](https://testng.org/doc/index.html)
2. Stackoverflow [link](http://stackoverflow.com)
3. Google charts [link](https://developers.google.com/chart/)
4. DataTable [link](https://datatables.net/examples/basic_init/table_sorting.html)
5. Java [link](https://www.java.com)
6. Jquery | JavaScript [link](https://www.jqueryscript.net)
7. Bootstrap [link](http://getbootstrap.com/docs/4.1/examples/dashboard/)
8. Icons8 [link](https://icons8.com/)
9. FontAwesome [link](https://fontawesome.com)

---

Inspired from [robotframework-metrics](https://github.com/adiralashiva8/robotframework-metrics)

---
