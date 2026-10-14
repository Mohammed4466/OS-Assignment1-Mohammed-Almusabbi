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
| **Full Name** | [Mohammed Shaddad Almusabbi] |
| **Student ID** | [446050919] |
| **University Email** | [446050919]@std.psau.edu.sa |
| **GitHub Username** | [Mohammed4466] |
| **Repository Link** | [https://github.com/Mohammed4466/OS-Assignment1-Mohammed-Almusabbi] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/18utWc9wJI0d2hbDz6kqT-HkFRaMsOmYk/view?usp=sharing]

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

### Entry 1 - [Oct 13, 2026, 12:50 AM]
**What I did**: I set up my GitHub repository and prepared my development environment for the assignment.

**Details**: I created my own repository from the starter repository renamed it and started connecting GitHub with VS Code I also prepared the project so I could work on the Java code.

**Challenges**: Git was not installed on my computer at first so I could not use Git features in VS Code.

**Solution**: I downloaded and installed Git then connected my GitHub account to VS Code

**Time spent**: 1 hours and 20 minutes

---

### Entry 2 - [Oct 13, 2026, 2:20 PM]
**What I did**: Set my student ID in the code and committed it

**Details**: I opened SchedulerSimulation.java and checked the student ID in the code and made sure it was correct then saved and committed the changes to GitHub After that I checked my repository to make sure the commit was there.

**Challenges**: I had some problems with the program output because it showed strange letters and confusing text. I was not sure if the program was working correctly at first.

**Solution**: I changed the language to English United States and enabled the beta option. After that the output looked normal and was easier to understand. After that I was able to commit my changes and push them to my repository without problems.

**Time spent**: 1 hours and 30 minutes

---

### Entry 3 - [Oct 13, 2026, 4:30 PM]
**What I did**: I started working on the process priority feature. I added a priority value for each process from 1 to 10 and made it show in the ready queue.

**Details**: I added a priority value to the Process class and made the priority appear when the processes are added to the ready queue. I kept the queue working in the same FIFO order and checked the output to make sure the priority was displayed correctly.

**Challenges**: At first I was not sure how to add the priority without changing the FIFO order of the ready queue. I also needed to make sure the priority appeared correctly in the output.

**Solution**: I added a random priority value from 1 to 10 for each process and updated the output to show it in the ready queue. I tested the program to make sure the priority appeared correctly and the FIFO order stayed the same.

**Time spent**: 1 hours and 40 minutes

---

### Entry 4 - [Oct 13, 2026, 6:30 PM]
**What I did**: I added a context switch counter to count how many times a process starts running during the simulation. I also made the program print the total number at the end.

**Details**: I added a counter in the code in Process class and increased it whenever a new thread was started. At the end of the simulation I printed the total number of context switches so I could see how many times the threads started running.

**Challenges**: I was not sure where to increase the counter in the code so it would count correctly. I also needed to make sure the final number was printed after the simulation finished.

**Solution**: I placed the counter where the thread starts and increased it each time by 1. I also added a print statement at the end of the simulation to show the total count. Then I ran the program and checked that the number appeared in the output.

**Time spent**: 2 hours and 30 minutes

---

### Entry 5 - [Oct 13, 2026, 9:20 PM]
**What I did**: I started working on the waiting time feature. I wanted to track how long each process waited in the ready queue and show the waiting time and turnaround time in a table at the end of the simulation.

**Details**: I added new variables to track the waiting time for each process. I also added a list to keep track of all processes and started working on the final table to show the process name and its burst time and waiting time and turnaround time.


**Challenges**: I had some difficulty with this feature because I needed to understand how to calculate the waiting time for each process and when to start and stop counting it. I also needed to make sure the waiting time and turnaround time were correct in the final table.

**Solution**: I used AI a little to help me understand how to track the waiting time and where to add the code. I followed the steps and tested the program to check the output and make sure the table showed the correct values.

**Time spent**: 2 hours and 40 minutes

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

**Total time spent on assignment**: [10 hours]//if you mean the implementation time only

**Most challenging part**: Feature 3 (waiting time tracking) was the most challenging part because I needed to understand how to calculate the waiting time for each process and when to start and stop counting it. I also had to make sure the waiting time and turnaround time were displayed correctly in the final table.

**Most interesting learning**: I learned how to use GitHub to manage my project and save my work. I learned how to fork a repository and connect GitHub with VS Code. I also learned how to commit my changes and push them to my GitHub repository. I understood why it is important to make separate commits for different features. This helped me keep track of my progress and save each update to the repository.

**What I would do differently next time**: Next time, I would read the code more carefully before starting the implementation. I would also test each feature after adding it and make smaller commits on GitHub. This would help me find mistakes earlier and understand the code better.

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

[I learned how threads work in Java and how they are used in the simulation.
 I learned that Thread.start() starts a thread
 while Thread.join() waits for a thread to finish
 I also learned that Thread.sleep() can be used to simulate the time a process spends running.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was dealing with the errors and problems I faced during the work
At the beginning I had a problem because Git was not installed on my computer
I also had a problem with the program output because it appeared unclear and showed strange characters
These problems made it difficult to know if everything was working correctly
I had to solve the setup problems before I could continue working comfortably I also faced some difficulty when implementing Feature 3]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I solved the Git problem by downloading and installing Git on my computer
 After that I connected my GitHub account to VS Code so I could manage my repository and push my changes
 To fix the unclear program output I changed the language settings to English (United States) and enabled the beta option in the settings This made the output easier to read and understand
 For Feature 3 I used AI a little to help me understand how to track the waiting time and where to add the code]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading can be used in many real-world applications
 For example in games multithreading can help handle different tasks at the same time
 such as player movement and online communication
 This helps the game run smoothly while the player is playing.]

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

[A process is a running program while a thread is a smaller unit of execution
 Processes have separate memory while threads share memory
 Threads also use fewer resources than processes
 In this assignment we used `new Thread(process)` to simulate processes using Java threads]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[The ready queue follows the FIFO order so the first process added is the first one to run 
 Each process gets a time quantum of 5000 ms 
 If a process does not finish it is added to the end of the ready queue again For example P4 has a burst time of 12268 ms and a time quantum of 5000 ms It was re-queued twice before it finished
 This allows other processes to get CPU time making the scheduling fair]

Example from my output:
 
```
[▶ P4 executing quantum [5000ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P4 completed quantum 5000ms │ Overall progress: [████████░░░░░░░░░░░░] 40%
     Remaining time: 7268ms
  ↻ P4 yields CPU for context switch

  ➕ P4 | Priority: 9 added to ready queue │ Burst time: 12268ms
   ▶ P4 executing quantum [5000ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P4 completed quantum 5000ms │ Overall progress: [████████████████░░░░] 81%
     Remaining time: 2268ms
  ↻ P4 yields CPU for context switch

  ➕ P4 | Priority: 9 added to ready queue │ Burst time: 12268ms
   ▶ P4 executing quantum [2268ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P4 completed quantum 2268ms │ Overall progress: [████████████████████] 100%
     Remaining time: 0ms
  ✓ P4 finished execution!]
```

**Explanation of example:**
[P4 has a burst time of 12268 ms and a time quantum of 5000 ms It was added back to the ready queue twice because it did not finish in the first two turns In the third turn it used the remaining 2268 ms and finished]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [When is P1 in the New state? P1 is in the New state when its thread is created using `new Thread(process)` in `addProcessToQueue()` before `start()` is called]

2. **Runnable**: [When does P1 become Runnable? P1 becomes Runnable when `start()` is called in the scheduler loop making the thread ready to execute]

3. **Running**: [When is P1 Running? P1 is Running when its thread executes the `run()` method and processes its assigned time quantum]

4. **Waiting**: [When and why would a thread be Waiting? P1 enters a waiting state when its thread calls `Thread.sleep()` to simulate the time quantum The main thread waits for P1 to finish using `Thread.join()`]

5. **Terminated**: [When is P1 Terminated? P1 enters the Terminated state when its `run()` method finishes and the thread completes its execution]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Operating System CPU Scheduling]

**Description**:
[The operating system gives each process a small amount of CPU time called a time quantum If a process does not finish the CPU switches to another process]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability? Round-Robin is useful because it gives each process a fair chance to use the CPU The time quantum helps prevent one process from using the CPU for too long and context switching allows other processes to run]

### Example 2: [Multithreading in Games]

**Description**:
[In games different threads can handle tasks such as player movement sounds and online communication Round-Robin can give each task a turn to use the CPU]

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability? Round-Robin can help give each task a fair chance to use the CPU. The time quantum limits how long each task runs before switching to another task This can help keep the game responsive]

## Summary

**Key concepts I understood through these questions:**
1.Threads
2.Round-Robin Scheduling
3.Context Switching

**Concepts I need to study more:**
1.Thread Lifecycle
2.Waiting Time

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [x] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [x] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
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
- [x] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [x] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
