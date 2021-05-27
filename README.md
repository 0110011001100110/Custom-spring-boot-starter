# Custom-spring-boot-starter
 #A custom spring-boot-starter for cross-cutting concerns using Spring AOP to secure web-services (soap&amp;rest)
 
 To use this custom spring-boot-starter, you should add it to your project's pom.xml as a dependecy. To do so, first of all use following command to build the starter and install its artifactId in your local maven repository:

`mvn clean install`

 Then add the built artifactId as a dependency in your project's pom.xml. As an example, I created a simple spring boot project that has a simple rest api named spring-rest-demo. In spring-rest-demo, I added the custom spring-boot-starter artifactId in pom.xml as a dependecy.
 
 To start learning about spring-boot-starters and writing your own custom spring-boot-starter, below links are so helpful as a start point:
 
 
https://www.baeldung.com/spring-boot-starters

https://www.baeldung.com/spring-boot-custom-starter

https://vishnu-g.medium.com/creating-custom-spring-boot-starter-to-solve-cross-cutting-concerns-d76f555beb64

