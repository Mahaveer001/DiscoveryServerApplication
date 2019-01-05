#DiscoveryServerApplication
eureka server url : http://localhost:8761/
eureka service url: localhost:8091/UserDetails/listAll
eureka service client url :localhost:8092/listAll

eureka service client calls >>eureka service which fetches data from ms db
both eureka service and eureka service client are registered on eureka server.