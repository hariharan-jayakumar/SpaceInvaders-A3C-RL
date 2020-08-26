## Motivation

Reinforcement Learning has produced a lot of excitement in the AI community because of it's tendency to act based on rewards - which is very similar to how human brains work. When combined with Deep Learning, we move closer to simulating the workings of a human brain - and hence inch closer to the dream of 'True Artifical Intelligence'.

I used this project to learn try my hand at Reinforcement Learning, picking the stock example of training a RL agent to play the Atari Space Invaders game.

## Team-Mate

Nihal Das

## Important Learnings

OpenAI gym
Deep Q Learning
Asynchronous Advantage Actor-Critic
Parallel Computing

## Observations

During our experimentation, we realized how sensitive RL algorithms were to the hyper-parameters used - small changes in hyper-parameter lead to a large effect on it's performance. While working with DQN especially, the model often became unstable during training (even with experience replay) and was unable to cross the score of 300.

A3C (for GPU) algorithm offered much more stability during training - as a result of multiple processes collecting different learnings and feeding these learnings to each other, the system was able to learn from more diverse learnings and became more adept at playing the game.

## Results

We trained our agent using the A3C algorithm, to achieve a score of 1000 points (This score can be improved significantly by training it longer in GPUs. It is worth noting that RL agents using A3C and trained for sufficient time have effectively 'solved' the game)

## Achievements

Submitted as part of a competition for Qualcomm employees, I teamed up with Nihal Das and our submission ranked #10th in the overall rankings. 

## Future Work

Apply RL algorithms to other novel use-cases

## Project Reference

https://github.com/dgriff777/a3c_continuous
