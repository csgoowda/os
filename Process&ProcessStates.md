
# 🧠 OS — Day 2

# **Process & Process States (Very Important)**

---

# 🖥️ What is a Process?

**Interview Definition:**
A **process** is a **program in execution**.

👉 When you run a program, it becomes a **process**.

---

## ✅ Example of Process

Running:

* Chrome
* VS Code
* Calculator

Each running application is a **separate process**.

---

## 🎯 Interview Tip

**Program vs Process** (Very commonly asked)

| Program              | Process             |
| -------------------- | ------------------- |
| Passive              | Active              |
| Stored on disk       | Running in memory   |
| Example: `.exe` file | Running application |

**Simple Line to Say:**

> A program becomes a process when it starts executing.

---

# 🔄 Process States (Very Important)

A process moves through **5 states**.

These states are **frequently asked in exams and interviews**.

---

## 1️⃣ New State

**Meaning:**
Process is **being created**.

Example:

* You click **VS Code**
* OS creates process

---

## 2️⃣ Ready State

**Meaning:**
Process is **ready to run**, waiting for CPU.

Important:

👉 Process is in memory
👉 Waiting for CPU time

---

## 3️⃣ Running State ⭐

**Meaning:**
CPU is **executing the process**.

Only **one process runs at a time per CPU core**.

---

## 4️⃣ Waiting State (Blocked)

**Meaning:**
Process is **waiting for input/output**.

Example:

Waiting for:

* Keyboard input
* File read
* Network data

---

## 5️⃣ Terminated State

**Meaning:**
Process has **finished execution**.

Example:

* You close calculator

---

# 🔁 Process Flow Diagram (Must Remember)

This is very important.

```
New → Ready → Running → Waiting → Ready → Running → Terminated
```

**Key Idea:**

Running → Waiting happens when:

👉 Process needs input/output.

Waiting → Ready happens when:

👉 Input/output finishes.

---

# 📊 Process States Summary Table

| State      | Meaning                  |
| ---------- | ------------------------ |
| New        | Process created          |
| Ready      | Waiting for CPU          |
| Running    | CPU executing            |
| Waiting    | Waiting for input/output |
| Terminated | Process finished         |

---

# 🧠 Process Control Block (PCB) ⭐ (Very Important)

Most students forget this — but **interviewers ask this**.

---

## What is PCB?

**Definition:**
PCB (**Process Control Block**) is a **data structure** used by OS to store **process information**.

OS uses PCB to **manage processes**.

---

## 📦 Information Stored in PCB

PCB stores:

* Process ID (**PID**)
* Process State
* Program Counter
* CPU Registers
* Memory Information
* Scheduling Information

---

## 🎯 Simple Interview Line

> PCB stores all important information about a process.

---

# 🔄 Context Switching ⭐ (Very Important)

Another **frequently asked topic**.

---

## What is Context Switching?

**Definition:**
Context Switching is the **process of saving one process state and loading another process state**.

Done by **CPU scheduler**.

---

## Simple Example

Imagine:

You are:

* Watching YouTube
* Writing code

CPU switches between them.

That switching is:

👉 **Context Switching**

---

## Steps in Context Switching

1️⃣ Save current process state
2️⃣ Load next process state
3️⃣ Resume execution

---

## Important Note

Too many context switches:

❌ Reduce performance
❌ Increase overhead

---

# 🎯 Most Asked Interview Questions

Practice these:

1️⃣ What is a process?
2️⃣ Difference between program and process
3️⃣ What are process states?
4️⃣ What is PCB?
5️⃣ What is Context Switching?
6️⃣ What happens in waiting state?

---



