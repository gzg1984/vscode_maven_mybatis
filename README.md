# Help
- use git@github.com:gzg1984/MyBatis-example.git to generate the database access code
# How To Test
http://localhost:8080/mybatis/user/showUser?id=22

# Tips
- .classpath is needed for this project to point out which classpath in spring-mvc.xml is used
- http://localhost:8080/mybatis/ shows Hello World!
- http://localhost:8080/mybatis/user/showUser?id=2
    - should show 306290364@qq.com
- update log4j will make EMPTY_BYTE_ARRAY problem. update log4j-api to solve it
- update spring version will make other severial configure chagne and should add new package in pom
- should add source of mapper.xml in pom to deploy it into war
- including properties varias name conflict problem , change varias to property_url
- change commons-dbcp to 1.4 to solve conflict between mysql and dbcp