# Optimized Exam Seating Algorithm

## What is this?
Using [this](https://ieeexplore.ieee.org/document/7514601) research paper, I will implement an algorithm that calculates the optimal exam seating for standardized exams to prevent cheating. This algorithm will partition students into two or more groups, and then seat them in such a way that:
- No student with a similar copy of the exam will sit next to each other.
- No student with a similar copy of the exam will be in direct eyesight of one another.
## How does it work?
Using a genetic algorithm, this code splits students into any groupSize >= 2, such that there will always be at *least* 2 sets of students with different exams. This ensures, in the slightest, that we can gurantee the previously mentioned parameters. 
## Why is this needed?
Cheating is, and always has been, an issue in higher level academia. Using such measures we can make systems that nearly gurantee that no student will have the ability to cheat. Malpractice research is not novel, and this algorithm intends to build on such research. 
