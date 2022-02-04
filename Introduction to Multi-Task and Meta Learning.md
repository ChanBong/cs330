---
tags:
- course
- stanford
- meta_rl
- ai
- rl
- 330/1
people:
- finn_c
review_status: false
alias: Course Introduction and Start of Multi-Task Learning
---

# [Introduction to Multi-Task and Meta Learning](Introduction%20to%20Multi-Task%20and%20Meta%20Learning.md)
Home : [README](README.md)

## Learning Objective
- Why study multi-task learning and meta-learning ?

## Summary 

## Notes
### Topics 
1. Multi-task learning, transfer learning basics 
2. Meta-learning algorithms (black-box approaches, optimization-based meta-learning, metric learning) 
3. Advanced meta-learning topics (meta-overfitting, unsupervised meta-learning, Bayesian models) 
4. Multi-task RL, goal-conditioned RL 
5. Meta-reinforcement learning 
6. Hierarchical RL 
7. Lifelong learning
8. Open problems

Topics we won't cover 
- AutoML
	- architecture search
	- hyperparameter optimization

### Why care about Meta Learning
- How can we enable agents to learn a collection of skills
	- They must generalize across tasks with some common sense understanding to do well 
	- Supervision can’t be taken for granted
- We are good at training a robot to do a single task but when the environment changes we have to learn the policy again from scratch
- Such algorithms train specialist in one task. Humans are generalist who can use their prior experience and can learn in a highly diverse environments

### Why should we care about deep multi-task and meta-learning 
- What if you want a more general-purpose AI system? 
	- Learning each task from scratch isn't gonna make it 
- What if you don't have a large dataset ?
- What if your data has a long tail ?
	- Very difficult to perform in relatively less encountered scenarios
- What if you have to quickly learn something new
	- About a new object, environment etc.

### Informal Definitions
- Task : Learning a objective function from a label space and a loss function 
- The multi-task learning problem: Learn all of the tasks more quickly or more proficiently than learning them independently.
- The meta-learning problem: Given data on previous tasks, learn a new task more quickly and/or more proficiently
- Critical Assumption : These tasks in a multi-task setting must share some common structure, otherwise you are better off learning them as a single task


## Lectures and Readings 
**Required**
- Lecture Notes : [lecture_1](file:///C:/Users/ASUS/Documents/spring_2022/cs330/lecture_1/cs330_intro_2021.pdf)

**Optional**
- [Pytorch Tutorial]()

## Exercise
- 