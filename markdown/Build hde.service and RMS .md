Build hde.service and RMS

- Build hde.service first
  - Import missing dependencies, Mr Huy has sent via chat.
  - Right click on module > Maven > Update Project [Alt + F5]
  - No-svn: edit script.bat, -DnewVersion=2.1.0
  - Maven build... > life cycle phase: install
- RMS build:
  - Edit maven plugin install version to newest.
  - Add dependencies: fix error package not existed.

```xml
<dependency>
    <groupId>org.json</groupId>
    <artifactId>json</artifactId>
    <version>20200518</version>
</dependency>
<!-- https://mvnrepository.com/artifact/org.apache.httpcomponents/httpcore -->
<dependency>
    <groupId>org.apache.httpcomponents</groupId>
    <artifactId>httpcore</artifactId>
    <version>4.4.13</version>
</dependency>
<!-- https://mvnrepository.com/artifact/org.apache.httpcomponents/httpclient -->
<dependency>
    <groupId>org.apache.httpcomponents</groupId>
    <artifactId>httpclient</artifactId>
    <version>4.5.12</version>
</dependency>
<!-- https://mvnrepository.com/artifact/it.sauronsoftware.cron4j/cron4j -->
<dependency>
    <groupId>it.sauronsoftware.cron4j</groupId>
    <artifactId>cron4j</artifactId>
    <version>2.2.5</version>
</dependency>
```

- Switching between J7, J8: Choose Project > JRE System Library:
  - Switch J7, J8 from drop down list.
  -  Environments... : to add new java home
- After editing pom file, hit Save, workplace save automatically