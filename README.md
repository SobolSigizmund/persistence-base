persistence-base
================

### Tecnologies

A base for all your persistence projects, build in top of:

* EclipseLink and JPA2
* Google Guice
* MySQL
* Apache Maven

### Providing

* A MappedSuperclass with @Id and @Version
* A AbstractDao that provide CRUD operations out of the box
* A PersistenceInitializer and other helper classes for the Guice setup.

### How-to use

Just clone this repository, and modify it for your project, creating your beans and daos.
You may also need to hack:

* persistece.xml
* PersistenceModule.java

That's it. If you have any issues, feel free to inform here.
