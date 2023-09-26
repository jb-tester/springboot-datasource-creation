# Test project for DataSource generation from the SB configurations

different DB (SQL and NOSQL) are tested.
R2DBC connections are not considered in this project

each DB configuration is located in the specific application-*.properties file.

* Common: Placeholders: https://youtrack.jetbrains.com/issue/IDEA-333342 - application-placeholders.properties

* Empty values: https://youtrack.jetbrains.com/issue/IDEA-333368 - application-empty.properties

* H2: https://youtrack.jetbrains.com/issue/IDEA-332421 - application-h2.properties

* No action w/o `spring.datasource.driver-class-name` property: https://youtrack.jetbrains.com/issue/IDEA-333352 
sqlite, sybase, redshift, hsqldb, db2, derby

* Redis: https://youtrack.jetbrains.com/issue/IDEA-333370, https://youtrack.jetbrains.com/issue/IDEA-333379 - application-nosql-redis.properties

