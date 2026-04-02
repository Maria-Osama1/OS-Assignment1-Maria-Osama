# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:

### Entry 1 - [April 1, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**: 
- Created GitHub account with university email
- Forked the starter repository
- Changed student ID on line 92 to my actual ID (441234567)
- Compiled and ran the program successfully

**Challenges**: Had to install JDK first because javac wasn't recognized

**Solution**: Downloaded JDK 17 from Oracle website and set PATH variable

**Time spent**: 30 minutes

---

## Your Development Log:

### Entry 1 - [March 31, 2026, 6:00 PM]
**What I did**: Create github account and set up the project

**Details**: 
- Created GitHub account
- Forked the repository from GitHub
- Opened the project in VS Code
- Updated my student ID 
- Ran the program to see the initial output

**Challenges**: The program didn’t run correctly at first in VS Code

**Solution**: install java tools and used terminal commands to run the program

**Time spent**: 45 minutes

---

### Entry 2 - [March 31, 2026, 7:00 PM]
**What I did**: Understood the program code

**Details**: 
- Studied how Round Robin scheduling is implemented
- Tracked how processes move in the ready queue
- Observed how threads are used to simulate execution

**Challenges**: It was confusing to understand how threads represent CPU execution

**Solution**: Followed the output step by step and connected it to the code

**Time spent**: 1 hour

---

### Entry 3 - [April 1, 2026, 5:30 PM]
**What I did**: Implemented Feature 1

**Details**: 
- Added a priority field to the Process class
- Updated constructor to include priority
- Generated random values between 1 and 5
- Displayed priority in the output

**Challenges**: Had trouble passing the new parameter correctly

**Solution**: Fixed the constructor arguments and updated object creation

**Time spent**: 30 minutes

---

### Entry 4 - [April 1, 2026, 6:30 PM]
**What I did**:  Implemented Feature 2

**Details**: 
- Added a static counter variable
- Incremented it whenever a new thread starts
- Displayed the total at the end

**Challenges**: Was unsure where to count the context switch

**Solution**: Placed it before starting the thread to reflect CPU switching

**Time spent**: 30 minutes

---

### Entry 5 - [April 2, 2026, 7:00 PM]
**What I did**: Implemented Feature 3

**Details**: 
- Added variables to track waiting time
- Recorded when processes enter the queue
- Calculated waiting time before execution
- Accumulated the total waiting time

**Challenges**: Calculating waiting time correctly across multiple cycles

**Solution**: Used timestamps and updated waiting time incrementally

**Time spent**: 30 minutes

---

### Entry 6 - [April 2, 2026, 5:00 PM]
**What I did**: Testing and final adjustments

**Details**: 
- Ran the full program to verify all features
- Checked output for correctness
- Added comments for clarity
- Prepared files for submission

**Challenges**: Minor formatting issues in output

**Solution**: Adjusted print statements

**Time spent**: 20 minutes

---

## Summary

**Total time spent on assignment**: [3 hours and 35 minutes]

**Most challenging part**: Tracking and calculating the waiting time correctly

**Most interesting learning**: Understanding how scheduling algorithms work in real systems

**What I would do differently next time**: Test each feature immediately after implementing it to catch issues earlier
