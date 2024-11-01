# Design patterns
Design patterns are proven solutions to common design problems in software development. They are typically categorized into three main types:

* Creational Patterns – Deal with object creation mechanisms.
* Structural Patterns – Focus on object composition or relationships.
* Behavioral Patterns – Concentrate on communication between objects.

Here’s a comprehensive overview with examples:
# Creational Design Patterns

| Pattern  | Description | Description |
| ------------- | ------------- | ------------- |
| Factory Method  | Provides an interface for creating objects in a superclass but allows subclasses to alter the type of object that will be created.  | Creating different financial products (e.g., loans, savings accounts) without knowing their specific classes.  |
| Abstract Factory  | Provides an interface to create families of related or dependent objects without specifying their concrete classes. | Creating UI components (e.g., buttons, text fields) that adapt to different operating systems (Windows, macOS).  |
| Singleton | Ensures a class has only one instance and provides a global point of access to it. | Database connection pool, logger instances.  |
| Builder  | Provides an interface to create families of related or dependent objects without specifying their concrete classes. | Building complex financial reports with multiple optional fields and configurations.   |
| Prototype  | Allows constructing complex objects step-by-step, separating the creation process from the representation. | Creating duplicate objects of various products like insurance policies or templates for new users.  |
