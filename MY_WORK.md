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
| **Full Name** | Shahad Alassmi | 
| **Student ID** | 445052149 | 
| **University Email** | 445052149@std.psau.edu.sa |
| **GitHub Username** | shahadalassmi |
| **Repository Link** | https://github.com/shahadalassmi/OS-Assignment1-Shahad-Alassmi |

 
---

## 🎥 Video Link

**Video Link**: https://drive.google.com/file/d/1-9bD_ETcXs9sT8oifbFmclcess4Jf6kw/view?usp=sharing

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

 ### Entry 1 - October 4, 2026

**What I did**: Set up the Operating Systems assignment repository and prepared the project.

**Details**: I started the OS Assignment 1 project and created my own public GitHub repository from the starter repository. I also verified and set my university email on GitHub and checked the project files. I prepared the repository so I could start working on the SchedulerSimulation program.

**Challenges**: I was initially unsure about the correct repository setup and GitHub requirements.

**Solution**: I checked the assignment requirements and made sure the repository was public and had the required name and university email.

**Time spent**: Approximately 1 hour.

---

 ### Entry 2 - October 5, 2026

**What I did**: Implemented Feature 2: Context Switch Counter.

**Details**: I added a counter to the SchedulerSimulation program to track the number of context switches. I updated the scheduler so the counter increases each time a new process starts running. I also added the total number of context switches to the final output.

**Challenges**: I needed to understand when a context switch should be counted so that the counter would represent the scheduler behavior correctly.

**Solution**: I reviewed the scheduler flow and placed the counter increment when the next process starts running. I then ran the program and checked the final context switch count in the output.

**Time spent**: Approximately 1 hour.

---

 ### Entry 3 - October 6, 2026

**What I did**: Implemented Feature 3: Waiting Time Tracking.

**Details**: I added waiting time tracking to the SchedulerSimulation program. I recorded when a process entered the ready queue and calculated the time it spent waiting before running again. I also added waiting time and turnaround time to the final process table.

**Challenges**: The most difficult part was understanding when the waiting time should be measured, especially when a process was moved back to the ready queue after using its time quantum.

**Solution**: I tracked the queue entry time using `System.currentTimeMillis()` and calculated the waiting time when the process started running. I tested the program several times and checked the waiting time and turnaround time values in the final output table.

**Time spent**: Approximately 1.5 hours.

---

 ### Entry 4 - October 7, 2026

**What I did**: Fixed Feature 3 and continued documenting the assignment.

**Details**: I reviewed the waiting time implementation and updated the Process class to track the process creation time using `System.currentTimeMillis()`. I then committed the correction to the repository. After that, I continued completing the MY_WORK.md file, including the development log and reflection sections.

**Challenges**: I needed to make sure the waiting time implementation matched the assignment requirements and that the documentation accurately described the work I completed.

**Solution**: I reviewed the README requirements, checked the code and output, and made the required correction. I then continued documenting the actual steps and challenges from the assignment.

**Time spent**: Approximately 1 hour.
---
 ### Entry 5 - October 9, 2026

**What I did**: Reviewed the assignment requirements and continued completing the final documentation.

**Details**: I reviewed the `MY_WORK.md` file and checked the Student Information, Development Log, Reflection, and Technical Answers sections. I also reviewed the final checklist to identify the remaining requirements before submission. In addition, I checked the code comments and program output to verify the implemented features.

**Challenges**: I needed to make sure the documentation accurately reflected the work completed and that no important submission requirements were missed.

**Solution**: I compared the project with the assignment requirements, reviewed the program output, and identified the remaining tasks, including recording and uploading the demonstration video.

**Time spent**: Approximately 30 minutes.

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

 **Total time spent on assignment**: Approximately 5 hours.

**Most challenging part**: Implementing the waiting time feature and understanding when each process enters the ready queue and how its waiting time is calculated.

**Most interesting learning**: Understanding how Round-Robin scheduling distributes CPU time among processes using a ready queue and a time quantum.

**What I would do differently next time**: I would record my development log after each work session and test every feature immediately after implementing it.

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

I discovered that numerous threads can carry out tasks within the same application thanks to multithreading. The Process class in this assignment implements Runnable, and each process thread's execution is started using Thread.start(). Additionally, I discovered that while Thread.sleep() simulates the process execution time, Thread.join() causes the main scheduler thread to wait for the process thread to complete It startled me that the scheduler and process threads might be in different states simultaneously, particularly while the main thread was waiting with join() and the process thread was sleeping. I gained a better understanding of the interplay between threads, time quantum, and context changes thanks to this assignment.
## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

Implementing the waiting time feature was the most difficult aspect of this task. I had to comprehend when each process joined the ready queue and how long it waited before restarting, which made it challenging.Additionally, I had to use System.currentTimeMillis() to track process timing and understand how the waiting time is calculated. Ensuring that the final waiting time and turnaround time numbers were accurately reported in the output table presented another difficulty. I was able to comprehend how the timing data was being gathered by testing the software several times. This feature was difficult because even a tiny error in time tracking could have an impact on the outcome.
## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

By completing the task step-by-step and testing the program after each feature, I was able to overcome the difficulties. To make sure my modifications complied with the necessary guidelines, I went over the README again. I examined the code and compared the outcomes with the program output when I encountered issues with the waiting time computations. In order to ensure that the results were displayed accurately, I also ran the program multiple times after making modifications. Before altering the code when I wasn't positive about a need, I looked it over. This improved my comprehension of the features and allowed me to address issues without compromising their functioning.
## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading concepts can be used in many real-world applications. In a web browser, different threads can handle tasks such as loading pages, playing media, and responding to user actions at the same time. In a mobile application, threads can perform background tasks while the main thread keeps the interface responsive. In a music player, one thread can play music while another handles user controls or loads data. These examples are similar to my assignment because multiple threads can perform tasks while sharing CPU time. Thread scheduling and time limits help prevent one task from using the CPU continuously. This makes applications more responsive and allows multiple tasks to make progress.
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

A thread is a smaller unit of execution that operates inside a process and has the ability to share resources, whereas a process is an independent program with its own memory space. Because they share memory, threads are typically quicker to construct and interact with than individual processes. Since the scheduler is modeling CPU scheduling and Java threads are appropriate for expressing the execution of each simulated process, we utilize Java threads in this assignment rather than building actual operating system processes. Our code's `Process` class simulates a process, and the Java thread that really runs it is created by `new Thread(process)` in `addProcessToQueue()`.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

A process in Round-Robin scheduling is moved back into the ready queue so it can resume later if it does not complete within its time quantum. When a process in my software uses its time quantum and has burst time left, it gets re-queued. This prevents one process from using the CPU continually and instead gives other programs access to CPU time. Because the ready queue operates in FIFO order, allowing other processes to run, re-queuing is crucial for fairness.

Example from my output:
```
  P3 executing quantum [4000ms]
P3 completed quantum 4000ms
Remaining time: 4684ms
P3 yields CPU for context switch

P3 added to ready queue │ Burst time: 8684ms │ Priority: 10

P3 executing quantum [4000ms]
P3 completed quantum 4000ms
Remaining time: 684ms
P3 yields CPU for context switch

P3 added to ready queue │ Burst time: 8684ms │ Priority: 10
```

**Explanation of example:**
P3 has a burst time of 8684ms and the time quantum is 4000ms. After the first quantum, P3 still has 4684ms remaining, so it is placed back into the ready queue. After the second quantum, it has 684ms remaining and is re-queued again. This shows how Round-Robin scheduling gives other processes a chance to run before P3 continues. P3 was re-queued twice before it finished because its burst time was 8684ms and its time quantum was 4000ms.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*
 1. **New**: P1 is in the New state after its Thread object is created in `addProcessToQueue()` but before `Thread.start()` is called.

2. **Runnable**: P1 becomes Runnable when `currentThread.start()` is called, meaning the thread is ready to run.

3. **Running**: P1 is Running when its thread is executing the `run()` method and using the CPU for its time quantum.

4. **Waiting**: P1 thread enters the TIMED_WAITING state when Thread.sleep() is called during its execution. Meanwhile, the main scheduler thread waits for P1 to finish when it calls Thread.join().


5. **Terminated**: P1 reaches the Terminated state after its execution finishes and its `run()` method completes.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): CPU Scheduling

**Description**:

Round-Robin scheduling allows an operating system to distribute CPU time among several active programs. Like the processes in my simulation, any active program may be viewed as a process. Before a context transfer takes place, the time quantum allots a finite amount of CPU time to each process.
**Why Round-Robin works well here**:
Round-Robin is appropriate since it is equitable and allows every process to utilize the CPU. While context switches permit other processes to operate, the time quantum prohibits one process from utilizing the CPU continuously.
### Example 2: web Server Handling Multiple Requeste

**Description**:

Numerous client requests may need to be handled simultaneously by a web server. Similar to how a process in my simulation receives a time quantum, each request can only receive a certain amount of processing time. In order to prevent one request from consuming all of the processing time, the server can rotate between requests.
**Why Round-Robin works well here**:

Round-Robin can handle several requests in a fair and timely manner. While the time quantum regulates how long each request can use the CPU before another request has a chance, context switches enable the system to switch between requests.
## Summary

**Key concepts I understood through these questions:**
1. The distinction between a thread and a process, as well as how the simulated processes are carried out using threads.
2. How Round-Robin scheduling distributes CPU time equitably using a ready queue and a time quantum.
3. The relationship between the scheduler and thread lifecycle states, context changes, waiting times, and turnaround times.


**Concepts I need to study more:**
1. The specifics of thread communication and synchronization.
2. The internal implementation of context switching and CPU scheduling by operating systems.


---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [x] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [x] Repository is renamed to `OS-Assignment1-Shahad-Alassmi`
- [x] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [x] Student ID is set in `SchedulerSimulation.java` (line 150)
- [x] Code compiles and runs with no errors
- [x] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [x] Each feature has clear comments

**Commits**
- [x] **At least 3 meaningful commits, ideally 6 or more**
- [x] **One commit per feature**
- [x] Commits are spread over **different dates** (not all in the last hour)
- [x] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [x] Full name and student ID filled in at the top
- [x] Development log has **5+ entries** on different dates
- [x] Reflection: 4 questions, 5-7 sentences each
- [x] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [x] No `[...]` placeholders left
- [x] No section headers deleted

**Video**
- [x] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [x] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
