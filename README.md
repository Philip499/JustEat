# Technical Test 
For the Given Feature use JUST EAT website to find restaurants

## PlatForm
By using Behaviour driven development on a Maven Project with Java, Selenium ,TestNG, Cucumber ,Gherkins Language  

### Prerequisites
Setup Java
Download and install the JDK from http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
Add "C:\Program Files\Java\jdk1.8.0_121\bin" to your 'PATH' variables
Add 'JAVA_HOME' to your environment variables ("C:\Program Files\Java\jdk1.8.0_121")
Setup Maven 
Either use the bundled one with IntelliJ or download from https://maven.apache.org/download.cgi
Add Selenium , TestNG and Cucumber dependencies             
        <dependency>              
            <groupId>org.seleniumhq.selenium</groupId>                              
            <artifactId>selenium-java</artifactId>                              
            <version>2.45.0</version>                               
        </dependency>             
        <dependency>              
            <groupId>org.testng</groupId>                               
            <artifactId>testng</artifactId>                             
            <version>6.8</version>                              
            <scope>test</scope>                                     
       </dependency>              
       <dependency>
            <groupId>info.cukes</groupId>
            <artifactId>cucumber-java</artifactId>
            <scope>test</scope>
            <version>1.0.11</version>
        </dependency>
        <dependency>
            <groupId>info.cukes</groupId>
            <artifactId>cucumber-jvm</artifactId>
            <version>1.0.11</version>
            <type>pom</type>
        </dependency>
        <dependency>
            <groupId>commons-io</groupId>
            <artifactId>commons-io</artifactId>
            <version>2.5</version>
            <scope>test</scope>
        </dependency>
        <dependency>
            <groupId>info.cukes</groupId>
            <artifactId>cucumber-java</artifactId>
            <version>1.0.11</version>
            <scope>compile</scope>
        </dependency>
        <dependency>
            <groupId>info.cukes</groupId>
            <artifactId>cucumber-java</artifactId>
            <version>1.0.11</version>
        </dependency>
     </dependencies>
     
     #### Environment Setup
     
     Once the Prerequisites setup is done , under the maven project in the Folder Structure src\main\java , Place JustEat.Java file
     
     ##### Running the Test
     
     Build and Run the test.
     
     ###### Notes:
     
     Update TextNG.xml : suite name , Test name and Class name
     Feature File : MyTest.Feature File explain the Feature and Scenarios under test using Gherkins Language.
      
        
