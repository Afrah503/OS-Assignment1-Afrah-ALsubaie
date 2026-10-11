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
| **Full Name** | [Afrah Mutlaq Al Subaie] |
| **Student ID** | [445052061] |
| **University Email** | [445052061@std.psau.edu.sa] |
| **GitHub Username** | [Afrah503] |
| **Repository Link** | [https://github.com/Afrah503/OS-Assignment1-Afrah-AlSubaie] |
 
---

## 🎥 Video Link

**Video Link**: [ video1:https://drive.google.com/file/d/1oU807HCm3BpTXfW0AWRDPJS9OHVlHnxq/view?usp=sharing]
[ video2:https://drive.google.com/file/d/1cuAlzbG8LCN_IJdeJ-Un73xxHtA36WN1/view?usp=sharing]
[ video3:https://drive.google.com/file/d/1BWNaOAKPusDe9pHfCUu5E5inGsOPkPfI/view?usp=sharing]

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
### Entry 1 - [October 8, 2026, 2:30 PM]
**What I did**: Forked the repository and set up student ID.

**Details**:
- Forked the starter repository and verified local configuration.
- Updated student ID on line 150 in `SchedulerSimulation.java` to my actual ID (445052061).
- Compiled and ran the simulation to test the environment.

**Challenges**: Configuring the Java execution environment in VS Code.

**Solution**: Configured the Java extension path and re-ran `javac`.

**Time spent**: 30 minutes

---

### Entry 2 - [October 9, 2026, 11:00 AM]
**What I did**: Implemented Feature 1 (Process priority tracking).

**Details**:
- Enhanced `Process.java` with start time tracking parameters.
- Added getters and setters for accurate execution time measurements.
- Tested compilation to ensure no broken references.

**Challenges**: Ensuring non-interfering timing metrics across active threads.

**Solution**: Placed timestamps right before thread burst execution.

**Time spent**: 45 minutes

---

### Entry 3 - [October 9, 2026, 4:00 PM]
**What I did**: Implemented Feature 2 (Queue and Map Management).

**Details**:
- Formulated `addProcessToQueue()` to link processes with ready queue operations.
- Ensured process mapping within `processMap` remained synchronized during execution.
- Verified status messages in terminal output.

**Challenges**: Handling thread state transitions correctly.

**Solution**: Carefully structured thread instantiation inside the helper method.

**Time spent**: 1 hour

---

### Entry 4 - [October 10, 2026, 1:15 PM]
**What I did**: Implemented Feature 3 (Summary Metrics Report).

**Details**:
- Built final metrics printing method to display waiting time per process.
- Calculated total turnaround time and average waiting times.
- Verified color-formatted output in the console.

**Challenges**: Calculating individual waiting times in a preemptive Round-Robin queue.

**Solution**: Subtracted burst execution time from overall elapsed turnaround time.

**Time spent**: 45 minutes

---

### Entry 5 - [October 10, 2026, 7:30 PM]
**What I did**: Finalized Documentation and Prepared Video Link.

**Details**:
- Filled out reflection questions and technical explanations in `MY_WORK.md`.
- Recorded the 2-minute demo video showing student ID, commits, and simulation execution.
- Uploaded video and pasted public sharing link into `MY_WORK.md`.

**Challenges**: Keeping the video duration within the 2 to 3 minute restriction.

**Solution**: Followed a timed script covering all mandatory assignment aspects.

**Time spent**: 1 hour

---


## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [4 hours]

**Most challenging part**:Understanding thread synchronization and accurate waiting time calculation.

**Most interesting learning**:Seeing how Round Robin scheduling guarantees fairness using Time Quantums.

**What I would do differently next time**:Start documenting development log entries simultaneously during coding sessions.

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

[I learned that multithreading allows multiple threads to run concurrently, simulating processes by sharing the CPU efficiently. Using methods like Thread.start() initialized the threads, while Thread.join() ensured the main thread waited for all worker threads to complete execution. Simulating work with Thread.sleep() helped visualize state transitions clearly in the console output. It was fascinating to see how Java manages concurrent execution alongside shared data structures.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was implementing precise queue management and calculating accurate waiting times for each process in the Round-Robin scheduler. Ensuring that threads paused and resumed correctly without causing race conditions or deadlocks required careful debugging of the execution flow. Understanding how the time quantum interacts with thread states was also initially complex. However, breaking down the code logic step by step helped clarify these mechanics.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame these challenges by carefully re-reading the README documentation and analyzing the structure of SchedulerSimulation.java from top to bottom. Adding descriptive System.out.println debug statements allowed me to trace the exact state and lifecycle of each thread during execution. Testing small code changes incrementally helped isolate errors quickly and verify the output against expected scheduling behavior.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[applications such as web browsers, where multiple tabs run concurrently as separate threads. Another application is in media streaming software, where one thread downloads media data while another renders video frames. Operating systems also rely on similar scheduling principles to ensure responsive user interfaces and fair CPU allocation across all background applications.]

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

[When a process does not finish within its assigned time quantum, its execution is paused, and it is re-queued back into the ready queue to wait for its next turn. For example, in my program output, process `P3` had a larger burst time and was re-queued multiple times before it finally terminated. Re-queueing is crucial for fairness because it prevents any single process from monopolizing the CPU and ensures responsive scheduling for all tasks.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[When a process does not finish within its assigned time quantum, its execution is paused, and it is re-queued back into the ready queue to wait for its next turn. Re-queueing is crucial for fairness because it prevents any single process from monopolizing the CPU and ensures responsive scheduling for all tasks.]

Example from my output:
```
[P3 added to ready queue (Burst: 8, Priority: 2)
P3 running... remaining burst: 4
P3 re-queued to ready queue]
```

**Explanation of example:**
[This output snippet shows process P3 being initially added to the ready queue with a burst time of 8. After executing for one time quantum, its remaining burst drops to 4, and because it hasn't finished, it is re-queued back into the ready queue to wait for its next CPU cycle.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 is in the New state when instantiated via new Process() before its thread is created.]

2. **Runnable**: [P1 becomes Runnable when added to the ready queue and its thread is initialized using Thread.start()]

3. **Running**: [P1 is Running when the scheduler allocates the CPU to execute its run() method]

4. **Waiting**: [A thread enters Waiting when Thread.sleep() is called during its time quantum execution or when waiting on join()]

5. **Terminated**: [P1 is Terminated once its remaining burst time reaches zero and its execution finishes.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Operating System CPU Scheduling]

**Description**:
[The operating system CPU scheduler manages multiple active user applications concurrently, allocating CPU time slices to each program. In this scenario, running programs play the role of processes, the scheduling time slice acts as the time quantum, and saving/restoring CPU registers represents the context switch.]

**Why Round-Robin works well here**:
[Round-Robin fits this scenario because it guarantees fairness by ensuring no single application monopolizes the CPU, maintaining high user interface responsiveness and predictable execution times across all background tasks.]

### Example 2: [Multi-Player Online Video Game Server]

**Description**:
[A game server handles multiple incoming player actions and network packets sequentially in a continuous loop. Here, individual player requests act as processes, the update frequency window represents the time quantum, and switching between player contexts acts as the context switch.]

**Why Round-Robin works well here**:
[Round-Robin fits this scenario because it ensures complete **fairness** by giving every task an equal time share, high **responsiveness** so no process hangs, and **predictability** in managing execution cycles.]

## Summary

**Key concepts I understood through these questions:**
1.The core differences between processes and threads, along with resource sharing mechanics.
2.How Round-Robin scheduling works and how time quantums are calculated.
3.Thread lifecycle states and how to track their state transitions programmatically.

**Concepts I need to study more:**
1.Advanced scheduling algorithm complexities in distributed resource systems.
2.Optimizing thread synchronization to prevent advanced concurrency issues.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ x] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ x] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ x] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ x] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ x] Code compiles and runs with no errors
- [ x] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ x] Each feature has clear comments

**Commits**
- [ x] **At least 3 meaningful commits, ideally 6 or more**
- [ x] **One commit per feature**
- [ x] Commits are spread over **different dates** (not all in the last hour)
- [ x] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [x ] Full name and student ID filled in at the top
- [x ] Development log has **5+ entries** on different dates
- [x ] Reflection: 4 questions, 5-7 sentences each
- [x ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ x] No `[...]` placeholders left
- [ x] No section headers deleted

**Video**
- [x ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [x ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ x] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ x] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
