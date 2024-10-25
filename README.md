 





<h1>CNN-model-Pacman-game</h1>

 

<h2>Description</h2>

<br />
In this project, I developed an advanced AI model based on Deep Convolutional Q-Learning to train an agent capable of playing Pac-Man. The model integrates a Convolutional Neural Network (CNN) and a fully connected neural network to process the visual inputs of the game. By combining CNN for image recognition and Deep Q-Learning for decision-making, the AI agent is able to "see" the game screen and take actions based on the rewards from the environment, learning optimal strategies over time. (CNN).

The goal of this project was to implement a model that learns to master Pac-Man autonomously, improving performance by playing numerous rounds and learning from experience.
<br />




<h2>Languages and Utilities Used</h2>

- <b>Python: Core programming language.</b>
- <b>Gymnasium (LunarLander-v2): Simulation environment for training the agent.</b>
- <b>PyTorch: Deep learning framework used to implement and train the DQN model.</b>
- <b>Deep Q-Learning (DQN): Reinforcement learning algorithm that combines Q-learning with deep neural networks for decision-making.</b>


<h2>Objective</h2>

- <b>Train an AI agent to perform safe and efficient lunar landings by optimizing its actions through reinforcement learning.</b> 
- <b>The project demonstrates the application of AI in solving complex control problems in a simulated space environment.</b> 


<h2>Walk-through:</h2>

<p align="center">
Diagram: <br/>
<img src="[https://github.com/Vlad774/ActiveDirectoryLab/blob/main/Creating%20Users%20script.jpg](https://github.com/Vlad774/ActiveDirectoryLab/blob/main/diagram.jpg)"/>
<br />
<br />
First try: Episodes - 904 | Score rate - 200.65  <br/>
<img src="https://github.com/Vlad774/Deep-Q-Learning-for-Lunar-Landing/blob/main/AutoLanding_v1.gif"/>
<br />
<br />
Second try: Episodes - 360 | Score rate - 201.64 <br/>
<img src="https://github.com/Vlad774/Deep-Q-Learning-for-Lunar-Landing/blob/main/AutoLanding_v2.gif"/>
<br />
<br />
Third try: Episodes - 299 | Score rate - 201.33  <br/>
<img src="https://github.com/Vlad774/Deep-Q-Learning-for-Lunar-Landing/blob/main/AutoLanding_v3.gif"/>
<br />
<br />
Four try: Episodes - 364 | Score rate - 202.72  <br/>
<img src="https://github.com/Vlad774/Deep-Q-Learning-for-Lunar-Landing/blob/main/AutoLanding_v4.gif"/>


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
