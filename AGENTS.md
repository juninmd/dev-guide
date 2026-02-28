```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the development of AI coding agents (AGENTS) within this repository are robust, maintainable, and efficient.  Adherence to these principles is mandatory for all development activities.

**1. DRY (Don't Repeat Yourself)**

*   All functions, classes, and modules should have single, well-defined responsibilities.
*   Avoid duplication of logic and code.
*   Refactor existing code to eliminate redundancy.
*   Use design patterns where appropriate to standardize solutions.

**2. KISS (Keep It Simple, Stupid)**

*   Strive for simplicity in design and implementation.
*   Avoid overly complex solutions.
*   Prioritize clarity and readability.
*   Keep code concise and easy to understand.
*   Minimize cognitive load on developers.

**3. SOLID Principles**

*   **Single Responsibility Principle:** Each class, function, or module should have one and only one reason to change.
*   **Open/Closed Principle:** The system should be open for extension but closed for modification.
*   **Liskov Substitution Principle:**  Subclasses should be able to replace parent classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be forced to depend on abstractions they do not use.
*   **Dependency Inversion Principle:** High-level modules should not depend on low-level modules.

**4. YAGNI (You Aren't Gonna Need It)**

*   Implement only the necessary functionality.
*   Avoid adding features that are not currently required.
*   Focus on delivering working code.
*   Refactor code to remove unused or obsolete features.

**5. Code Structure & File Size**

*   **Maximum Code Length:** 180 lines of code per file.
*   **File Structure:**
    *   **Modules:** Group related code into logical modules.  Each module should have a single, well-defined purpose.
    *   **Classes:**  Each class should represent a distinct concept or behavior.
    *   **Functions:** Each function should perform a specific task and have a single responsibility.
    *   **Data Structures:**  Use appropriate data structures (e.g., lists, dictionaries) for efficient data management.
    *   **Consistency:**  Follow consistent naming conventions and coding style throughout the repository.
*   **Naming Conventions:**  Adopt a consistent naming convention (e.g., snake_case).

**6. Testability & Mocking**

*   **All development must be productive.**  Do not use mocks or fake implementations.
*   All unit tests should be written to verify the functionality of individual code units.
*   Unit tests should cover critical functionality and edge cases.
*   Tests should be independent and isolated.
*   Test coverage should be at least 80%.
*   Focus on automated testing; automated testing is primary.
*   Mocking/stubbing should be reserved for tests *only*.  No real implementations in production code.

**7.  Specific Considerations for AGENTS:**

*   **State Management:** Implement a robust state management system using appropriate data structures and algorithms.
*   **Communication Protocols:** Define clear communication protocols between agents (e.g., message queues, APIs).
*   **Agent Roles & Responsibilities:** Clearly define agent roles and their responsibilities.
*   **Error Handling:** Implement comprehensive error handling and logging.
*   **Configuration Management:**  Establish a well-defined mechanism for managing agent configurations.
*   **Scalability:** Design the system with scalability in mind.

**8. Documentation**

*   Include clear and concise documentation for all classes, functions, and modules.
*   Provide comments explaining complex logic.
*   Use docstrings to describe the purpose of functions and classes.

**9.  Code Quality & Style**

*   Use consistent indentation and spacing.
*   Write clear and concise code.
*   Apply linting and static analysis tools to identify potential issues.
*   Follow the established coding style guide.

**10.  Commit Frequency:**

*   Commit changes frequently (e.g., every 24 hours).
*   Small, focused commits are preferred.

These guidelines are intended as a starting point and may be subject to change as the project evolves. Regular review and adherence to these principles are essential for maintaining a high-quality and maintainable AGENTS.
```