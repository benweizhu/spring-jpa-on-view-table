# spring-jpa-on-view-table

在读写操作分离的情况下，某些JPA级联读会让直行效率变慢，改用读取视图，可以让多次的级联SQL查询变成单次的
