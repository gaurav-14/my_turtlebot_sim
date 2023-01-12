# my_turtlebot_sim #
Repository to test CI with gazebo simulator on self-hosted machine

## What it does? ##
1. Spawns turtlebot3 in a gazebo world.
2. mover.py moves it a certain distance
3. test_bot_moves.py test whether turtlebot3 actually moves that distance.

## Continuous Integration ##
Github CI is implemented for this repository for learning purpose.    
A self-hosted runner is installed on local machine where [test_sim.yml](.github/workflows/test_sim.yml) workflow is executed.   

Above testing is repeated whenever push is made to master branch of this repository.

## Reference ##
This repository is inspired from this blog:     
https://formant.io/news-and-blog/2022/06/14/development/creating-a-robotics-simulation-pipeline-with-github-actions-and-ros/

