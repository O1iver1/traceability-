# TraceLinkOntologyDBConnector
 An Java program designed to import tracelink ontology from RDF files (typically generated by fluent editor 2015) to database
## JDK Version
### Recommeded
 JDK1.8_301
### Other Version
 JDK1.8+ should also work with this project but any JDK below version 1.8 is not supported.
### Known Problem with JDK11+
 When program was stared several warning messages will pop up like the lines below

`WARNING: An illegal reflective access operation has occurred`

`WARNING: Illegal reflective access by com.google.inject.internal.cglib.core.$ReflectUtils$2 (file:/D:/env/apache-maven-3.8.1/repository/com/google/inject/guice/4.0/guice-4.0.jar) to method java.lang.ClassLoader.defineClass(java.lang.String,byte[],int,int,java.security.ProtectionDomain)`

`WARNING: Please consider reporting this to the maintainers of com.google.inject.internal.cglib.core.$ReflectUtils$2`

`WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations`

`WARNING: All illegal access operations will be denied in a future release`

In most cases, this will not affect the running of this program. However, just in case, it is recommended to use JDK1.8 instead
## Open sourse projects used in this project
OWLAPI 5.0.0        https://github.com/owlcs/owlapi

JUnit 4.13.2        https://github.com/junit-team/junit4

MySQL Connector/J   https://github.com/mysql/mysql-connector-j