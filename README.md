# Reinforcement Learning — Coursework

Assignments, notes and exams from three reinforcement learning courses, from
tabular methods to deep and offline RL. Notebooks are committed with their
outputs.

![Map of RL methods](assets/rl-methods.png)

## 1402-2 · Dr. Rohban (Sharif)

| Folder | Topic |
|---|---|
| [`HW1`](1402-2-rohban/HW1) | Theory assignment and its solution (PDF) |
| [`HW2`](1402-2-rohban/HW2) | Monte Carlo and TD control; a DQN agent with replay memory |
| [`HW3`](1402-2-rohban/HW3) | On-policy methods: REINFORCE and PPO |
| [`HW4`](1402-2-rohban/HW4) | Offline RL: online vs. offline SAC, behavioural cloning |
| [`exams`](1402-2-rohban/exams) | Quiz 1 and 2 keys, the final with solutions, and the previous year's final |
| [`notes`](1402-2-rohban/notes) | My notes for the course (see below) |

`course-schedule.jpg` and `RL_02_03_Spring_Syllabus_Public.xlsx` give the session
plan.

### Notes

- [`notes/handwritten-notes.pdf`](1402-2-rohban/notes/handwritten-notes.pdf) —
  my handwritten notes for the whole course (71 pages, mixed Persian/English).
- [`notes/annotated-slides/`](1402-2-rohban/notes/annotated-slides) — the
  lecture slides with my annotations, numbered by session: MDPs and dynamic
  programming, Monte Carlo, TD learning, function approximation, policy
  gradients, actor-critic, TRPO/PPO, soft actor-critic, exploration,
  model-based RL, imitation learning and inverse RL. Files ending in
  `_board-notes` are the whiteboard notes from class.

## 1401-2 · Dr. Rohban (Sharif)

The previous offering of the same course: assignment notebooks and PDFs
(HW0–HW4: tabular methods, CartPole, PPO vs. DDPG, MCTS and Thompson
sampling, soft actor-critic), each with the published reference solutions.
The `*_98102176` solutions are by Alireza Gargoori.

Papers referenced in the HW3 solutions:
- W. Shi, S. Song, C. Wu — *Soft Policy Gradient Method for Maximum Entropy Deep
  Reinforcement Learning*, IJCAI 2019 — [pdf](https://www.ijcai.org/proceedings/2019/0475.pdf)
- S. Levine — *Reinforcement Learning and Control as Probabilistic Inference:
  Tutorial and Review*, 2018 — [arXiv:1805.00909](https://arxiv.org/abs/1805.00909)

## 1399-2 · Dr. Golestani

| File | Topic |
|---|---|
| [`HW1`](1399-2-golestani/HW1.ipynb) | Policy iteration on a grid world |
| [`HW2`](1399-2-golestani/HW2.ipynb) | Exploration: ε-greedy vs. softmax, zero vs. optimistic initialisation |
| [`HW3`](1399-2-golestani/HW3.ipynb) | Deep Q-learning on Atari |

Each notebook also has an `.html` export.

## Books and other references

- R. S. Sutton, A. G. Barto — *Reinforcement Learning: An Introduction*, 2nd
  ed., MIT Press, 2018 — free at [incompleteideas.net](http://incompleteideas.net/book/the-book-2nd.html)
- A. Plaat — *Deep Reinforcement Learning*, Springer, 2022 — [arXiv:2201.02135](https://arxiv.org/abs/2201.02135)
- D. Silver et al. — *Mastering Chess and Shogi by Self-Play with a General
  Reinforcement Learning Algorithm* (AlphaZero), 2017 — [arXiv:1712.01815](https://arxiv.org/abs/1712.01815)
- Berkeley CS 285, *Deep Reinforcement Learning* — [course page](https://rail.eecs.berkeley.edu/deeprlcourse/)

The plain lecture slides of these courses are not stored here.
