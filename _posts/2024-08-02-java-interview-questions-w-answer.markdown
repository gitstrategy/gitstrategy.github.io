---
layout: post
title:  "Java Interview Questions with Answer"
date:   2024-08-02 14:07:00 -0400
categories: [programming,java]
---
## Interview Questions and Answers

### Common Interview Questions for Java Developer

#### Core Java
1. What is Java?
    * Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible.
2. What are the main features of Java?
    * Object-oriented, Platform-independent, Simple, Secure, Portable, Robust, Multithreaded, Distributed, Dynamic.
3. Explain the concept of OOPs.
    * Object-Oriented Programming is a paradigm that uses "objects" to design applications and computer programs. Key concepts include Abstraction, Encapsulation, Inheritance, and Polymorphism.
4. What is the difference between JDK, JRE, and JVM?
    * JDK (Java Development Kit) is a software development kit for Java.
    * JRE (Java Runtime Environment) is used to run Java applications.
    * JVM (Java Virtual Machine) is a part of JRE which executes Java bytecode.
5. What is the purpose of the main() method in Java?
    * The main() method serves as the entry point for Java applications. It is where the program begins execution.
6. What is a Class and an Object?
    * A class is a blueprint for creating objects. An object is an instance of a class.
7. What is inheritance in Java?
    * Inheritance is a mechanism wherein a new class is derived from an existing class.
8. Explain method overloading and method overriding.
    * Overloading: Same method name with different parameters.
    * Overriding: Redefining a method in a subclass that already exists in the parent class.
9. What is the difference between abstract class and interface?
    * An abstract class can have both abstract and concrete methods. An interface can only have abstract methods (prior to Java 8).
10. What is encapsulation?
    * Encapsulation is the wrapping of data (variables) and code (methods) together as a single unit.
11. What is polymorphism?
    * Polymorphism means the ability to take many forms. It allows one interface to be used for a general class of actions.
12. Explain the concept of packages in Java.
    * A package in Java is a namespace that organizes a set of related classes and interfaces.
13. What is the difference between == and .equals() method?
    * == compares the reference, .equals() compares the content.
14. What is the purpose of the final keyword in Java?
    * final can be used to mark a variable, method, or class as immutable or unchangeable.
15. What is a constructor?
    * A constructor is a special method that is called when an object is instantiated.
16. What is exception handling in Java?
    * Exception handling is a mechanism to handle runtime errors, using try, catch, throw, throws, and finally.
17. What are the different types of exceptions in Java?
    * Checked exceptions, unchecked exceptions, and errors.
18. What is the difference between ArrayList and LinkedList?
    * ArrayList uses a dynamic array, LinkedList uses a doubly-linked list. ArrayList is better for fast access, LinkedList is better for fast insertion and deletion.
19. Explain the significance of the static keyword in Java.
    * static is used for memory management. It can be applied to variables, methods, blocks, and nested classes.
20. What is a singleton class?
    * A singleton class allows only one instance of itself to be created and provides a global point of access to that instance.
Spring Framework
21. What is the Spring Framework?
    * Spring is a powerful, feature-rich framework for building enterprise-level Java applications.
22. Explain the concept of dependency injection.
    * Dependency Injection is a design pattern that allows the creation of dependent objects outside of a class and provides those objects to a class in various ways.
23. What are Spring beans?
    * Spring beans are the objects that form the backbone of a Spring application. They are managed by the Spring IoC container.
24. What is the Spring IoC container?
    * The IoC container is responsible for instantiating, configuring, and assembling Spring beans.
25. Explain the difference between @Component, @Service, @Repository, and @Controller.
    * @Component is a generic stereotype for any Spring-managed component.
    * @Service indicates a service layer class.
    * @Repository indicates a data access object (DAO) class.
    * @Controller indicates a controller class in Spring MVC.
26. What is Spring Boot?
    * Spring Boot is an extension of the Spring framework that simplifies the setup and development of new Spring applications.
27. What is the difference between @Autowired and @Inject?
    * Both annotations are used for dependency injection, but @Autowired is a Spring-specific annotation, while @Inject is a standard Java annotation.
28. Explain the use of @RestController in Spring.
    * @RestController is a specialized version of @Controller which automatically returns a response body in RESTful web services.
29. What is Spring Data JPA?
    * Spring Data JPA is a part of the Spring Data family that makes it easy to implement JPA-based repositories with minimal boilerplate code.
30. How do you handle exceptions in Spring MVC?
    * Using @ExceptionHandler, @ControllerAdvice, and HandlerExceptionResolver.
31. What is Spring AOP?
    * Spring AOP (Aspect-Oriented Programming) is a programming paradigm that allows you to modularize cross-cutting concerns like logging, security, etc.
32. Explain the concept of aspect, advice, pointcut, and joinpoint in Spring AOP.
    * Aspect: A module that encapsulates a concern.
    * Advice: Action taken by an aspect.
    * Pointcut: A predicate that matches join points.
    * Joinpoint: A point during the execution of a program.
33. What is a transaction in Spring?
    * A transaction is a sequence of operations that are treated as a single logical unit of work. Spring provides a consistent transaction management interface.
34. How do you define a transaction in Spring?
    * Using @Transactional annotation.
35. What is Spring Security?
    * Spring Security is a framework that focuses on providing authentication and authorization to Java applications.
36. How do you secure a Spring Boot application?
    * Using Spring Security to configure authentication, authorization, and other security features.
37. Explain the role of ApplicationContext in Spring.
    * ApplicationContext is a central interface in the Spring IoC container that provides configuration information, manages bean lifecycle, and more.
38. What is a proxy in Spring?
    * A proxy is an object that acts as a surrogate for another object to control access to it.
39. What are the different types of Spring proxies?
    * JDK dynamic proxies and CGLIB proxies.
40. Explain Spring Batch.
    * Spring Batch is a framework for batch processing, providing reusable functions for processing large volumes of data.
41. What is the purpose of @SpringBootApplication annotation?
    * It combines @Configuration, @EnableAutoConfiguration, and @ComponentScan with their default attributes.
42. How do you create a custom annotation in Spring?
    * By defining an annotation interface and using @Retention and @Target annotations to specify its scope and target.
43. What is Spring Cloud?
    * Spring Cloud is a set of tools for building distributed systems and microservices, leveraging patterns like configuration management, service discovery, and circuit breakers.
44. What is Spring Cloud Config?
    * Spring Cloud Config provides server and client-side support for externalized configuration in a distributed system.
45. Explain the use of @Value annotation in Spring.
    * @Value is used to inject values into fields, methods, and constructor parameters from property files or system properties.
Development Process and Related Technologies
Cloud (AWS, GCP)
46. What is AWS?
    * Amazon Web Services (AWS) is a comprehensive, evolving cloud computing platform provided by Amazon.
47. What is GCP?
    * Google Cloud Platform (GCP) is a suite of cloud computing services offered by Google.
48. Explain the concept of cloud computing.
    * Cloud computing is the delivery of computing services over the internet, including storage, processing, and software.
49. What are the different types of cloud service models?
    * Infrastructure as a Service (IaaS), Platform as a Service (PaaS), Software as a Service (SaaS).
50. What is EC2 in AWS?
    * Amazon EC2 (Elastic Compute Cloud) is a web service that provides resizable compute capacity in the cloud.
51. What is S3 in AWS?
    * Amazon S3 (Simple Storage Service) is an object storage service offering scalability, data availability, security, and performance.
52. What is Lambda in AWS?
    * AWS Lambda is a serverless compute service that runs code in response to events and automatically manages the compute resources required.
53. What is Kubernetes?
    * Kubernetes is an open-source container-orchestration system for automating the deployment, scaling, and management of containerized applications.
54. Explain Google Kubernetes Engine (GKE).
    * GKE is a managed Kubernetes service offered by Google Cloud, providing a simplified way to deploy, manage, and scale containerized applications.
55. What is a VPC in AWS?
    * A Virtual Private Cloud (VPC) allows you to launch AWS resources into a virtual network that you define.
56. What is IAM in AWS?
    * AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS services and resources.
CI/CD
57. What is CI/CD?
    * Continuous Integration (CI) and Continuous Deployment/Delivery (CD) are practices that aim to improve software delivery by automating testing and deployment.
58. Explain the benefits of CI/CD.
    * Faster delivery of features, improved quality and reliability, reduced manual effort, and better collaboration among teams.
59. What is Jenkins?
    * Jenkins is an open-source automation server used to automate the building, testing, and deployment of software.
60. How do you set up a CI/CD pipeline in Jenkins?
    * Install Jenkins, create a new job, configure source code management, set up build triggers, define build steps, and configure post-build actions.
61. What is Docker?
    * Docker is a platform for developing, shipping, and running applications in containers.
62. How does Docker differ from virtual machines?
    * Docker containers share the host OS kernel and isolate applications from each other, while VMs run a full guest OS.
63. What is a Dockerfile?
    * A Dockerfile is a script containing instructions on how to build a Docker image.
64. What is a Docker Compose?
    * Docker Compose is a tool for defining and running multi-container Docker applications using a YAML file.
65. What is the purpose of a build server?
    * A build server automates the compilation, testing, and packaging of software projects.
Networking
66. What is an IP address?
    * An IP address is a unique identifier assigned to each device connected to a network.
67. Explain the difference between IPv4 and IPv6.
    * IPv4 is a 32-bit address format, while IPv6 is a 128-bit address format, providing a larger address space.
68. What is DNS?
    * The Domain Name System (DNS) translates domain names to IP addresses.
69. What is a firewall?
    * A firewall is a network security device that monitors and controls incoming and outgoing network traffic based on predetermined security rules.
70. What is a subnet?
    * A subnet is a segmented piece of a larger network, divided to improve performance and security.
71. What is NAT?
    * Network Address Translation (NAT) is a method of remapping one IP address space into another.
72. What is HTTP?
    * The HyperText Transfer Protocol (HTTP) is the foundation of data communication on the web.
73. What is HTTPS?
    * HTTPS (HyperText Transfer Protocol Secure) is an extension of HTTP, providing secure communication over a computer network.
74. What is a VPN?
    * A Virtual Private Network (VPN) extends a private network across a public network, allowing users to send and receive data securely.
75. What is load balancing?
    * Load balancing distributes network or application traffic across multiple servers to ensure no single server becomes overwhelmed.
Development Practices and Tools
76. What is Agile methodology?
    * Agile is an iterative approach to project management and software development that helps teams deliver value to their customers faster and with fewer headaches.
77. What is Scrum?
    * Scrum is an Agile framework for managing work, with a focus on iterative progress and collaboration.
78. What is the purpose of a stand-up meeting in Scrum?
    * Stand-up meetings are daily meetings where team members discuss their progress, plans, and obstacles.
79. What is a user story in Agile?
    * A user story is a short, simple description of a feature from the perspective of the end user.
80. What is the role of a Product Owner in Scrum?
    * The Product Owner is responsible for defining the features of the product and prioritizing the backlog.
81. What is Test-Driven Development (TDD)?
    * TDD is a software development process where tests are written before code, ensuring that the software meets its requirements.
82. What is Continuous Testing?
    * Continuous Testing involves executing automated tests as part of the software delivery pipeline to obtain feedback on the business risks associated with the latest build.
83. What is Pair Programming?
    * Pair Programming is an Agile software development technique where two programmers work together at one workstation.
84. What is Refactoring?
    * Refactoring is the process of restructuring existing computer code without changing its external behavior to improve nonfunctional attributes.
85. What is a Version Control System (VCS)?
    * A VCS is a system that records changes to a file or set of files over time so that specific versions can be recalled later.
86. What is Git?
    * Git is a distributed version control system used to track changes in source code during software development.
87. What is a Git branch?
    * A Git branch is a separate line of development created within a repository.
88. Explain the concept of merge conflicts in Git.
    * Merge conflicts occur when changes in different branches conflict and Git is unable to automatically merge them.
89. What is a pull request?
    * A pull request is a method of submitting contributions to a project, where the changes are reviewed before being merged into the main branch.
90. What is Jenkins Pipeline?
    * Jenkins Pipeline is a suite of plugins that support implementing and integrating continuous delivery pipelines into Jenkins.
91. What is Infrastructure as Code (IaC)?
    * IaC is the process of managing and provisioning computing infrastructure through machine-readable definition files.
92. What are the benefits of using IaC?
    * Consistency, repeatability, scalability, version control, and automation of infrastructure setup.
93. What is Terraform?
    * Terraform is an open-source IaC tool that allows you to build, change, and version infrastructure safely and efficiently.
94. What is Ansible?
    * Ansible is an open-source automation tool used for configuration management, application deployment, and task automation.
95. What is CI/CD pipeline as code?
    * It refers to defining the CI/CD pipeline in a code format, which can be versioned and managed like any other source code.
96. What is Blue-Green Deployment?
    * Blue-Green Deployment is a release management strategy that reduces downtime and risk by running two identical production environments, only one of which (blue or green) serves live production traffic.
97. What is Canary Deployment?
    * Canary Deployment is a technique to reduce the risk of introducing new software versions into production by slowly rolling out the change to a small subset of users before making it available to the entire infrastructure.
98. What is Microservices architecture?
    * Microservices architecture is a design pattern that structures an application as a collection of loosely coupled services, each implementing business capabilities.
99. What are the advantages of Microservices architecture?
    * Scalability, resilience, agility, and independent deployment.
100. What is DevOps? - DevOps is a set of practices that combines software development (Dev) and IT operations (Ops) aimed at shortening the development lifecycle and providing continuous delivery with high software quality.


#### In-Depth Spring Framework Interview Questions

**Spring Core**
101. Explain the different types of dependency injection in Spring. - Constructor Injection: Dependencies are provided through a class constructor. - Setter Injection: Dependencies are provided through setter methods. - Field Injection: Dependencies are injected directly into fields. It is the least preferred as it lacks transparency and is difficult to test.
102. What is the BeanFactory and how does it differ from the ApplicationContext? - BeanFactory: The BeanFactory is the simplest container providing basic dependency injection capabilities. - ApplicationContext: It extends BeanFactory to add more enterprise-specific functionality such as event propagation, declarative mechanisms to create a bean, and various means to look up.
103. Explain the different scopes of a Spring Bean. - Singleton: Only one instance of the bean is created and shared. - Prototype: A new instance is created each time the bean is requested. - Request: A new instance is created for each HTTP request. - Session: A new instance is created for each HTTP session. - Global-session: A new instance is created for a global HTTP session (portlet applications).
104. What is a Proxy object in Spring? - A proxy object in Spring is an object created by the Spring AOP framework to implement aspect-oriented programming. Proxies allow for additional behavior to be provided to an object without modifying the original code.
105. How does Spring handle transaction management? - Spring provides a consistent transaction management interface that can be used in any environment, supporting both programmatic and declarative transaction management.
106. Explain the difference between programmatic and declarative transaction management in Spring. - Programmatic: Transactions are managed using code by explicitly beginning and ending the transaction. - Declarative: Transactions are managed using annotations (@Transactional) or XML configuration.
107. What is the Spring Bean lifecycle? - Instantiation -> Populate properties -> BeanNameAware.setBeanName() -> BeanFactoryAware.setBeanFactory() -> ApplicationContextAware.setApplicationContext() -> BeanPostProcessor.postProcessBeforeInitialization() -> InitializingBean.afterPropertiesSet() -> Custom init-method -> BeanPostProcessor.postProcessAfterInitialization() -> Ready to use -> DisposableBean.destroy() -> Custom destroy-method.

**Spring Boot**

108. How does Spring Boot simplify application development? - Spring Boot simplifies development by providing pre-configured templates, eliminating the need for boilerplate configuration, and offering a set of starter projects for easy dependency management.
109. What are Spring Boot starters? - Starters are a set of convenient dependency descriptors you can include in your application. For example, spring-boot-starter-web includes dependencies for building web applications.
110. What is Spring Boot Auto-Configuration? - Spring Boot’s auto-configuration attempts to automatically configure your Spring application based on the jar dependencies you have added.
111. What is Spring Boot Actuator? - Spring Boot Actuator provides production-ready features to help you monitor and manage your application, such as health checks and metrics.
112. How do you configure properties in Spring Boot? - Properties can be configured using the application.properties or application.yml files, command line arguments, environment variables, or custom configuration files.
113. What is the purpose of the @SpringBootApplication annotation? - It combines @Configuration, @EnableAutoConfiguration, and @ComponentScan annotations, simplifying the setup of a Spring Boot application.

**Spring MVC**

114. What is the DispatcherServlet in Spring MVC? - The DispatcherServlet is the front controller in Spring MVC that receives all requests, coordinates them through handlers, and returns the appropriate response.
115. What are Controllers in Spring MVC? - Controllers are the components that handle user requests, process them, and return the view or object that should be rendered.
116. Explain the role of @RequestMapping annotation. - @RequestMapping is used to map web requests to specific handler methods in a controller.
117. What is the difference between @RequestParam and @PathVariable? - @RequestParam is used to extract query parameters, form parameters, and even files from the request, while @PathVariable extracts values from the URI template.
118. What is a ViewResolver in Spring MVC? - A ViewResolver maps view names to actual views. For example, InternalResourceViewResolver resolves view names to JSP files.
119. How do you handle form data in Spring MVC? - Form data can be handled using the @ModelAttribute annotation and binding the form fields to a model object.

**Spring Security**

120. What is Spring Security? - Spring Security is a powerful and highly customizable authentication and access-control framework for securing Spring-based applications.
121. How do you implement security in a Spring Boot application? - By adding the Spring Security dependency and configuring security settings through annotations (@EnableWebSecurity, @Configuration) and classes extending WebSecurityConfigurerAdapter.
122. What is the difference between authentication and authorization? - Authentication: Verifies the identity of a user. - Authorization: Determines the access level and permissions granted to an authenticated user.
123. What is the purpose of the UserDetailsService interface in Spring Security? - UserDetailsService is used to retrieve user-related data. It has a method loadUserByUsername which is used to fetch user details from a data source.
124. How do you handle password encryption in Spring Security? - By using the PasswordEncoder interface, which provides methods for password hashing and verification.
125. What are the different ways to secure a REST API in Spring? - Using HTTP Basic Authentication, OAuth2, JWT (JSON Web Token), or API keys.

**Spring Data**

126. What is Spring Data JPA? - Spring Data JPA is a part of the Spring Data family that makes it easy to implement JPA-based repositories with minimal boilerplate code.
127. What is a CrudRepository in Spring Data JPA? - CrudRepository provides CRUD functionalities for an entity class being managed, such as save, delete, and find operations.
128. What is the purpose of the @Query annotation in Spring Data JPA? - @Query is used to define custom SQL queries directly in the repository interface.
129. How do you implement pagination and sorting in Spring Data JPA? - By using the Pageable and Sort interfaces along with methods in the repository.
130. What is the difference between JpaRepository and CrudRepository? - JpaRepository extends CrudRepository and provides JPA-specific methods like flushing the persistence context and batch deletes.
Spring Integration and Spring Batch
131. What is Spring Integration? - Spring Integration is a framework that provides support for building enterprise integration solutions using message-driven architecture.
132. What are the key components of Spring Integration? - Channels, messages, endpoints, and adapters.
133. What is Spring Batch? - Spring Batch is a lightweight, comprehensive batch framework designed to enable the development of robust batch applications.
134. What are the main components of Spring Batch? - Jobs, Steps, ItemReaders, ItemProcessors, and ItemWriters.
135. How do you configure a Spring Batch job? - By defining job and step beans in a configuration class, and specifying the processing logic for each step.


### Other Java Core Interview Questions
1. What is Java?
    * Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible.
2. What are the features of Java?
    * Platform Independence, Object-Oriented, Secure, Multithreaded, Portable, Robust, Dynamic, and High Performance.
3. What is the difference between JDK, JRE, and JVM?
    * JDK: Java Development Kit, which includes JRE and development tools.
    * JRE: Java Runtime Environment, which includes JVM and libraries for running Java applications.
    * JVM: Java Virtual Machine, which runs Java bytecode on any platform.
4. What is a Java Class?
    * A blueprint from which individual objects are created. It contains fields and methods to define the properties and behaviors of the objects.
5. What is an Object in Java?
    * An instance of a class that has state and behavior.
6. Explain the concept of Inheritance in Java.
    * Inheritance is a mechanism where one class acquires the properties (fields) and behaviors (methods) of another class.
7. What is Polymorphism in Java?
    * The ability of an object to take on many forms, typically achieved through method overriding and method overloading.
8. What is Encapsulation in Java?
    * The wrapping of data (variables) and code (methods) into a single unit called a class. It restricts direct access to some of the object's components.
9. What is Abstraction in Java?
    * The process of hiding the implementation details from the user and only exposing the functionality.
10. What is the difference between an interface and an abstract class in Java?
    * An interface can only declare methods, while an abstract class can have method implementations. An abstract class can have constructors and member variables, whereas an interface cannot.
11. What is the default value of a local variable in Java?
    * Local variables do not have a default value; they must be initialized before use.
12. What is a Constructor in Java?
    * A constructor is a special method that is called when an object is instantiated. It initializes the new object.
13. Can we overload a constructor in Java?
    * Yes, constructors can be overloaded with different parameter lists.
14. What is the 'this' keyword in Java?
    * It refers to the current object within a class method or constructor.
15. What is the 'super' keyword in Java?
    * It is used to refer to the immediate parent class object.
16. What is method overloading in Java?
    * Method overloading is the ability to create multiple methods with the same name but different parameters.
17. What is method overriding in Java?
    * Method overriding occurs when a subclass provides a specific implementation of a method already defined in its superclass.
18. What is the use of the 'final' keyword in Java?
    * The final keyword is used to declare constants, prevent inheritance, and prevent method overriding.
19. What is a static variable in Java?
    * A static variable is shared among all instances of a class. It is associated with the class rather than any object.
20. What is a static method in Java?
    * A static method belongs to the class rather than any object instance and can be called without creating an object of the class.
21. What are the access modifiers in Java?
    * Public, Private, Protected, and Default.
22. What is the difference between '=='' and 'equals()' in Java?
    * == checks for reference equality (whether they point to the same object), while equals() checks for value equality (whether two objects are meaningfully equivalent).
23. What is a package in Java?
    * A package is a namespace for organizing classes and interfaces in a logical manner.
24. What is exception handling in Java?
    * Exception handling is a mechanism to handle runtime errors, ensuring the normal flow of the application. It uses try, catch, finally, throw, and throws.
25. What is the difference between checked and unchecked exceptions?
    * Checked exceptions are checked at compile-time, while unchecked exceptions are checked at runtime.
26. What is a try-catch block in Java?
    * A try block contains code that might throw an exception, and a catch block handles the exception.
27. What is the purpose of the finally block?
    * The finally block contains code that is always executed, regardless of whether an exception is thrown or not.
28. What is the difference between throw and throws?
    * throw is used to explicitly throw an exception, while throws is used in a method signature to declare that the method might throw exceptions.
29. What is a thread in Java?
    * A thread is a lightweight subprocess, the smallest unit of processing.
30. What is multithreading in Java?
    * Multithreading is a process of executing multiple threads simultaneously to maximize CPU utilization.
31. How do you create a thread in Java?
    * By extending the Thread class or implementing the Runnable interface.
32. What is the lifecycle of a thread in Java?
    * New -> Runnable -> Running -> Blocked -> Terminated.
33. What is synchronization in Java?
    * Synchronization is a mechanism to control the access of multiple threads to shared resources.
34. What is the purpose of the synchronized keyword?
    * To prevent thread interference and consistency problems by ensuring that only one thread can access a resource at a time.
35. What is a deadlock in Java?
    * A deadlock is a situation where two or more threads are blocked forever, waiting for each other.
36. What is the difference between wait() and sleep() in Java?
    * wait() releases the lock on an object and allows other threads to acquire it, while sleep() keeps the lock and simply pauses the thread.
37. What is a daemon thread in Java?
    * A daemon thread is a background thread that does not prevent the JVM from exiting when the program finishes.
38. What is the purpose of the volatile keyword?
    * To indicate that a variable's value will be modified by different threads.
39. What are generics in Java?
    * Generics enable types (classes and interfaces) to be parameters when defining classes, interfaces, and methods.
40. What is type erasure in Java?
    * Type erasure is the process by which generic type information is removed by the Java compiler, making the code compatible with Java versions before generics.
41. What is the purpose of the Comparable interface?
    * To impose a natural ordering on the objects of each class that implements it.
42. What is the purpose of the Comparator interface?
    * To define multiple ways to compare objects, allowing for custom sorting.
43. What are lambda expressions in Java?
    * Lambda expressions are a feature in Java that enables writing inline implementations of functional interfaces.
44. What are functional interfaces in Java?
    * An interface with a single abstract method, which can be implemented using a lambda expression or method reference.
45. What is the Stream API in Java?
    * A sequence of elements supporting sequential and parallel aggregate operations, enabling functional-style operations on collections.
46. What are default methods in Java?
    * Methods in interfaces with a body, providing a default implementation that can be overridden by implementing classes.
47. What is the purpose of the Optional class in Java?
    * To represent a value that may or may not be present, reducing the need for null checks.
48. What are annotations in Java?
    * Annotations provide metadata about the program, which can be processed at compile-time, runtime, or by tools.
49. What is reflection in Java?
    * Reflection is the ability to inspect and modify the behavior of classes, methods, and fields at runtime.
50. What is a singleton class in Java?
    * A class that allows only one instance to be created.
51. What is the difference between String, StringBuilder, and StringBuffer?
    * String is immutable, StringBuilder is mutable and not thread-safe, and StringBuffer is mutable and thread-safe.
52. What is an immutable object?
    * An object whose state cannot be changed after it is created.
53. What is a marker interface in Java?
    * An interface with no methods, used to indicate that a class has a certain property (e.g., Serializable).
54. What is serialization in Java?
    * The process of converting an object into a byte stream, so it can be easily saved to a file or sent over a network.
55. What is the purpose of the transient keyword?
    * To indicate that a field should not be serialized.
56. What is the difference between HashMap and Hashtable?
    * HashMap is not synchronized and allows null keys and values, whereas Hashtable is synchronized and does not allow null keys or values.
57. What is the difference between ArrayList and LinkedList?
    * ArrayList is backed by an array and provides fast random access, while LinkedList is a doubly-linked list and provides fast insertion and deletion.
58. What is the purpose of the Collections class?
    * To provide static methods for common operations on collections, such as sorting and searching.
59. What is the difference between Iterator and ListIterator?
    * Iterator can traverse a collection in one direction, while ListIterator can traverse a list in both directions and allows modification of elements.
60. What are Comparable and Comparator used for?
    * They are used for sorting objects. Comparable is for natural ordering, and Comparator is for custom ordering.
61. What is the purpose of the clone() method?
    * To create and return a copy of the object.
62. What is method hiding in Java?
    * When a static method in a subclass has the same signature as a static method in the parent class.
63. What is the purpose of the instanceof keyword?
    * To test whether an object is an instance of a specific class or interface.
64. What is a nested class in Java?
    * A class defined within another class. There are four types: static nested class, inner class, local class, and anonymous class.
65. What is the purpose of the synchronized keyword in Java?
    * To control the access of multiple threads to a shared resource.
66. What is the difference between volatile and synchronized?
    * volatile ensures visibility of changes to variables across threads, while synchronized ensures mutual exclusion and visibility.
67. What is an enum in Java?
    * A special Java type used to define collections of constants.
68. What is the purpose of the assert keyword?
    * To create assertion statements for testing assumptions in the code.
69. What is the purpose of the System class?
    * To provide access to system resources such as standard input, output, and error streams.
70. What is the difference between a Queue and a Stack?
    * A Queue follows FIFO (First In, First Out), while a Stack follows LIFO (Last In, First Out).
71. What is the difference between HashSet and TreeSet?
    * HashSet does not maintain any order of elements, while TreeSet maintains elements in a sorted order.
72. What is the purpose of the Collections class?
    * To provide utility methods for collection operations, such as sorting, searching, and synchronizing collections.
73. What is a weak reference in Java?
    * A reference that does not prevent its referent from being made finalizable, garbage collected, and then reclaimed.
74. What is a SoftReference in Java?
    * A reference that is cleared at the discretion of the garbage collector in response to memory demand.
75. What is a WeakHashMap in Java?
    * A HashMap where the keys are weakly referenced, meaning they can be garbage collected when no longer referenced elsewhere.
76. What is the purpose of the java.lang.Runtime class?
    * To provide methods to interact with the Java runtime environment.
77. What is a ThreadLocal variable?
    * A variable that is local to the current thread, allowing each thread to have its own copy.
78. What is the purpose of the wait(), notify(), and notifyAll() methods?
    * These methods are used for inter-thread communication and synchronization.
79. What is the purpose of the System.gc() method?
    * To suggest that the JVM should perform garbage collection, though it is not guaranteed to happen immediately.
80. What is the difference between System.gc() and Runtime.gc()?
    * System.gc() is a class method that internally calls Runtime.gc(), an instance method.
81. What is the purpose of the Serializable interface?
    * To enable an object to be converted into a byte stream and subsequently restored.
82. What is the purpose of the Externalizable interface?
    * To provide custom serialization and deserialization logic by implementing writeExternal() and readExternal() methods.
83. What is the purpose of the transient keyword?
    * To indicate that a field should not be serialized.
84. What is the Optional class in Java 8?
    * A container object which may or may not contain a non-null value, reducing the need for null checks.
85. What is the Stream API in Java 8?
    * A framework for processing sequences of elements, supporting functional-style operations like map-reduce transformations.
86. What is a lambda expression?
    * A concise way to represent an anonymous function, used primarily to implement functional interfaces.
87. What is a functional interface in Java?
    * An interface with a single abstract method, used as the target for lambda expressions and method references.
88. What is a default method in an interface?
    * A method with a default implementation, allowing new methods to be added to interfaces without breaking existing implementations.
89. What is the purpose of the java.util.function package?
    * To provide target types for lambda expressions and method references, with functional interfaces like Function, Consumer, and Predicate.
90. What is a method reference in Java?
    * A shorthand notation of a lambda expression to call a method, using :: syntax.
91. What is the difference between map and flatMap in Streams?
    * map transforms each element in a stream, while flatMap transforms each element to a stream and flattens the result into a single stream.
92. What is the Collectors utility class used for?
    * To provide various methods for creating Collector implementations, such as toList(), toSet(), and joining().
93. What is the purpose of the Optional class in Java?
    * To represent a value that may or may not be present, reducing the risk of NullPointerException.
94. What is a CompletableFuture in Java?
    * A class that represents a future result of an asynchronous computation, allowing chaining of dependent actions.
95. What is the Nashorn engine in Java 8?
    * A JavaScript engine for executing JavaScript code within the Java Virtual Machine.
96. What is a spliterator in Java 8?
    * An iterator-like interface for splitting and traversing elements of a source, used for parallel processing.
97. What are stream pipelines?
    * A sequence of stream operations, consisting of a source, intermediate operations, and a terminal operation.
98. What is the difference between peek and map in Streams?
    * peek is mainly used for debugging, as it allows viewing the elements as they flow through the stream, while map transforms the elements.
99. What is the Predicate interface in Java 8?
    * A functional interface representing a single argument function that returns a boolean.
100. What is the purpose of the forEach method in Streams? - To perform an action for each element in the stream, typically used as a terminal operation.

