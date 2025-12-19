CS 320 Portfolio Reflection
How can I ensure that my code, program, or software is functional and secure?

I ensure that my software is functional and secure by using unit testing, validation, and defensive programming techniques throughout development. In Project One, I created JUnit tests for the Contact and ContactService classes to verify that all requirements were met, including data validation rules and expected behaviors. Writing tests alongside the code helped catch errors early and ensured that each method behaved correctly under both valid and invalid inputs.

From a security standpoint, I focused on input validation and encapsulation. Fields were kept private, setters enforced constraints, and invalid data was rejected before it could cause issues. Automated tests helped confirm that these safeguards continued to work as the code evolved. This approach reduces bugs, prevents unexpected behavior, and improves overall software reliability.

How do I interpret user needs and incorporate them into a program?

I interpret user needs by carefully analyzing requirements and translating them into specific, testable behaviors. In this course, the project requirements clearly defined what the services needed to do, such as creating, updating, and deleting contact, task, and appointment objects. I used these requirements to guide both my implementation and my test cases.

By writing tests that directly reflected the requirements, I was able to verify that the program met user expectations. This process helped ensure that functionality aligned with what the user needed rather than assumptions made during development. Testing from a user-focused perspective reinforced the importance of building software that behaves predictably and consistently.

How do I approach designing software?

I approach software design by focusing on clarity, modularity, and testability. I break problems down into smaller components and design classes with single, clear responsibilities. In Project One, separating the Contact object from the ContactService allowed for cleaner code and more targeted testing.

I also design software with testing in mind. Writing unit tests influenced how I structured methods and data validation, leading to more maintainable and readable code. In Project Two, reflecting on testing strategies reinforced the importance of choosing the right testing approach based on requirements. Overall, I aim to design software that is easy to understand, easy to test, and easy to maintain.
