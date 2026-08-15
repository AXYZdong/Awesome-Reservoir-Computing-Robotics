# Awesome-Reservoir-Computing-Robotics
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated collection of papers, codes, and software frameworks at the intersection of **Reservoir Computing** and **Robotics**, with a focus on **Perception, Navigation, and Control**.

We welcome your support — if you find this repository valuable, please consider giving it a ⭐ or sharing it with others.

> [!NOTE]
> Contributions are highly encouraged! If you spot any missing resources, feel free to submit a **Pull Request** or open an **Issue**. We look forward to collaborating with you to keep this collection comprehensive and up-to-date.


- [Robotics Perception](#reservoir-computing-in-robotics-perception)
  - [Visual Perception](#visual-perception)
  - [Auditory Perception](#auditory-perception)
  - [Tactile Perception](#tactile-perception)
  - [Olfactory Perception](#olfactory-perception)
- [Robotics Navigation](#reservoir-computing-in-robotics-navigation)
  - [Localization](#localization)
  - [Path Planning](#path-planning)
  - [Decision-Making](#decision-making)
- [Robotics Control](#reservoir-computing-in-robotics-control)
  - [Motion Control](#motion-control)
  - [Morphological Control](#morphological-control)
  - [Collaborative Control](#collaborative-control)
- [Implementations](#implementations)
  - [Hardware Implementations](#reservoir-computing-hardware-implementations)
  - [Software Frameworks](#reservoir-computing-software-frameworks)


## 📖 Overview

Reservoir Computing (RC) has emerged as a powerful paradigm for robotic applications, offering efficient temporal processing, low training cost, and compatibility with neuromorphic hardware. This repository systematically organizes resources spanning:

- **Perception** — Visual, auditory, tactile, and olfactory perception
- **Navigation** — Localization, path planning, and decision-making
- **Control** — Motion control, morphological control, and collaborative control

## 👀️ Reservoir Computing for Robotics Perception

### Visual Perception
| Paper                                                                                                                                   |  Year  |             Pub.             |                 Index Term                 |
|:----------------------------------------------------------------------------------------------------------------------------------------|:------:|:----------------------------:|:------------------------------------------:|
| [A near-infrared retinomorphic device with high dimensionality reservoir expression](https://doi.org/10.1002/adma.202411225)            |  2024  |      Advanced Materials      |   Infrared vision; Retinomorphic device    |
| [Ultralow-power machine vision with self-powered sensor reservoir](https://doi.org/10.1002/advs.202106092)                              |  2022  |       Advanced Science       |    In-sensor computing; Ultralow-power     |
| [Scaling up liquid state machines to predict over address events from dynamic vision sensors](https://doi.org/10.1088/1748-3190/aa7663) |  2017  | Bioinspiration & Biomimetics |  Dynamic vision sensor; Motion prediction  |
| [Event-based features for robotic vision](https://doi.org/10.1109/IROS.2013.6696960)                                                    |  2013  |             IROS             |   Event-based vision; Feature extraction   |

### Auditory Perception
| Paper                                                                                                                                                        | Year |                           Pub.                            |                  Index Term                   |
|:-------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:---------------------------------------------------------:|:---------------------------------------------:|
| [Flexible artificial vision computing system based on FeOx optomemristor for speech recognition](https://doi.org/10.1088/1674-4926/24080004)                 | 2025 |                 Journal of Semiconductors                 | Analogy signal processing; Speech recognition |
| [Dynamic-structured reservoir spiking neural network in sound localization](https://ieeexplore.ieee.org/document/10418107)                                   | 2024 |                        IEEE Access                        |     Sound localization; Dynamic structure     |
| [Hysteretic oscillator-based reservoir computing for audio waveform pattern recognition](https://ieeexplore.ieee.org/document/10651003)                      | 2024 |                           IJCNN                           |      Coupled oscillators; Audio waveform      |
| [A digital liquid state machine with biologically inspired learning and its application to speech recognition](https://ieeexplore.ieee.org/document/7024132) | 2015 | IEEE Transactions on Neural Networks and Learning Systems |   Speech recognition; Spike-based learning    |


### Tactile Perception
| Paper                                                                                                                                                                            | Year |                     Pub.                      |                    Index Term                     |
|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:---------------------------------------------:|:-------------------------------------------------:|
| [Tapered whisker reservoir computing for real-time terrain identification-based navigation](https://doi.org/10.1038/s41598-023-31994-x)                                          | 2023 |              Scientific Reports               |      Tapered whisker; Terrain identification      |
| [Ground reaction force estimation in a quadruped robot via liquid state networks](https://doi.org/10.1109/IJCNN55064.2022.9892423)                                               | 2022 |                     IJCNN                     | Ground reaction force estimation; Quadruped robot |
| [A tapered whisker-based physical reservoir computing system for mobile robot terrain identification in unstructured environments](https://doi.org/10.1109/LRA.2022.3146602)     | 2022 |     IEEE Robotics and Automation Letters      |      Tapered whisker; Terrain identification      |
| [Haptic feedback with a reservoir computing-based recurrent neural network for multiple terrain classification of a walking robot](https://doi.org/10.1007/978-3-030-27538-9_20) | 2019 | Intelligent Robotics and Applications (ICIRA) |      Terrain classification; Haptic feedback      |


### Olfactory Perception
| Paper                                                                                                                                                                                           | Year |               Pub.                |                   Index Term                   |
|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:---------------------------------:|:----------------------------------------------:|
| [High-speed olfactory perception with adaptive load balancing based on a laser array reservoir computing architecture](https://doi.org/10.1016/j.neunet.2025.108173)                            | 2026 |          Neural Networks          |  Chemical sensors; Continuous gas prediction   |
| [A bio-inspired neuromorphic olfaction system for highly sensitive and selective gas sensing at room temperature](https://doi.org/10.1016/j.snb.2025.138198)                                    | 2025 | Sensors and Actuators B: Chemical | Neuromorphic olfaction; Memristor; Gas sensing |
| [An artificial olfactory inference system based on memristive devices](https://doi.org/10.1002/inf2.12196)                                                                                      | 2021 |              InfoMat              | Artificial olfactory system; Memristive device |
| [Reservoir computing compensates slow response of chemosensor arrays exposed to fast varying gas concentrations in continuous monitoring](https://doi.org/10.1016/j.snb.2015.03.028)            | 2015 | Sensors and Actuators B: Chemical |  Chemical sensors; Continuous gas prediction   |



## 🧭 Reservoir Computing for Robotics Navigation

### Localization
| Paper                                                                                                                                                                                           | Year |      Pub.       |                     Index Term                     |
|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:---------------:|:--------------------------------------------------:|
| [Echo state network and variational autoencoder integrated with online optimization for robust pose estimation in unmanned surface vehicles](https://doi.org/10.1016/j.measurement.2026.121454) | 2026 |   Measurement   |     Unmanned surface vehicle; Pose estimation      |
| [Robot localization by echo state networks using RSS](https://doi.org/10.1007/978-3-319-04129-2_15)                                                                                             | 2014 |    Springer     |    Wireless sensor networks; Robot localization    |
| [Learning slow features with reservoir computing for biologically-inspired robot localization](https://doi.org/10.1016/j.neunet.2011.08.004)                                                    | 2012 | Neural Networks |         Slow feature analysis; Place cells         |
| [Supervised learning of internal models for autonomous goal-oriented robot navigation using reservoir computing](https://ieeexplore.ieee.org/document/5509212)                                  | 2010 |       ICRA      |    Goal-oriented navigation; Imitation learning    |
| [Event detection and localization for small mobile robots using reservoir computing](https://doi.org/10.1016/j.neunet.2008.03.010)                                                              | 2008 | Neural Networks | Robot localization; Event detection; Implicit map  |


### Path Planning
| Paper                                                                                                                                                               | Year |                               Pub.                               |                     Index Term                      |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:----------------------------------------------------------------:|:---------------------------------------------------:|
| [Prediction-based data collection of UAV-assisted maritime internet of things](https://doi.org/10.1016/j.vehcom.2024.100854)                                        | 2024 |                     Vehicular Communications                     |    Unmanned aerial vehicle; Trajectory planning     |
| [Swarm UAV networking with collaborative beamforming and automated ESN learning in the presence of unknown blockages](https://doi.org/10.1016/j.comnet.2023.109804) | 2023 |                        Computer Networks                         |   Distributed beamforming; Reinforcement learning   |
| [Mental simulation on reservoir computing as an efficient planning method for mobile robot navigation](https://doi.org/10.34385/proc.71.A3L-D-02)                   | 2022 | International Symposium on Nonlinear Theory and Its Applications |      Mental simulation; Reinforcement learning      |
| [Deep reinforcement learning for interference-aware path planning of cellular-connected UAVs](https://doi.org/10.1109/ICC.2018.8422706)                             | 2018 |      IEEE International Conference on Communications (ICC)       |     Interference-aware; Reinforcement learning      |
| [Predictive modeling of time-varying environmental information for path planning](https://ieeexplore.ieee.org/document/6722373)                                     | 2013 |  IEEE International Conference on Systems, Man, and Cybernetics  |  Predictive modeling; Path planning; Kalman filter  |


### Decision-Making
| Paper                                                                                                                                                           | Year |                                             Pub.                                             |                    Index Term                     |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:--------------------------------------------------------------------------------------------:|:-------------------------------------------------:|
| [Harnessing natural embodied intelligence for spontaneous jellyfish cyborgs](https://doi.org/10.1038/s41467-025-59889-7)                                        | 2025 |                                    Nature Communications                                     |  Embodied; Locomotion prediction; Motion capture  |
| [Brain-inspired neural network navigation system with hippocampus, prefrontal cortex, and amygdala functions](https://doi.org/10.1109/ISPACS51563.2021.9651058) | 2021 | International Symposium on Intelligent Signal Processing and Communication Systems (ISPACS)  | Brain-inspired network; Navigation; Service robot |
| [Modular reservoir computing networks for imitation learning of multiple robot behaviors](https://doi.org/10.1109/CIRA.2009.5423194)                            | 2009 | IEEE International Symposium on Computational Intelligence in Robotics and Automation (CIRA) |      Imitation learning; Obstacle avoidance       |
| [Modeling multiple autonomous robot behaviors and behavior switching with a single reservoir computing network](https://doi.org/10.1109/ICSMC.2008.4811557)     | 2008 |                IEEE International Conference on Systems, Man, and Cybernetics                | Imitation; Behavior switching; Multiple behaviors |
| [Mobile robot control in the road sign problem using reservoir computing networks](https://ieeexplore.ieee.org/document/4543321)                                | 2008 |                                             ICRA                                             |   T-maze task; Road sign problem; Mobile robot    |



## ⚙️ Reservoir Computing for Robotics Control

### Motion Control
| Paper                                                                                                                                                      | Year |                          Pub.                           |                   Index Term                    |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:-------------------------------------------------------:|:-----------------------------------------------:|
| [Transient-reinforced tunnel coordinated control of underactuated marine surface vehicles with actuator faults](https://doi.org/10.1109/TITS.2023.3324346) | 2024 | IEEE Transactions on Intelligent Transportation Systems |      Neural estimator; Coordinated control      |
| [An online learning strategy for echo state network](https://doi.org/10.1109/TSMC.2023.3319357)                                                            | 2024 |  IEEE Transactions on Systems Man Cybernetics-Systems   |     Time series prediction; Online learning     |
| [Model-free tracking control of complex dynamical trajectories with machine learning](https://doi.org/10.1038/s41467-023-41379-3)                          | 2023 |                  Nature Communications                  |     Nonlinear tracking control; Model-free      |
| [Reinforcement learning for quadrupedal locomotion with design of continual-hierarchical curriculum](https://doi.org/10.1016/j.engappai.2020.103869)       | 2020 |   Engineering Applications of Artificial Intelligence   | Quadrupedal locomotion; Reinforcement learning  |
| [A prey-predator model for efficient robot tracking](https://ieeexplore.ieee.org/document/7989409)                                                         | 2017 |                          ICRA                           |    Prey-predator model; Autoregressive model    |


### Morphological Control
| Paper                                                                                                                                         | Year |                 Pub.                 |                      Index Term                      |
|:----------------------------------------------------------------------------------------------------------------------------------------------|:----:|:------------------------------------:|:----------------------------------------------------:|
| [Limit cycle generation with pneumatically driven physical reservoir computing](https://doi.org/10.1109/ICRA48891.2023.10161315)              | 2023 |                 ICRA                 |  Pneumatic pipeline system; Limit cycle generation   |
| [Behavioral diversity generated from body–environment interactions in a simulated tensegrity robot](https://doi.org/10.1109/LRA.2021.3139083) | 2022 | IEEE Robotics and Automation Letters |       Tensegrity robots; Behavioral diversity        |
| [Physical reservoir computing with origami and its application to robotic crawling](https://doi.org/10.1038/s41598-021-92257-1)               | 2021 |          Scientific Reports          | Robotic crawling; Nonlinear dynamics; Soft Robotics  |
| [Locomotion without a brain: physical reservoir computing in tensegrity structures](https://doi.org/10.1162/ARTL_a_00080)                     | 2013 |           Artificial Life            |       Tensegrity structures; Embodied robotics       |
| [Online learning for behavior switching in a soft robotic arm](https://doi.org/10.1109/ICRA.2013.6630738)                                     | 2013 |                 ICRA                 |         Behavior switching; Soft robotic arm         |


### Collaborative Control
| Paper                                                                                                                                                                  | Year |                                  Pub.                                   |                       Index Term                        |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:-----------------------------------------------------------------------:|:-------------------------------------------------------:|
| [Learning-based optimal cooperative formation tracking control for multiple UAVs: a feedforward-feedback design framework](https://doi.org/10.1109/TASE.2023.3322028)  | 2025 |         IEEE Transactions on Automation Science and Engineering         | Cooperative formation tracking; Reinforcement learning  |
| [Echo state networks for embodied evolution in robotic swarms](https://doi.org/10.1007/s10015-022-00828-w)                                                             | 2023 |                      Artificial Life and Robotics                       |          Swarm robotics; Evolutionary robotics          |
| [Modular adaptive control for LOS-based cooperative path maneuvering of multiple underactuated autonomous surface vehicles](https://doi.org/10.1109/TSMC.2017.2650219) | 2017 |          IEEE Transactions on Systems Man Cybernetics-Systems           |       Modular adaptive control; Path maneuvering        |
| [An electromyography-driven central pattern generator model for robotic control application](https://doi.org/10.1109/ROBIO.2012.6491270)                               | 2012 |       IEEE International Conference on Robotics and Biomimetics (ROBIO) |       Central pattern generator; Electromyography       |



## Implementations
### Reservoir Computing Hardware Implementations

- FPGA-based Implementations

| Paper                                                                                                                                                                                    | Year |                                     Pub.                                      |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:-----------------------------------------------------------------------------:|
| [ SpikeSpec: an on-chip learning neuromorphic accelerator for spectrum sensing with triplet-boosting and hardware friendly loss function](https://ieeexplore.ieee.org/document/10891704) | 2025 | IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems |
| [Ghost reservoir: a memory-efficient low-power and real-time neuromorphic processor of liquid state machine with on-chip learning](https://ieeexplore.ieee.org/document/10511289)        | 2024 |         IEEE Transactions on Circuits and Systems II: Express Briefs          |
| [Adaptive input-to-neuron interlink development in training of spike-based liquid state machines](https://ieeexplore.ieee.org/document/9401085)                                          | 2021 |       2021 IEEE International Symposium on Circuits and Systems (ISCAS)       |
| [Energy efficient parallel neuromorphic architectures with approximate arithmetic on FPGA](https://www.sciencedirect.com/science/article/pii/S0925231216311213)                          | 2017 |                                Neurocomputing                                 |
| [Liquid state machine based pattern recognition on FPGA with firing-activity dependent power gating and approximate computing](https://ieeexplore.ieee.org/document/7527245)             | 2016 |         IEEE International Symposium on Circuits and Systems (ISCAS)          |
| [SSO-LSM: A Sparse and self-organizing architecture for liquid state machine based neural processors](https://ieeexplore.ieee.org/document/7568626)                                      | 2016 |    IEEE/ACM International Symposium on Nanoscale Architectures (NANOARCH)     |
| [General-purpose LSM learning processor architecture and theoretically guided design space exploration](https://ieeexplore.ieee.org/abstract/document/7348397)                           | 2015 |           IEEE Biomedical Circuits and Systems Conference (BioCAS)            |
| [Compact hardware liquid state machines on FPGA for real-time speech recognition](https://www.sciencedirect.com/science/article/pii/S0893608007002353)                                   | 2008 |                                Neural Networks                                |


- ASIC-based Implementations

| Paper                                                                                                                                                                   | Year |                               Pub.                                |
|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:-----------------------------------------------------------------:|
| [LSM-based hotspot prediction and hotspot-aware routing in NoC-based neuromorphic processor](https://ieeexplore.ieee.org/document/10486852)                             | 2024 |     IEEE Transactions on Very Large Scale Integration Systems     |
| [Neuromorphic on-chip reservoir computing with spiking neural network architectures](http://arxiv.org/abs/2407.20547)                                                   | 2024 |                               arXiv                               |
| [DNN-SNN co-learning for sustainable symbol detection in 5G systems on loihi chip](https://ieeexplore.ieee.org/document/10285018)                                       | 2024 |            IEEE Transactions on Sustainable Computing             |
| [Hardware-aware liquid state machine generation for 2D/3D network-on-chip platforms](https://www.sciencedirect.com/science/article/pii/S1383762122000297)               | 2022 |                  Journal of Systems Architecture                  |
| [Liquid state machine on loihi: memory metric for performance prediction](https://link.springer.com/content/pdf/10.1007/978-3-031-15934-3_57.pdf)                       | 2022 |          Artificial Neural Networks and Machine Learning          |
| [A long short-term memory for AI applications in spike-based neuromorphic hardware](https://www.nature.com/articles/s42256-022-00480-w)                                 | 2022 |                    Nature Machine Intelligence                    |
| [Liquid state machine on SpiNNaker for spatio-temporal classification tasks](https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2022.819063/full) | 2022 |                     Frontiers in Neuroscience                     |
| [A multi-objective LSM/NoC architecture co-design framework](https://www.sciencedirect.com/science/article/pii/S1383762121001119)                                       | 2021 |                  Journal of Systems Architecture                  |
| [A hardware aware liquid state machine generation framework](https://ieeexplore.ieee.org/document/9401057)                                                              | 2021 | 2021 IEEE International Symposium on Circuits and Systems (ISCAS) |


- Analog Circuit-based Implementations

| Paper                                                                                                                                                                     | Year |                                 Pub.                                 |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:--------------------------------------------------------------------:|
| [LSMR: synergy randomness in liquid state machine and RRAM-based analog-digital accelerator](https://dl.acm.org/doi/10.1145/3676536.3676691)                              | 2025 |  IEEE/ACM International Conference on Computer-Aided Design (ICCAD)  |
| [A neuransistor with excitatory and inhibitory neuronal behaviors for liquid state machine](https://onlinelibrary.wiley.com/doi/abs/10.1002/adma.202419122)               | 2025 |                          Advanced Materials                          |
| [Multilayer reservoir computing based on ferroelectric α-In2Se3 for hierarchical information processing](https://onlinelibrary.wiley.com/doi/abs/10.1002/adma.202108826)  | 2024 |                          Advanced Materials                          |
| [Leaky FinFET for reservoir computing with temporal signal processing](https://pubs.acs.org/doi/10.1021/acsami.3c02630)                                                   | 2023 |                  ACS Applied Materials & Interfaces                  |
| [Reservoir computing with biocompatible organic electrochemical networks for brain-inspired biosignal classification](https://www.science.org/doi/10.1126/sciadv.abh0693) | 2021 |                           Science Advances                           |
| [Toward real-time, at-home patient health monitoring using reservoir computing CMOS IC](https://ieeexplore.ieee.org/document/9617636)                                     | 2021 | IEEE Journal on Emerging and Selected Topics in Circuits and Systems |
| [Spatial-temporal hybrid neural network with computing-in-memory architecture](https://ieeexplore.ieee.org/document/9406054)                                              | 2021 |     IEEE Transactions on Circuits and Systems I: Regular Papers      |
| [Analog hardware implementation of spike-based delayed feedback reservoir computing system](https://ieeexplore.ieee.org/document/7966288)                                 | 2017 |      International Joint Conference on Neural Networks (IJCNN)       |


- Memristor-based Implementations

| Paper                                                                                                                                                                                          | Year |                               Pub.                               |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:----------------------------------------------------------------:|
| [A memristor-based event-driven reservoir computing system for cardiac arrhythmia detection](https://advanced.onlinelibrary.wiley.com/doi/10.1002/aisy.202500350)                              | 2025 |                   Advanced Intelligent Systems                   |
| [Spatiotemporal reservoir computing with a reconfigurable multifunctional memristor array](https://advanced.onlinelibrary.wiley.com/doi/10.1002/adma.202510635)                                | 2025 |                        Advanced Materials                        |
| [Brain-inspired reservoir computing using memristors with tunable dynamics and short-term plasticity](https://doi.org/10.1021/acsami.3c16003)                                                  | 2024 |                ACS Applied Materials & Interfaces                |
| [Memristor based liquid state machine with method for in-situ training](https://ieeexplore.ieee.org/document/10478203/)                                                                        | 2024 |               IEEE Transactions on Nanotechnology                |
| [A memristor-based analogue reservoir computing system for real-time and power-efficient signal processing](https://www.nature.com/articles/s41928-022-00838-3)                                | 2022 |                        Nature Electronics                        |
| [Rotating neurons for all-analog implementation of cyclic reservoir computing](https://www.nature.com/articles/s41467-022-29260-1)                                                             | 2022 |                      Nature Communications                       |
| [Diffusive and drift halide perovskite memristive barristors as nociceptive and synaptic emulators for neuromorphic computing](https://onlinelibrary.wiley.com/doi/abs/10.1002/adma.202007851) | 2021 |                        Advanced Materials                        |
| [Dynamic memristor-based reservoir computing for high-efficiency temporal signal processing](https://www.nature.com/articles/s41467-020-20692-1)                                               | 2021 |                      Nature Communications                       |
| [A training-efficient hybrid-structured deep neural network with reconfigurable memristive synapses](https://ieeexplore.ieee.org/abstract/document/8866734)                                    | 2020 | IEEE Transactions on Very Large Scale Integration (VLSI) Systems |
| [Temporal data classification and forecasting using a memristor-based reservoir computing system](https://www.nature.com/articles/s41928-019-0313-3)                                           | 2019 |                        Nature Electronics                        |
| [Reservoir computing using dynamic memristors for temporal information processing](https://www.nature.com/articles/s41467-017-02337-y)                                                         | 2017 |                      Nature Communications                       |


- Emerging Physical Implementations

| Paper                                                                                                                                                                                       | Year |                 Pub.                  | Physical Method |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----:|:-------------------------------------:|:---------------:|
| [Reservoir computing based on ZnWO4-x/WO3-x heterojunction optoelectronic memristor for time-series data and static image processing](https://ieeexplore.ieee.org/document/11095265)        | 2025 | IEEE Transactions on Electron Devices |     Hybrid      |
| [Quantum fourier transformation using quantum reservoir computing network](https://onlinelibrary.wiley.com/doi/abs/10.1002/qute.202400396)                                                  | 2025 |     Advanced Quantum Technologies     |     Quantum     |
| [Quantum reservoir computing for photonic entanglement witnessing](https://www.science.org/doi/10.1126/sciadv.ady7987)                                                                      | 2025 |           Science Advances            |     Hybrid      |
| [Ultrafast silicon photonic reservoir computing engine delivering over 200 TOPS](https://www.nature.com/articles/s41467-024-55172-3)                                                        | 2024 |         Nature Communications         |    Phinonic     |
| [Configured quantum reservoir computing for multi-task machine learning](https://www.sciencedirect.com/science/article/pii/S2095927323005807)                                               | 2023 |           Science Bulletin            |     Quantum     |
| [Exploring quantumness in quantum reservoir computing](https://link.aps.org/doi/10.1103/PhysRevA.108.052427)                                                                                | 2023 |           Physical Review A           |     Quantum     |
| [An optoelectronic synapse based on α-in2se3 with controllable temporal dynamics for multimode and multiscale reservoir computing](https://www.nature.com/articles/s41928-022-00847-2)      | 2022 |          Nature Electronics           |     Hybrid      |
| [Novel nondelay-based reservoir computing with a single micromechanical nonlinear resonator for high-efficiency information processing](https://www.nature.com/articles/s41378-021-00313-7) | 2021 |    Microsystems & Nanoengineering     |     Hybrid      |
| [Quantum neuromorphic computing with reservoir computing networks](https://onlinelibrary.wiley.com/doi/abs/10.1002/qute.202100053)                                                          | 2021 |     Advanced Quantum Technologies     |     Quantum     |
| [Experimental demonstration of reservoir computing on a silicon photonics chip](https://www.nature.com/articles/ncomms4541)                                                                 | 2014 |         Nature Communications         |    Phinonic     |
| [Parallel photonic information processing at gigabyte per second data rates using transient states](https://www.nature.com/articles/ncomms2368)                                             | 2013 |         Nature Communications         |    Phinonic     |
| [Photonic information processing beyond turing: an optoelectronic implementation of reservoir computing](https://opg.optica.org/oe/abstract.cfm?uri=oe-20-3-3241)                           | 2012 |            Optics Express             |    Phinonic     |



### Reservoir Computing Software Frameworks

|                     Software                     | Year |                                  Open Source                                  | ESN | LSM | Programming Language |
|:------------------------------------------------:|:----:|:-----------------------------------------------------------------------------:|:---:|:---:|:--------------------:|
|   **Dedicated Reservoir Computing Framework**    |      |                                                                               |     |     |                      |
|                    ESNToolbox                    | 2001 |         [Website](https://www.ai.rug.nl/minds/uploads/ESNToolbox.zip)         |  √  |  ×  |        Matlab        |
|                       CSIM                       | 2003 |             [Website](https://www.lsm.tugraz.at/csim/index.html)              |  ×  |  √  |     Matlab, C++      |
|                       Oger                       | 2012 |                  [GitHub](https://github.com/neuronalX/Oger)                  |  √  |  √  |        Python        |
|                     DeepESN                      | 2017 | [Website](https://ww2.mathworks.cn/matlabcentral/fileexchange/69402-deepesn/) |  √  |  ×  |        Matlab        |
|                    EchoTorch                     | 2018 |               [GitHub](https://github.com/nschaetti/EchoTorch)                |  √  |  ×  |        Python        |
|                   PyTorch-ESN                    | 2018 |             [GitHub](https://github.com/stefanonardo/pytorch-esn)             |  √  |  ×  |        Python        |
|                   ReservoirPy                    | 2020 |             [GitHub](https://github.com/reservoirpy/reservoirpy)              |  √  |  √  |        Python        |
|                     bio2art                      | 2021 |                 [GitHub](https://github.com/AlGoulas/bio2art)                 |  √  |  ×  |        Python        |
|                     RcTorch                      | 2022 |                [GitHub](https://github.com/blindedjoy/RcTorch)                |  √  |  ×  |        Python        |
|                      PyRCN                       | 2022 |                [GitHub](https://github.com/blindedjoy/RcTorch)                |  √  |  ×  |        Python        |
|              ReservoirComputing.jl               | 2022 |           [GitHub](https://github.com/SciML/ReservoirComputing.jl)            |  √  |  ×  |        Julia         |
|                     SNP, DNP                     | 2023 |           [Website](https://codeocean.com/capsule/7809611/tree/v1)            |  √  |  ×  |        Matlab        |
|                      PRCpy                       | 2024 |                  [GitHub](https://github.com/OSJL-py/PRCpy)                   |  √  |  ×  |        Python        |
|                     conn2res                     | 2024 |               [GitHub](https://github.com/netneurolab/conn2res)               |  √  |  √  |        Python        |
|                   reservoirnet                   | 2025 |  [GitHub](https://github.com/computorg/published-202505-ferte-reservoirnet)   |  √  |  ×  |          R           |
|                     OpenPRC                      | 2026 |             [GitHub](https://github.com/DARE-Lab-VT/OpenPRC-dev)              |  √  |  ×  |        Python        |
| **Neurocomputing-Oriented Simulation Framework** |      |                                                                               |     |     |                      |
|                      Brain2                      | 2014 |                [GitHub](https://github.com/brian-team/brian2)                 |  ×  |  √  |        Python        |
|                      Nengo                       | 2014 |                   [GitHub](https://github.com/nengo/nengo)                    |  ×  |  √  |        Python        |
|                     NeuCube                      | 2014 |                    [GitHub](https://github.com/KEDRI-AUT)                     |  ×  |  √  |    Matlab, Python    |
|                     BindsNET                     | 2018 |                [GitHub](https://github.com/BindsNET/bindsnet)                 |  ×  |  √  |        Python        |
|                     TENNLab                      | 2018 |            [GitHub](https://github.com/TENNLab-UTK/framework-open)            |  ×  |  √  |         C++          |
|                       NEST                       | 2019 |               [GitHub](https://github.com/nest/nest-simulator)                |  ×  |  √  |     Python, C++      |
|                     snnTorch                     | 2023 |               [GitHub](https://github.com/jeshraghian/snntorch)               |  ×  |  √  |        Python        |
|                     BrainCog                     | 2023 |               [GitHub](https://github.com/BrainCog-X/Brain-Cog)               |  ×  |  √  |        Python        |
|                     BrainPy                      | 2023 |                 [GitHub](https://github.com/Brainpy/Brainpy)                  |  √  |  ×  |        Python        |
|                   SpikingJelly                   | 2023 |            [GitHub](https://github.com/fangwei123456/spikingjelly)            |  ×  |  √  |        Python        |

---
<a href="https://clustrmaps.com/site/1c9kj" title="ClustrMaps">
  <img src="https://www.clustrmaps.com/map_v2.png?d=SpMxv-E5e4ngMl0aLMOr83hM3_ezLZlg4lKRuWXWtkU&cl=ffffff" />
</a>