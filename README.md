# 🍝 Philosophers: Concurrency & Synchronization

**A simulation of the classic Dining Philosophers problem to master Multi-Threading and Mutexes.**
This project focuses on solving race conditions and preventing deadlocks in a resource-constrained environment.

![Language](https://img.shields.io/badge/Language-C-blue) ![Topic](https://img.shields.io/badge/Topic-MultiThreading-orange)

## 🧠 Core Concepts

The goal is to keep a group of philosophers alive while they share limited resources (forks) under strict timing constraints.

* **Thread Management:** Creating and managing threads using `pthread`.
* **Synchronization:** Using **Mutexes** to protect shared memory resources and prevent data races.
* **Deadlock Prevention:** Implementing algorithms to ensure resource availability without blocking the system.
* **High-Precision Timing:** Managing time in milliseconds (`gettimeofday`) to check for starvation status.

## 🏥 Relevance to AI/Engineering
Understanding concurrency and thread safety is fundamental for **High-Performance Computing**, parallel data processing, and optimizing GPU utilization in modern AI pipelines.

## 🚀 Usage
```bash
make
# ./philo [number_of_philos] [time_to_die] [time_to_eat] [time_to_sleep]
./philo 5 800 200 200
