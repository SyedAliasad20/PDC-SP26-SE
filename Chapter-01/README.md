# Chapter 01 – Introduction to Parallel and Distributed Computing

## Overview

This chapter introduces the fundamental concepts of parallel and distributed computing. It focuses on how computational tasks can be divided and executed simultaneously to improve performance and efficiency.

---

## Objectives

* Understand the difference between sequential and parallel execution
* Learn basic concepts of multiprocessing and threading
* Analyze performance improvements using parallel execution

---

## Folder Structure

```
Chapter-01/
│── Code/        # Python implementation files
│── Output/      # Screenshots of code and execution results
│── README.md    # Documentation
```

---

## Key Concepts

| Concept              | Description                            |
| -------------------- | -------------------------------------- |
| Sequential Execution | Tasks run one after another            |
| Parallel Computing   | Multiple tasks run at the same time    |
| Threading            | Lightweight process for parallel tasks |
| Multiprocessing      | Running tasks using multiple CPU cores |

---

## Visual Analysis (Quick Understanding)

### Execution Comparison

```
Sequential Execution:
Task1 → Task2 → Task3 → Task4

Parallel Execution:
Task1 ┐
Task2 ├──→ Execute Together → Faster Result
Task3 ┤
Task4 ┘
```

### Performance Insight

| Execution Type | Time Taken | Efficiency |
| -------------- | ---------- | ---------- |
| Sequential     | High       | Low        |
| Parallel       | Low        | High       |

---

## Implementation Summary

* Implemented basic Python programs for parallel execution
* Used multiprocessing and threading concepts
* Observed reduced execution time compared to sequential programs

---

## Output

All execution screenshots are available in the **Output/** folder, including:

* Code execution results
* Performance comparison outputs

---

## Learning Outcome

* Clear understanding of how parallel computing improves performance
* Ability to implement basic multiprocessing in Python
* Practical knowledge of execution flow differences

---

## Conclusion

Parallel computing significantly enhances performance by executing multiple tasks simultaneously. This chapter builds the foundation for advanced parallel programming concepts used in real-world systems.
