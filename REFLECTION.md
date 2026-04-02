# Reflection Questions

## Instructions
Answer the following questions about your learning experience. Each answer should be **at least 5-7 sentences** and show your understanding.

---

## Question 1: What did you learn about multithreading?

**Your Answer:**

Through this assignment, I learned how multithreading allows multiple tasks to execute concurrently within the same program. I understood how threads are created in Java using the Thread class and how each thread represents a separate flow of execution. I also learned about thread states, such as running, waiting, and terminated, and how threads transition between these states during execution. One important concept I learned is how threads can simulate CPU scheduling, even though they are not actually running in parallel on a single-core system. I was surprised by how thread execution can be controlled using methods like start() and join() to manage the order of execution. Additionally, I realized that threads share resources, which makes coordination and timing important. Overall, this assignment helped me connect theoretical concepts of multithreading to practical implementation.

---

## Question 2: What was the most challenging part of this assignment?

**Your Answer:**

The most challenging part of this assignment was implementing the waiting time calculation correctly. The difficulty came from the fact that each process does not execute once, but instead runs in multiple cycles and re-enters the ready queue several times. This made it harder to determine exactly when a process is waiting versus when it is executing. Understanding where to place the time tracking logic in the code required careful analysis of the execution flow. I initially found it confusing to track the transitions between queue and execution. Additionally, I had to ensure that the waiting time accumulates correctly across multiple cycles. This challenge was closely related to understanding how scheduling algorithms work in real systems.

---

## Question 3: How did you overcome the challenges you faced?

**Your Answer:**

To overcome the challenges, I approached the problem step by step and focused on understanding the logic before implementing it. I used debugging techniques such as printing intermediate values to track how the program behaves during execution. I also relied on System.currentTimeMillis() to accurately measure time and experimented with different placements of the calculation. When something didn’t work as expected, I reviewed the code flow and tried to identify where the logic might be incorrect. Breaking the problem into smaller parts made it easier to manage and test each component separately. I also referred to lecture concepts and examples to better understand how scheduling and waiting time should work. This systematic approach helped me eventually reach a correct solution.

---

## Question 4: How can you apply multithreading concepts in real-world applications?

**Your Answer:**

Multithreading is widely used in real-world applications to improve performance and responsiveness. For example, in web browsers, multiple threads are used to load web pages, handle user input, and run background scripts simultaneously. In mobile applications, threads allow the app to perform tasks like downloading data while still responding to user interactions. Games also use multithreading to manage rendering, physics calculations, and input processing at the same time. In this assignment, I saw how threads can simulate CPU scheduling, which is similar to how operating systems manage multiple processes. Multithreading helps ensure that no single task blocks the entire system. This makes applications faster, smoother, and more efficient. Understanding this concept is important for developing scalable and responsive software systems.
---

## Additional Reflections (Optional)

### What would you like to learn more about?

I would like to learn more about advanced multithreading topics such as synchronization and avoiding race conditions. I am also interested in understanding how threads are managed in multi-core systems and how true parallelism is achieved. Learning about thread safety and concurrency control mechanisms would also be valuable.
---

### How confident do you feel about multithreading concepts now?

Intermediate

I feel comfortable with the basic concepts such as thread creation, execution, and scheduling. I understand how threads interact in a program and how they can be used to simulate real-world scenarios. However, I still need more practice with advanced topics like synchronization and handling shared resources safely.
---

### Feedback on the assignment

This assignment was very helpful in connecting theoretical concepts with practical implementation. It required careful thinking and problem-solving, especially for time-related calculations. The difficulty level was appropriate, but some parts, like waiting time calculation, were challenging. Overall, it was a valuable learning experience.