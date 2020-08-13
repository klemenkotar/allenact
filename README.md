
<div align="center">
    <br>
    <img src="docs/img/placeholderLogo.png" />
    <br>
    <i>An open source Framework for Reproducible, Reusable, and Robust Embodied-AI Research.</i>
    </p>
    <hr/>
</div>

AllenAct is a modular and flexible learning framework designed with a focus on the unique requirements of Embodied-AI research. It provides first-class support for a growing collection of embodied environments, tasks and algorithms, provides reproductions of state-of-the-art models and includes extensive documentation, tutorials, start-up code, and pre-trained models.

## Quick Links

- [Website - TODO](https://allenact.org/)
- [Github - TODO](https://github.com/allenai/allenact)
- [Documentation - TODO](https://allenact.org/)
- [Install](docs/getting_started/installation.md)
- [Tutorials](docs/tutorials/minigrid-tutorial.md)
- [Contributing Guidelines](CONTRIBUTING.md)
- [Citation](#citation)

## Features & Highlights

* _Support for multiple environments_: We provide support for the [i-THOR](https://ai2thor.allenai.org/ithor/), [Robo-THOR](https://ai2thor.allenai.org/robothor/) and [Habitat](https://aihabitat.org/) embodied environments as well as for grid-worlds including [MiniGrid](https://github.com/maximecb/gym-minigrid).
* _Task Abstraction_: Tasks and environments are decoupled in AllenAct, enabling researchers to easily implement a large variety of tasks in the same environment.
* _Algorithms_: We provide support for a variety of on-policy algorithms including [PPO](https://arxiv.org/pdf/1707.06347.pdf), [DD-PPO](https://arxiv.org/pdf/1911.00357.pdf), [A2C](https://arxiv.org/pdf/1611.05763.pdf), Imitation Learning and [DAgger](https://www.ri.cmu.edu/pub_files/2011/4/Ross-AISTATS11-NoRegret.pdf) as well as offline training such as offline IL.
* _Sequential Algorithms_: AllenAct makes it trivial to experiment with different sequences of training routines, which are often the key to successful policies.
* _Simultaneous Losses_: AllenAct allows researchers to easily combine various losses while training models (for instance, use an external self-supervised loss while optimizing a PPO loss).
* _Multi-agent support_: AllenAct provides support for multi-agent algorithms and tasks.
* _Visualizations_: We provide out of the box support to easily visualize first person and third person cameras for agents as well as intermediate model tensors, integrated into Tensorboard.
* _Pre-trained models_: AllenAct provides code and models for a number of standard Embodied AI tasks.
* _Tutorials_: We provide start-up code and extensive tutorials to help ramp up new researchers to the field of AllenAct.
* _First-class PyTorch support_: While many well-developed libraries exist for reinforcement learning in 
   Tensorflow, we are one of a few to target PyTorch.

## Contributions
We welcome contributions from the greater community. If you would like to make such a contributions we recommend first submitting an [issue](https://github.com/allenai/allenact/issues) describing your proposed improvement. Doing so can ensure we can validate your suggestions before you spend a great deal of time upon them. Improvements and bug fixes should be made via a pull request from your fork of the repository at [https://github.com/allenai/allenact](https://github.com/allenai/allenact).

All code in this repository is subject to formatting, documentation, and type-annotation guidelines. For more details, please see the our [contribution guidelines](CONTRIBUTING.md).

## Acknowledgments
This work builds upon the [pytorch-a2c-ppo-acktr](https://github.com/ikostrikov/pytorch-a2c-ppo-acktr-gail) library of Ilya Kostrikov and uses some data structures from FAIR's [habitat-api](https://github.com/facebookresearch/habitat-api).

## License
AllenAct is MIT licensed, as found in the [LICENSE](LICENSE.md) file.

## Team
AllenAct is an open-source project built by members of the PRIOR research group at the Allen Institute for Artificial Intelligence (AI2). AI2 is a non-profit institute with the mission to contribute to humanity through high-impact AI research and engineering.

<div align="left">
    <br>
    <img src="docs/img/PRIORLogoBlackEmbedded.png">
     &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
    <img src="docs/img/AI2_Logo_Square_Gradients_crop.png">
    <br>
</div>

## Citation
If you use this work, please cite:

```bibtex
@article{AllenAct,
  author = {Luca Weihs and Jordi Salvador and Klemen Kotar and Unnat Jain and Kuo-Hao Zeng and Roozbeh Mottaghi and Aniruddha Kembhavi},
  title = {AllenAct: A Framework for Reproducible, Reusable, and Robust Embodied AI Research},
  year = {2020},
  journal = {arXiv},
}

```


