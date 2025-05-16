# Introduction to MuJoCo

MuJoCo is a free and open-source physics engine designed to facilitate research and development in robotics, biomechanics, graphics, and animation, providing fast and accurate simulation capabilities.

* **MuJoCo**: **Mu**lti-**Jo**int dynamics with **Co**ntact
* Rigid-body simulation
* Essential simulator components:

  * Solving equations of motion (e.g., articulated body algorithms)
  * Contact solver (key factor for sim-to-real gaps)
  * User-friendly visualizer

## Tutorial Topics

1. Introduction to `MuJoCo` and `mujoco_parser`
2. Forward Kinematics
3. Forward Dynamics
4. Inverse Kinematics
5. Inverse Dynamics
6. Planning with `RRT`
7. Vision Reasoning with `GPT4o` and Open-Vocab Detection
8. Motion Retargeting for Unitree `G1`
9. PID Control for `Snapbot`
10. Reinforcement Learning with `Soft Actor-Critic` for `Snapbot`

---

## Project: Snapbot Olympics

### Overview

Optimize robotic motion using reinforcement learning. Train and evaluate control policies in simulation for various competition tasks.

### Events

* **Standing Long Jump:** Forward distance achieved by robot after jumping
* **High Jump:** Vertical height achieved by robot
* **Running Sideways:** Time to reach designated goal coordinate (faster is better)

### Simulation

* All tasks conducted in MuJoCo

### Provided Resources

* Snapbot robot model (`XML`)
* SAC algorithm implementation (`notebook/10_sac_snapbot_train.ipynb`, `notebook/10_sac_snapbot_eval.ipynb`, `pakage/gym/snapbot_env.py`, `pakage/rl/sac.py`)
* *(Reward functions must be designed by students)*

### Tasks

* Configure neural network dimensions based on robot DoF and action dimensions
* Design task-specific reward functions
* Train and evaluate policies
* Analyze reward function impact on performance

### Submission

* One-page A4 result report (must include reward definitions and model hyperparameters)
* Video of trained Snapbot performance

### Learning Outcomes

* Practical reinforcement learning experience
* Proficiency in task-specific reward design and evaluation
* Understanding neural network adjustments based on robot degrees of freedom

Aim to design the best policy and win the Snapbot Olympics!

---

### Contact

* **Prof. Sungjoon Choi:** [sungjoon dash choi at korea dot ac dot kr](mailto:sungjoon-choi@korea.ac.kr)
* **TA Taemoon Jeong:** [taemoon dash jeong at korea dot ac dot kr](mailto:taemoon-jeong@korea.ac.kr)
