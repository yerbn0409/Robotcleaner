# Robotcleaner
Algorithm to search for optimal cleaning path
Given input_Maze, This program finds the shortest path to travel each point at least once and return to the first point.. User can modify maze as 1 means obstacle and 0 means pass.
This program uses reinforcement learning. To be specific, at first this program shows random walk, giving feedback itself. If some choice results larger number of walk, later the possibility that choose that choice again will reduce.
Users can modify input_maze as 1 means obstacle 0 means passway. The more have this program iteration, the less number of walk will you observe. On the other hand, it is a stupid act to return to a cell that has just passed, even though it is not a dead end. So I put constraints on not making that choice.
After executing the code, press the Enter key in the console to move it to the learned path.
This program runs well whith python2 interpreter and made by Seo Hoon (Kyung Hee Univ, hhoon0001@naver.com).
