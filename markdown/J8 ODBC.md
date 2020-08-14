# Add ODBC to Java 8

- Copy `JdbcOdbc.dll` at `notes/uploads` to `C:\Program Files\Java\jdk1.8.0_66\jre\bin`

- Copy `jdbc.jar` at `notes/uploads` to `C:\Program Files\Java\jdk1.8.0_66\jre\lib\ext` 

- System variables > Add to `Class path` with following string:

  `. ; C:\Program Files\Java\jdk1.8.0_66\jre\lib\ext`

**Important**: Make sure your JRE System Library in Eclipse is `Java SE-1.8 (jdk1.8.0-66)`