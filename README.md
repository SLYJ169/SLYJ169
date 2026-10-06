### Hi 👋

Working on **Embodied AI / Vision-Language-Action (VLA) / Robot Learning**, with hands-on experience in real-robot VLA deployment and reinforcement-learning post-training.

Recent projects:

- **[SO-101 Multi-Model VLA Benchmark](https://github.com/SLYJ169/so101-vla-benchmark)**  
  Built a real-robot benchmark on the same **SO-101 + Front/Wrist dual-camera** setup and the same 50-episode dataset. Trained/deployed **ACT, SmolVLA and π0.5**, with final task completion of **75% / 85% / 95%** over 20 trials. Also evaluated π0.5 on unseen objects and implemented a continuous autonomous picking workflow for SmolVLA.

- **[G1 + Dex3 VLA RL Post-Training](https://github.com/SLYJ169/G1-dex3-vla-rl-post-training)**  
  Performed **full-parameter PPO post-training of GR00T-N1.5** for the Assemble Trocar task using **Unitree G1 29-DOF + Dex3 dual dexterous hands** in Isaac Sim / Isaac Lab. Completed **60 PPO updates, 7,680 trajectories and ≈1.97M environment steps** on 2× RTX PRO 6000 Blackwell, with stage-level profiling and failure analysis identifying **Align → Insert** as the main contact-rich bottleneck. The 10-env demo completed **8/10 tasks (80%)**.

#### Technical Focus

`VLA` · `Robot Learning` · `Reinforcement Learning` · `Embodied AI` · `LeRobot` · `OpenPI` · `GR00T` · `RLinf` · `Isaac Lab` · `JAX` · `PyTorch`
