# S.O.L.I.D

* **Single responsibility principle** - A class should have only a single responsibility.

* **Open/Closed principle - A class should be open for extension but closed for modification.

* **Liskov Substitution Principle** - A type must be substitutable by its subtypes without altering the correctness of the application.

* **Interface Segregation Principle** - Clients of a class should not be forced to depend on those of its methods that they don’t use.

* **Dependency inversion principle** - High-level classes should not dependent on low-level classes. Both of them should depend on abstractions. Abstractions should not depend upon details. Details should depend upon abstractions.

# Applied Anti-SOLID and SOLID Principles
### Code Samples and UML Class Diagrams
-----------
#### S - Single Responsibility Principle (SRP) <br />
A class should have only a single responsibility.<br /><br />
![srp](./assets/srp.JPG?raw=true "Single Responsibility Principle")

------

#### O - Open/Closed Principle (OCP) <br />
A class should be open for extension but closed for modification. <br /><br />
![ocp](./assets/ocp.JPG?raw=true "Open/Closed Principle")

-----

#### L - Liskov’s Substitution Principle (LSP) <br />
A type must be substitutable by its subtypes without altering the correctness of the application. <br /><br />
![lsp](./assets/lsp.JPG?raw=true "Liskov's Substitution Principle")

----

#### I - Interface Segregation Principle (ISP) <br />
Clients of a class should not be forced to depend on those of its methods that they don’t use.<br /><br />
![isp](./assets/isp.JPG?raw=true "Interface Segregation Principle")

-----

#### D - Dependency Inversion Principle (DIP)<br />
High-level classes should not dependent on low-level classes. Both of them should depend on abstractions.<br />
Abstractions should not depend upon details. Details should depend upon
abstractions.<br />
![dip](./assets/dip.JPG?raw=true "Dependency Inversion Principle")

--------

### SOLID Short Control List
- Do methods in the class have similar responsibilities? (SRP)
- Are there any method in the class that functions different based on different variables? (OCP)
- Are there any functionless methods/properties which comes from base class/interface in your derived classes? (LSP & ISP)
- Are there initiations of non-abstract objects in a high-level class? (DIP)

-------------

<br /><br /><br /><br /><br /><br /><br /><br />

-------------