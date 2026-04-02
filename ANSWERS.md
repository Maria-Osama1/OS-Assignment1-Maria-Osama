# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:**

A process is a complete program that runs independently and has its own memory space and system resources. In contrast, a thread is a smaller unit of execution that exists within a process and shares the same memory with other threads. Because threads share resources, they are faster to create and require less overhead compared to processes. Creating multiple processes would be more complex and consume more system resources. In this assignment, threads were used because they allow us to simulate multiple tasks running within a single program efficiently. This makes them more suitable for implementing scheduling algorithms like Round Robin.
---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:**

In Round-Robin scheduling, if a process does not finish within its assigned time quantum, it is stopped and placed at the end of the ready queue. This allows other processes to get their turn to run on the CPU. The scheduler then selects the next process in the queue and executes it. This cycle continues until all processes finish execution. This approach ensures fairness and prevents any single process from dominating CPU time.
Example from my output:
```
P1 is running...
P1 did not finish, remaining time = 2000ms
P1 added back to ready queue
P2 is running...```

**Explanation of example:**
In this example, process P1 starts running but does not complete within its time quantum. As a result, it is moved back to the end of the ready queue. The CPU then switches to process P2 instead of continuing P1. Later, P1 will run again when it reaches the front of the queue. This demonstrates how Round Robin scheduling rotates processes fairly.
---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**

1. **New**: P1 is in the New state when it is first created as a thread but has not started execution yet.

2. **Runnable**: P1 enters the Runnable state after the start() method is called, meaning it is ready and waiting for CPU scheduling.

3. **Running**: P1 is in the Running state when the CPU begins executing it during its assigned time quantum.

4. **Waiting**: P1 can enter a waiting-like state when it finishes its time quantum but still has remaining burst time, so it is placed back into the ready queue until its next turn.

5. **Terminated**: P1 reaches the Terminated state when it completes all its execution and does not return to the queue anymore.

---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: Web Browser

**Description**: 
A web browser uses multiple threads to load web pages, handle user input, and run background tasks like scripts and images.

**Why Round-Robin works well here**: 
Round Robin ensures that each task gets a fair share of CPU time, which keeps the browser responsive. It prevents one heavy task from blocking others and improves the overall user experience.

### Example 2: Mobile Applications

**Description**: 
Mobile applications use threads to perform tasks such as downloading data while the user is still interacting with the app.

**Why Round-Robin works well here**: 
Round Robin scheduling allows different tasks to run in turns without blocking each other. This keeps the application smooth and responsive, even when multiple operations are happening at the same time.
---

## Summary

**Key concepts I understood through these questions:**
1. The difference between threads and processes
2. How Round Robin scheduling works in practice
3. Thread lifecycle and state transitions

**Concepts I need to study more:**
1. Thread synchronization
2. Managing shared resources safely
