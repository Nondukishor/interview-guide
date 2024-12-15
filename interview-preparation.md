**Introduction**

I’m Nipu Chakraborty, a graduate and diploma holder in Computer Science and Engineering (CSE). Currently, I work as a Backend Tech Lead at a software company.
With 6 years of experience in web development, I’ve contributed to exciting projects like OTT platforms, e-commerce systems, and CMS SaaS applications.
I thrive on exploring innovative and creative ideas that make my work both meaningful and enjoyable.


**What is call stack in javascript?**

The call stack in JavaScript is a data structure that keeps track of function calls in the order they are executed, serving as the mechanism JavaScript uses to manage execution context. 
It is part of the JavaScript engine and plays a crucial role in function invocation and execution.The call stack operates on the Last In, First Out (LIFO) principle. 
The last function added to the stack is the first one to be executed and removed.

**What is event loop in JavaScript?**

The event loop in JavaScript is a mechanism that enables asynchronous operations by managing the execution of code, collecting and processing events, and running queued tasks. 
It is part of the JavaScript runtime and plays a key role in ensuring non-blocking execution in a single-threaded environment.

**What is memo in ReactJs?**

In React, memo is a higher-order component (HOC) used to optimize the performance of functional components by preventing unnecessary re-renders. 
It works by memorizing the rendered output of a component and only re-rendering it if its props change.

**What is the difference between memo and useMemo in React?**

The main difference between React.memo and useMemo lies in their purpose and application:

**React.memo:**
- Used to memoize a functional component to prevent unnecessary re-renders.
- Works at the component level by comparing the previous and next props.
- Applicable when you want to optimize re-renders of child components.

**useMemo:**

- Used to memoize the result of a function or computation within a functional component.
- Works at the value level to avoid recomputing expensive calculations or re-creating objects unless dependencies change.
- Helps optimize computations inside a component, not the component itself.


**What is Apache Kafka?**

Apache Kafka is an open-source, distributed event streaming platform designed to handle real-time data feeds with high throughput and low latency. 
It is widely used for building real-time data pipelines, event-driven applications, and stream processing systems.

**What Topic in Apache Kafka?**

Messages are categorized into topics. A topic is a logical channel to which producers write and from which consumers read. Topics are divided into partitions for parallel processing

**What is producers in kafka?**

Applications that publish (write) messages to Kafka topics.

**What is Consumers in Apache Kafka?**

Applications that subscribe to (read) messages from Kafka topics.

**What is broker in kafka?**

Kafka servers that store and manage data. A Kafka cluster consists of multiple brokers.

**What is offset and partition in kafka**

Each topic is split into partitions. Each message in a partition has a unique offset, which acts as a sequence identifier.
