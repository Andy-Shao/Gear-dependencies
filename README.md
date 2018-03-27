Gear version auto-manage for maven
==================================

How to use it
-------------
Adding these in your maven pom.xml file
It can manage Gear version automaticly. You will do not worry about the Gear version control in the projection.
```xml
<dependencyManagement>
  <dependencies>
    <dependency>
      <groupId>com.github.Andy-Shao</groupId>
      <artifactId>Gear-dependencies</artifactId>
      <version>${your-version}</version>
      <type>pom</type>
      <scope>import</scope>
    </dependency>
  </dependencies>
</dependencyManagement>
```
