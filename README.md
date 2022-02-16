### Configure Spring Boot Application with PostgreSQL Server
```
	spring.datasource.url=jdbc:postgresql://serverhostaddress:5432/databaseName
	spring.datasource.username=username
	spring.datasource.password=password
	spring.jpa.show-sql=true
	spring.jpa.generate-ddl=false
	spring.jpa.hibernate.ddl-auto=update
	spring.jpa.database-platform=org.hibernate.dialect.PostgreSQLDialect
	spring.jpa.properties.hibernate.temp.use_jdbc_metadata_defaults=true
	server.port=9090
```
### Configure Spring Boot Application with MySQL Community Server Database
```
	spring.datasource.url=jdbc:mysql://localhost:3306/relations?useSSL=false&allowPublicKeyRetrieval=true
	spring.datasource.username=root
	spring.datasource.password=Fahad@123
	spring.jpa.show-sql=true
# Hibernate Properties
#The SQL dialect makes Hibernate generate better SQL for the chosen database
	spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL5InnoDBDialect
# Hibernate ddl auto (create, create-drop, validate, update)
	spring.jpa.hibernate.ddl-auto=create-drop
	logging.level.org.hibernate.sql=DEBUG
	logging.level.org.hibernate.type=TRACE
	server.port=9090
```
### Configure Spring Boot Application with PhpMyAdmin database Server
```
	spring.datasource.url=jdbc:mysql://localhost:3306/springboottest?useUnicode=true&useJDBCCompliantTimezoneShif=true&useLegacyDatetimeCode=false&serverTimezone=UTC
	spring.datasource.username=root
	spring.datasource.password=
#add following properties if you are connected with thymeleaf template engine
	spring.thymeleaf.prefix=classpath:/templates/
	spring.thymeleaf.suffix=.html
	spring.thymeleaf.mode=HTML5
	spring.thymeleaf.encoding=UTF-8
	spring.thymeleaf.content-type=text/html
	spring.thymeleaf.cache=true
	server.port=9090
```
### Configure Spring Boot Application with SQL Server
```
	spring.datasource.url=jdbc:sqlserver://databaseHost;databaseName=databaseName
	spring.datasource.username=userName
	spring.datasource.password=databasePassword
	spring.datasource.driverClassName=com.microsoft.sqlserver.jdbc.SQLServerDriver
	spring.jpa.hibernate.dialect=org.hibernate.dialect.SQLServer2012Dialect
	spring.jpa.hibernate.naming.implicit-strategy=org.hibernate.boot.model.naming.ImplicitNamingStrategyLegacyJpaImpl
	spring.jpa.hibernate.naming.physical-strategy=org.hibernate.boot.model.naming.PhysicalNamingStrategyStandardImpl
	spring.jpa.show-sql=true
	spring.jpa.generate-ddl=false
	spring.jpa.hibernate.ddl-auto=update
	server.port=7981
```
### Add Following Properties if you are working with SMTP Server
```
	spring.mail.host=smtp.gmail.com
	spring.mail.port=587
	spring.mail.email.address=XXXXXXXXXX@gmail.com
	spring.mail.username=XXXXXXXXXX@gmail.com
	spring.mail.password=PASSWORD
	spring.mail.properties.mail.smtp.starttls.enable=true
	spring.mail.properties.mail.smtp.starttls.required=true
	spring.mail.properties.mail.smtp.auth=true
	spring.mail.properties.mail.smtp.ssl.enable=false
	spring.mail.properties.mail.smtp.ssl.trusted="*"
	spring.mail.properties.mail.smtp.connectiontimeout=5000
	spring.mail.properties.mail.smtp.timeout=5000
	spring.mail.properties.mail.smtp.writetimeout=5000
```

### Add Following Properties if you are working Files like Images or document.
```
	spring.servlet.multipart.enabled=true
# Threshold after which files are written to disk.
	spring.servlet.multipart.file-size-threshold=2KB
# Max file size.
	spring.servlet.multipart.max-file-size=200MB
# Max Request Size
	spring.servlet.multipart.max-request-size=215MB
```

