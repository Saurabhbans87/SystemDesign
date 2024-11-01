# Design patterns
Design patterns are proven solutions to common design problems in software development. They are typically categorized into three main types:

* Creational Patterns – Deal with object creation mechanisms.
* Structural Patterns – Focus on object composition or relationships.
* Behavioral Patterns – Concentrate on communication between objects.

Here’s a comprehensive overview with examples:
# Creational Design Patterns

Creational patterns provide various ways to create objects, increasing flexibility and reuse.

| Pattern  | Description | Description |
| ------------- | ------------- | ------------- |
| Factory Method  | Provides an interface for creating objects in a superclass but allows subclasses to alter the type of object that will be created.  | Creating different financial products (e.g., loans, savings accounts) without knowing their specific classes.  |
| Abstract Factory  | Provides an interface to create families of related or dependent objects without specifying their concrete classes. | Creating UI components (e.g., buttons, text fields) that adapt to different operating systems (Windows, macOS).  |
| Singleton | Ensures a class has only one instance and provides a global point of access to it. | Database connection pool, logger instances.  |
| Builder  | Allows constructing complex objects step-by-step, separating the creation process from the representation. | Building complex financial reports with multiple optional fields and configurations.   |
| Prototype  | Allows constructing complex objects step-by-step, separating the creation process from the representation. | Creating duplicate objects of various products like insurance policies or templates for new users.  |

# Structural Design Patterns

Structural patterns focus on class and object composition, forming larger structures through simpler components.

| Pattern  | Description | Description |
| ------------- | ------------- | ------------- |
| Adapter  | Converts one interface of a class into another that a client expects.  | Converting legacy system data formats (e.g., XML to JSON) for a new system.  |
| Bridge  | Separates an object’s abstraction from its implementation so the two can vary independently.  | Managing different types of bank accounts (savings, checking) across different bank services.  |
| Composite  | Composes objects into tree-like structures to represent part-whole hierarchies, treating individual and composite objects uniformly.  | File management systems, where files and folders are represented as a tree structure.  |
| Decorator  | Adds behavior or responsibilities to objects dynamically without modifying their class.  | Applying discounts or promotions to transactions at runtime in an e-commerce system. |
| Facade  | Provides a unified interface to a set of interfaces in a subsystem, making it easier to use.  | Simplifying a complex financial system by exposing a straightforward interface for creating, managing, and viewing accounts. |
| Flyweight  | Reduces memory use by sharing as much data as possible with similar objects.  | Managing financial transactions in high-frequency trading, where objects with the same transaction types share common properties. |
| Proxy  | Provides a surrogate or placeholder for another object to control access to it. | Adding access control to sensitive bank account actions or managing network-intensive calls to external services. |

# Behavioral Design Patterns

Behavioral patterns focus on communication between objects, defining how they interact and fulfill responsibilities.

| Pattern  | Description | Description |
| ------------- | ------------- | ------------- |
| Chain of Responsibility  | Passes a request along a chain of handlers until one handles it.  | Handling support requests in a help desk system, where requests escalate from lower to higher levels. |
| Command  | Encapsulates requests as objects, allowing for parameterization of clients with different requests, queuing, or logging.  | Transaction systems where operations (deposits, withdrawals) can be undone or redone. |
| Interpreter  | Implements an interpreter for a language by defining a grammar and interpretation logic.  | Interpreting and executing trading instructions in a domain-specific language (DSL) for finance. |
| Iterator  | Provides a way to access elements of a collection sequentially without exposing its underlying representation.  | Traversing through a list of transactions in an account history or portfolio. |
| Mediator  | Defines an object to encapsulate how objects interact, promoting loose coupling.  | Coordinating between modules in an online trading platform (order management, trading, account). |
| Memento  | Allows capturing and restoring an object’s internal state without exposing its details.  | Implementing undo functionality in financial modeling software or a document editor. |
| Observer  | Defines a one-to-many dependency where changes in one object trigger updates in others.  | Notifying users of stock price changes, interest rate adjustments, or account status updates. |
| State  | Allows an object to change its behavior when its internal state changes, appearing to change its class.  | Managing different states of an account (e.g., active, overdrawn, closed) and the allowed operations for each state. |
| Strategy  | Allows defining a family of algorithms and making them interchangeable.  | Applying different investment strategies (e.g., conservative, aggressive) for a portfolio. |
| Template Method  | Defines the structure of an algorithm, deferring steps to subclasses.  | Defining a general process for loan approval while allowing specific criteria for different loan types. |
| Visitor  | Allows adding further operations to objects without modifying their structure.  | Applying various operations like tax calculation or report generation on financial statements. |
