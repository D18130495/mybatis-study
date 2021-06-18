# mybatis

## Project structure and configuration
1. create maven
2. delete src folder
3. maven dependencies
### Maven dependencies
``` xml
    <dependencies>
        <dependency>
            <groupId>mysql</groupId>
            <artifactId>mysql-connector-java</artifactId>
            <version>5.1.47</version>
        </dependency>

        <dependency>
            <groupId>org.mybatis</groupId>
            <artifactId>mybatis</artifactId>
            <version>3.5.2</version>
        </dependency>

        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>4.12</version>
        </dependency>
    </dependencies>
```

## Login service
css clear cache problem
|situation|syntax|
|-----------|-----------|
|Before| href="${pageContext.request.contextPath}/css/style.css"|
|After|href="${pageContext.request.contextPath}/css/style.css?1"|

![An image](images/login.jpg)

## Logout service