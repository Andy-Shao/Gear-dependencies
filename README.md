Gear version auto-manage for maven
==================================

Why you need it?
----------------
After Mar 27, 2018. All of Gear release was definned by a kind of version of Gear-dependencies.
If you use multi-Gear jar in your system, use this pom which can avoid mix-version of Gear family jars in you projection

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
