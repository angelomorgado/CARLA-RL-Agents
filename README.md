# CARLA GymDrive

Carla GymDrive is a powerful framework designed to facilitate reinforcement learning experiments in autonomous driving using the Carla simulator. By providing a gymnasium-like environment, it offers an intuitive and efficient platform for training driving agents using reinforcement learning techniques.

## Citation

If you use Carla GymDrive in your research, please cite using the following citation:

**BibTeX:**
```bibtex
@misc{2024CARLAGymDrive,
  title = {CARLA-GymDrive: Autonomous driving episode generation for the Carla simulator in a gym environment.},
  author = {Ângelo Morgado and Nuno Pombo},
  year = {2024},
  url = {https://github.com/angelomorgado/CARLA-GymDrive},
  note = {Contact: angelo.morgado@ubi.pt}
}
```

**APA:**
```apa
Morgado, Â., \& Pombo, N. (2024). CARLA-GymDrive: Autonomous driving episode generation for the Carla simulator in a gym environment. email: angelo.morgado@ubi.pt. [Online]. Available: \url{https://github.com/angelomorgado/CARLA-GymDrive}.
```

## Agents

This branch contains the implementation of a couple of agents that can be used to train driving agents in the Carla simulator. The agents are implemented using the stable-baselines3 library, which provides a set of reinforcement learning algorithms, and thus we only need to define their architecture without worrying about the algorithm implementation.

There are currently 4 implemented agents:

- PPO End-to-End
- PPO Modular
- DQN End-to-End
- DQN Modular

Their architectures are defined in the `agents` folder.

---

## License

Carla GymDrive is licensed under the MIT License. See the [LICENSE](/LICENSE) file for details.

## Acknowledgements

Carla GymDrive is inspired by the open-source community and contributions from researchers and developers around the world. I would like to express our gratitude to the Carla team for providing an excellent simulator for autonomous driving research.

I would like to thank the user [song-hl](https://github.com/song-hl) for helping me debug the PPO custom feature extractor for the stable-baselines3 framework.
