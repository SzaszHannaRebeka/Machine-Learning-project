Machine Learning project
===================================

Small project made during my Introduction to reinforcement learning course.  

Our task was to create an agent that can complete a task in a closed, 3D environment, using the C# language and Unity as the development environment.  

I chose my topic to be a little drone following orbs towards a portal in a dense forest created with invisible walls and trees for visuals.  

My agent gets rewarded every time it picks up an orb, the reward is higher the less steps the agent took to get there, and reward is deducted for every action it takes before reaching the portal, motivating the agent to get there as quickly as possible.  
The agent has been clashing into the walls to minimise the amount of lost reward thus it gets reward deducted the closer it clashes into the wall to its starting point.  
Once the agent reaches the portal its reward is increased by the number of orbs collected multiplied by the difference between the maximum steps allowed and the steps it took for the agent to reach the goal, further motivating it to complete the task as quickly as possible.
