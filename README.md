# SOLID Principles with symfony

This is a simple project to explain how to use/applicate the SOLID principles in symfony's project sample

- **S**ingle responsibility principle: <i style="color:green">a class should only have one responsibility. Furthermore, it should only have one reason to change.</i>

- **O**pen/Closed principle: <i style="color:green"> Classes should be open for extension but closed for modification. In doing so, we stop ourselves from modifying existing code and causing potential new bugs in an otherwise happy application.</i>

- **L**iskov substitution principle: <i style="color:green">if class A is a subtype (Child) of class B (Parent), we should be able to replace B with A without disrupting the behavior of our program.</i>

- **I**nterface segregation principle: <i style="color:green">Larger interfaces should be split into smaller ones. By doing so, we can ensure that implementing classes only need to be concerned about the methods that are of interest to them.</i>

- **D**ependency inversion principle: <i style="color:green">The principle of dependency inversion refers to the decoupling of software modules. This way, instead of high-level modules depending on low-level modules, both will depend on abstractions.</i>

**Project Requirements:**

- Symfony 7.0.\* (last stable version in date of 28/04/2024)
- PHP 8.2
- Makefile
- Docker

**Project : Docker List commands**

- _make help_ : Display commands list - help screen
- _make build_ : Builds the Docker images
- _make up_ : Start the docker hub in detached mode
- _make start_ : Build and start the containers
- _make down_ : Stop the docker hub
- _make logs_ : Show live logs
- _make sh_ : Connect to the FrankenPHP container
- _make bash_ : Connect to the FrankenPHP container via bash so up and down arrows go to previous commands
- _make create-project_ : init symfony project - <b>last stable version v7.0.\*</b>
