# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Maria Osama Ali |
| **Student ID** | 444052918 |
| **University Email** | 444052918@std.psau.edu.sa |
| **GitHub Username** | Maria-Osama1 |
| **Repository Link** | https://github.com/Maria-Osama1/OS-Assignment1-Maria-Osama |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [Date and Time]
**What I did**: Set up the assignment project.

**Details**: 
Forked the starter repository on GitHub.

Added my student ID to the Java code.

Opened the project in VS Code.

Prepared Java to run the program.

**Challenges**: 
I was not familiar with Git and GitHub.

**Solution**:
I followed step-by-step instructions to set up the project.

**Time spent**:
20 min

---

### Entry 2 - [Date and Time]
**What I did**: Added the Process Priority feature.

**Details**: 
Added a priority variable to the Process class.

Used Random to generate a priority from 1 to 10.

Displayed the priority when each process entered the ready queue.

Ran the program to check the output.

**Challenges**:
I needed to make sure each process kept the same priority when it returned to the ready queue.

**Solution**:
I stored the priority in the Process object and checked the output to confirm it did not change.

**Time spent**: 30 min

---

### Entry 3 - [Date and Time]
**What I did**: Added the Context Switch Counter feature.

**Details**: 
Added a static variable to count context switches.

Increased the counter each time a process started running.

Displayed the total number at the end of the simulation.

Ran the program and got 31 as the total count.

**Challenges**:
I needed to understand where the counter should increase.

**Solution**:
I added the counter before currentThread.start() and checked the final output.

**Time spent**: 30 min

---

### Entry 4 - [Date and Time]
**What I did**:  Added the Waiting Time Tracking feature.

**Details**: 
Used System.currentTimeMillis() to measure waiting time.

Recorded when each process entered and left the ready queue.

Added a table showing burst time, waiting time, and turnaround time.

Tested the program and checked the results for all 14 processes.

**Challenges**:
Understanding how to calculate waiting time when a process returns to the queue.

**Solution**:
 I used variables to store and add the waiting time for each process.

**Time spent**: 30 min

---

### Entry 5 - [Date and Time]
**What I did**: Tested the program and uploaded my changes to GitHub.

**Details**: 
Ran the scheduler simulation in VS Code.

Checked that all 14 processes completed successfully.

Confirmed that the context switch counter displayed 31.

Checked the waiting time and turnaround time report.

Committed and pushed the completed features to GitHub.

**Challenges**:
I had problems connecting to GitHub when pushing my changes.

**Solution**:
 I tried pushing again until the changes were uploaded successfully.

**Time spent**: 20 min

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [2 hours]

**Most challenging part**: Understanding the Java code and using GitHub.

**Most interesting learning**: Seeing how the Round-Robin scheduler gives each process a turn to use the CPU.

**What I would do differently next time**: I would try to understand the code better before making changes and test each feature step by step.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

I learned some basic ideas about multithreading in Java. I learned that a thread is used to run a task in a program. In our assignment, we used threads to simulate processes. I learned that `start()` starts a thread and `join()` waits for it to finish. I also saw how processes take turns using the CPU. I still find multithreading confusing, and I need more practice to understand it better.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The most challenging part of this assignment was understanding the Java code. I was not familiar with how threads work. At first, I did not understand how the scheduler manages the processes. I also found Git and GitHub difficult because I am still learning how to use them. I needed help to understand where to add the new features. I still need more practice.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I asked for help when I did not understand something. I followed the instructions step by step. I tried to understand where I should add each part of the code. I used VS Code to run the program and check the output. When I had problems with GitHub, I tried again until I could push my changes, these steps helped me finish the assignment.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading can be useful in many real-world applications. For example, a web browser can load a page while the user does something else. It can also help a music application play music while the user changes songs. In operating systems, scheduling helps different tasks share CPU time. Our assignment showed me a simple example of how tasks take turns. I still need more practice to understand how multithreading is used in real applications.

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A process is a program that is running, while a thread is a part of a process. Processes usually have separate memory, but threads in the same process share memory. Threads are also easier and faster to create than separate processes. In our Java code, the `Process` class represents a simulated process, and `new Thread(process)` creates a real thread to run it. We used threads because they are easier to manage in our simulation.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, each process gets a limited time to use the CPU. If a process does not finish, it goes back to the ready queue. In my program, P2 had a burst time of 12221 ms and a time quantum of 5000 ms. P2 was added back to the queue two times before it finished. This helps make scheduling fair because other processes also get a chance to run.

Example from my output:
```
P2 executing quantum [5000ms]
Remaining time: 7221ms
P2 yields CPU for context switch
P2 added to ready queue | Burst time: 12221ms | Priority: 4
```

**Explanation of example:**
P2 did not finish during its first time quantum, so it returned to the ready queue. This allowed the next process to use the CPU.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 is in the New state when we create it using new Thread(process).

2. **Runnable**: P1 becomes Runnable when currentThread.start() is called.

3. **Running**: P1 starts executing the run() method when the CPU runs its thread.

4. **Waiting**: P1 temporarily sleeps using Thread.sleep(), while the main thread waits for P1 to finish using join().

5. **Terminated**: P1 becomes Terminated when the run() method finishes.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): CPU Scheduling

**Description**:
An operating system runs many programs, such as a browser and a text editor. The CPU scheduler gives each program a small amount of CPU time. This is similar to the processes and time quantum in our assignment.

**Why Round-Robin works well here**:
Round-Robin is useful because every program gets a chance to use the CPU. When one program finishes its time quantum, the scheduler switches to another program. This helps keep the system responsive.

### Example 2: Web Server

**Description**:
A web server receives requests from different users. Threads can help the server handle multiple requests. Each request can be treated like a task in a queue.

**Why Round-Robin works well here**:
Round-Robin can give each task a turn to use CPU time. If a task needs more time, it can wait for another turn. This can help prevent one task from taking all the CPU time.

## Summary

**Key concepts I understood through these questions:**
1.The basic difference between a process and a thread.
2.How Round-Robin scheduling uses a time quantum.
3.How the ready queue and context switches work.

**Concepts I need to study more:**
1.Thread lifecycle and synchronization.
2.Multithreading in real applications.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
