#### complex-management

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.charlemaznable/complex-management/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.charlemaznable/complex-management/)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)

常用依赖管理POM.

##### Maven Dependency Management

```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.github.charlemaznable</groupId>
            <artifactId>complex-management</artifactId>
            <version>0.1.6</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```

##### Maven Dependency Management SNAPSHOT

```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.github.charlemaznable</groupId>
            <artifactId>complex-management</artifactId>
            <version>0.1.7-SNAPSHOT</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```
