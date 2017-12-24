# Build project
```bash
mvn clean install
```

# If build failed with following error
# [ERROR] Failed to execute goal org.apache.maven.plugins:maven-compiler-plugin:3.3:compile (default-compile) on project g-code-editor: Fatal error compiling: invalid target release: 1.8 -> [Help 1]
# Then update your maven java version to java8
# Check maven java version
```bash
jingerbread:~ jingerbread$ mvn -version
Apache Maven 3.2.1 (ea8b2b07643dbb1b84b6d16e1f08391b666bc1e9; 2014-02-14T21:37:52+04:00)
Maven home: /usr/local/Cellar/maven/3.2.1/libexec
Java version: 1.7.0_51, vendor: Oracle Corporation
```

# Start 
```bash
java -jar target/g-code-editor.jar
```