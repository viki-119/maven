# maven
关于maven的基本知识

初始化的pom文件

          <?xml version="1.0" encoding="UTF-8"?>
          <project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/maven-v4_0_0.xsd">  
            <modelVersion>4.0.0</modelVersion>
            <groupId>viki-test</groupId>
            <artifactId>ajax_test</artifactId>
            <packaging>jar</packaging>
            <version>1.0-SNAPSHOT</version>
            <name>ajax_test</name>
          </project>
          
          <project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
            xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/maven-v4_0_0.xsd">
            <modelVersion>4.0.0</modelVersion>
            <groupId>ysml</groupId>
            <artifactId>excel_drdc_maven</artifactId>
            <packaging>war</packaging>
            <version>0.0.1-SNAPSHOT</version>
            <name>excel_drdc_maven Maven Webapp</name>
            <url>http://maven.apache.org</url>
            <dependencies>
              <dependency>
                <groupId>junit</groupId>
                <artifactId>junit</artifactId>
                <version>3.8.1</version>
                <scope>test</scope>
              </dependency>
            </dependencies>
            <build>
              <finalName>excel_drdc_maven</finalName>
            </build>
          </project>
