# Predator-Prey Q-learning for Swarm Coverage Path Planning
 
## Introduction
This repository contains the code for my 3rd year university project. The project was completed without the use of git and uploaded in its entirety after.

The aim of the project was to improve an existing method of coverage. I choose to do this by augmenting Q-learning using a predator-prey method I found. I worked to implement this augmented method into a swarm of agents which work to collectively cover an environment.

## Files
The progress through the project is documented in the numbered files. Starting with the simplest method and working towards the full implementation. Using separate files allowed me to test the new methods against the earlier versions.

1. This was the first step and is the creation of an environment and agent will be used to test the RL algorithms. To begin with the aim is to find a single point in the environment.
2. The creation of the swarm was next, this step is similar to the previous one however there are no multiple agents working to find multiple targets.
3. Coverage was next, this program focuses on moving from target tracking to coverage. It also reverts back to a single agent for simplicity.
4. The next step was then to add a swarm into the coverage scenario, ensuring that the agents of the swarm share knowledge of what they have visited. 
5. This program focuses on improving other parts of the program such as allowing a variable number of agents. This was important to make testing easier.
6. This was the most important step in development, I tested different methods to improve the normal Q-learning. I eventually decided on Predator-Prey over Double Q, I then implemented an adapted version of the predator-prey method that allows it to work within a swarm.
7. This step focuses on improving the outputs of the code to create better visual aids which could be used in the paper.
8. These programs combine code from previous steps together so that I can produce graphs for the paper.
9. This is the final form of the program, it is the cleaned up version which includes only what is needed to run the algorithm and see the results.