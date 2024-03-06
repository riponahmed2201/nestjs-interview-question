# NestJS Interview Question & Answer

## 1. What is NestJS, and why is it popular for building Node.js applications?

- NestJS is a framework for building efficient, reliable and scalable server-side applications. It is built on top of Node.js and is written in TypeScript. Its popularity stems from its modular architecture, ease of testing, and strong support for TypeScript, along with its utilization of Decorators for succinct and maintainable code.
- NestJS is a framework for building efficient, scalable Node.js server-side applications. It uses modern JavaScript, is built with TypeScript (preserves compatibility with pure JavaScript) and combines elements of Object-Oriented Programming, Functional Programming, and Functional Reactive Programming.

## 2. Who developed NestJS? Why did they develop NestJS?

- NestJS was developed by Kamil Myśliwiec, who is a Polish software engineer. He developed NestJS because he wanted to create a framework that would be easy to use and would allow developers to create scalable server-side applications.

## 3. When was NestJS first released?

- NestJS was first released on October 5, 2016.

## 4. Can you explain the key features of NestJS?

`Some key features of NestJS include:`

- `Modular Structure:` NestJS promotes a modular structure, helping to organize code in a clear and maintainable way.
- `Dependency Injection:` It has a robust Dependency Injection container that promotes code modularity and testability.
- `Decorators: Decorators:` NestJS utilizes decorators for adding metadata and additional behavior to classes, methods, and properties.
- `Middleware, Guards, Interceptors, and Pipes:` These classes help to handle different aspects of the request-response cycle.
- `Microservices Support:` NestJS has built-in support for microservice architecture.
- `Integration with Other Libraries:` It provides a level of abstraction over libraries like Express or Fastify, making integration easier.

## 5. What is the main difference between NestJS and Express.js?

- Express.js is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications. On the other hand, NestJS is a more opinionated framework built on top of Express.js (or Fastify) that provides a high-level abstraction with a lot of built-in decorators and modules, making it easier to organize and scale large applications. NestJS also has a strong emphasis on TypeScript, which is not inherent in Express.js.

## 6. How does NestJS promote the use of TypeScript in Node.js development?

- NestJS is built with TypeScript and encourages its use for building backend applications. It takes advantage of TypeScript's strong typing and modern ES/TS features to reduce bugs and improve the quality of code. Moreover, it utilizes decorators, modules, and classes, which are fundamental features of TypeScript, promoting a well-structured and strongly-typed codebase.

## 7. Describe the architecture pattern used by NestJS. What are the benefits of this pattern?

- NestJS utilizes a Monolithic architecture with a modular design inspired by Angular. The architecture promotes a modular structure, dependency injection, and the separation of concerns between controllers and providers. Benefits of this pattern include better code organization, maintainability, testability, and the ability to build scalable and extensible back-end applications. The modular design also allows for powerful abstractions and encapsulation of business logic, aiding in the development of large-scale applications.

## 8. Can you explain what TypeScript is and how it relates to NestJS?

- TypeScript is a typed superset of JavaScript that compiles to plain JavaScript. It adds optional types to JavaScript that support tools for large-scale JavaScript applications for the first time. NestJS is a framework for building efficient, scalable Node.js server-side applications. It uses TypeScript as its programming language.

## 9. What’s the difference between Angular and NestJS?

- Angular is a framework for building client-side applications, while NestJS is a framework for building server-side applications. NestJS is built on top of TypeScript and Express, and it aims to provide a more robust and scalable architecture for enterprise-level applications.

## 10. What are the main components of a NestJS application?

- The main components of a NestJS application are the controller, service, and module. The controller is responsible for handling incoming requests and sending responses. The service is responsible for business logic and interacting with data sources. The module is responsible for organizing the application into cohesive units.

## 11. What are modules and why are they used in NestJS?

- Modules are used in NestJS in order to group together related functionality and provide a higher-level structure for applications. By encapsulating related functionality into modules, NestJS applications can be more easily organized and maintained. This also makes it easier to reuse code across different parts of the application.

## 12. What are controllers and why are they used in NestJS?

- Controllers are responsible for handling incoming requests and sending responses to the client. In NestJS, controllers are used to define routes and map incoming requests to the appropriate handler functions.

## 13. What are services and why are they used in NestJS?

- Services are used in NestJS to encapsulate business logic and provide a way to share data and functionality between different parts of the application. Services can be injected into controllers and other services, making them a powerful tool for modularizing an application.

## 14. What does dependency injection mean in the context of programming? Why is it important for NestJS applications?

- Dependency injection is a technique for decoupling the dependencies of a software component from the component itself. This means that the component can be used in different contexts without having to change its code. In the context of NestJS, dependency injection is important because it allows NestJS to provide the dependencies that a component needs at runtime, instead of having to hard-code them into the component. This makes NestJS applications more flexible and easier to change.

## 15. What is an interceptor in the context of NestJS?

- Interceptors are functions that can be used to intercept incoming requests to a NestJS application and perform some sort of pre-processing or manipulation before the request is handled by the route handler. This can be useful for things like logging, authentication, or rate-limiting.

## 16. What are guards in the context of NestJS?

- Guards are functions that can be used to run checks before a route is executed. For example, you might use a guard to check if a user is logged in before allowing them to access a route. Guards can be used to perform all sorts of checks, and they can be used in combination with each other to create complex security systems.

## 17. What are pipes in the context of NestJS?

- Pipes are a feature of NestJS that allows for the transformation of data before it is passed to a route handler. This is useful for tasks such as validation or formatting data. Pipes can be chained together, and they can be used with middleware to create a powerful data processing pipeline.

## 18. What are middlewares in the context of NestJS?

Middlewares are functions that are executed by NestJS before a request reaches the final handler. Middlewares can be used for a variety of purposes, such as logging, authentication, and authorization.

## 19. What testing frameworks work best with NestJS?

- NestJS is a Node.js framework, so any testing framework that works with Node.js will work with NestJS. Some popular options include Jest, Mocha, and Jasmine.

## 20. What databases work best with NestJS?

- Any database that works with Node.js will work with NestJS. However, some databases are better suited for NestJS than others. For example, MongoDB is a popular choice for NestJS because it is a NoSQL database that is easy to use and scale.
