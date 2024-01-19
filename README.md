# Markov Chain and 1-D Random Walk

## Markov Chain Analysis
This README provides an analysis of an assignment that studies the writing process in four stages: read (r), write (w), e-mail (e), and surf (s). The process is modeled as a finite state discrete time Markov chain.

## Question 1: Markov Chain Analysis (10 Marks)

### Overview
Let's consider a paper-writing process with four stages: read (r), write (w), e-mail (e), surf (s). The process is modeled as a finite state discrete time Markov chain.

### Transition Probability Matrix
The one-step transition probability matrix, P, is given by:

```
P =
| r   w   e   s |
|---|---|---|---|
| 0.5  0.3  0   0.2 |
| 0.2  0.5  0.1  0.2 |
| 0.1  0.3  0.3  0.3 |
| 0    0.2  0.3  0.5 |
```

### Questions and Answers

#### (a) Evolution after 20 minutes
Suppose time (t) is measured in minutes (discrete). The Markov chain's evolution after 20 minutes is demonstrated. Additionally, P(X20 = s|X0 = r) is calculated.

#### (b) Evolution after 25 minutes
Similar to (a), the Markov chain's evolution after 25 minutes is explored. P(X25 = s|X20 = s) is also calculated.

#### (c) Stationary distribution
The existence of a stationary distribution is discussed, and if it exists, its values are determined.

#### (d) Limiting distribution
The existence of a limiting distribution is discussed, and if it exists, its values are determined.

---

## Question 2: 1-D Random Walk (10 Marks)

### Overview
This section explores a 1-D random walk starting from state i.

#### (a) Simulation for p = 0.5 and 500 steps
A 1-D random walk is simulated for p = 0.5 over 500 steps. The results are plotted, and the simulated probability is calculated.

#### (b) Simulation for p = 0.8 and 500 steps
A 1-D random walk is simulated for p = 0.8 over 500 steps. The results are plotted, and the simulated probability is calculated. A comparison with part (a) is made.

#### (c) Simulation for p = 0.8, 500 steps, repeated 1000 times
A 1-D random walk is simulated for p = 0.8 over 500 steps, and the process is repeated 1000 times. The results are plotted, and a comparison with part (b) is made.

---
