#Liquibase Practice

[LiquiBase](http://www.liquibase.org/index.html) is a migration framework for Java.

The great thing about liquid base is that its migrations will work for any supported SQL database. [support list](http://www.liquibase.org/databases.html)

###To Run
Go into project file and run mvn spring-boot:run

You can see the tables created and play with them by going to <localhost:8080/h2-console> the db url should be the default url but just in case the db is: 'jdbc:h2:mem:testdb'