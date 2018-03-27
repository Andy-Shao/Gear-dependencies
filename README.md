Gear version auto-manage for maven
==================================

How to use it
-------------
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
