# Homework #13: Multi-threaded Restaurant Simulation

## Overview
In this homework assignment, you are expected to demonstrate your understanding of multithreading and synchronization in Java by simulating a restaurant environment with multiple chefs preparing dishes concurrently.

## Task Description

### 1. Create a Multi-threaded Restaurant Simulation
Your simulation must represent a scenario where multiple chefs (threads) work together in a kitchen, each preparing different dishes.

### Requirements:
- Define any shared resources necessary for the task, such as a list of orders.
- Implement the `Chef` class, which will be responsible for the cooking process. Each chef is a separate thread.
- Manage thread lifecycle within the `Restaurant` main class, starting and coordinating the threads representing the chefs.

### 2. Implement Synchronization
Proper synchronization must be implemented to avoid conflicts, such as simultaneous use of shared kitchen resources (ovens, utensils, etc.).

### Possible Approaches:
- Utilize `synchronized` blocks or methods.
- Implement synchronization utilities such as `Locks` or `Semaphores`.

## Submission
Your completed Java program should be submitted by the next session. Please include comments in your code to detail your approach and explain how synchronization is handled.

Good luck, and happy coding!
