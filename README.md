# Awesome-Reservoir-Computing-Navigation
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repository collects papers, code, and software tools related to reservoir computing in robotics navigation.

If you find this repository helpful, please consider Stars ⭐ or Sharing 👋.

## Reservoir Computing Hardware Implementations

- FPGA-based Implementations

|                                                                                          Paper                                                                                           | Year |                                     Pub.                                      |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----:|:-----------------------------------------------------------------------------:|
| [ SpikeSpec: an on-chip learning neuromorphic accelerator for spectrum sensing with triplet-boosting and hardware friendly loss function](https://ieeexplore.ieee.org/document/10891704) | 2025 | IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems |
|    [Ghost reservoir: a memory-efficient low-power and real-time neuromorphic processor of liquid state machine with on-chip learning](https://ieeexplore.ieee.org/document/10511289)     | 2024 |         IEEE Transactions on Circuits and Systems II: Express Briefs          |
|                     [Adaptive input-to-neuron interlink development in training of spike-based liquid state machines](https://ieeexplore.ieee.org/document/9401085)                      | 2021 |       2021 IEEE International Symposium on Circuits and Systems (ISCAS)       |
|             [Energy efficient parallel neuromorphic architectures with approximate arithmetic on FPGA](https://www.sciencedirect.com/science/article/pii/S0925231216311213)              | 2017 |                                Neurocomputing                                 |
|       [Liquid state machine based pattern recognition on FPGA with firing-activity dependent power gating and approximate computing](https://ieeexplore.ieee.org/document/7527245)       | 2016 |         IEEE International Symposium on Circuits and Systems (ISCAS)          |
|                   [SSO-LSM: A Sparse and self-organizing architecture for liquid state machine based neural processors](https://ieeexplore.ieee.org/document/7568626)                    | 2016 |    IEEE/ACM International Symposium on Nanoscale Architectures (NANOARCH)     |
|              [General-purpose LSM learning processor architecture and theoretically guided design space exploration](https://ieeexplore.ieee.org/abstract/document/7348397)              | 2015 |           IEEE Biomedical Circuits and Systems Conference (BioCAS)            |
|                  [Compact hardware liquid state machines on FPGA for real-time speech recognition](https://www.sciencedirect.com/science/article/pii/S0893608007002353)                  | 2008 |                                Neural Networks                                |


- ASIC-based Implementations

|                                                                                  Paper                                                                                  | Year |                               Pub.                                |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----:|:-----------------------------------------------------------------:|
|               [LSM-based hotspot prediction and hotspot-aware routing in NoC-based neuromorphic processor](https://ieeexplore.ieee.org/document/10486852)               | 2024 |     IEEE Transactions on Very Large Scale Integration Systems     |
|                          [Neuromorphic on-chip reservoir computing with spiking neural network architectures](http://arxiv.org/abs/2407.20547)                          | 2024 |                               arXiv                               |
|                    [DNN-SNN co-learning for sustainable symbol detection in 5G systems on loihi chip](https://ieeexplore.ieee.org/document/10285018)                    | 2024 |            IEEE Transactions on Sustainable Computing             |
|        [Hardware-aware liquid state machine generation for 2D/3D network-on-chip platforms](https://www.sciencedirect.com/science/article/pii/S1383762122000297)        | 2022 |                  Journal of Systems Architecture                  |
|            [Liquid state machine on loihi: memory metric for performance prediction](https://link.springer.com/content/pdf/10.1007/978-3-031-15934-3_57.pdf)            | 2022 |          Artificial Neural Networks and Machine Learning          |
|                 [A long short-term memory for AI applications in spike-based neuromorphic hardware](https://www.nature.com/articles/s42256-022-00480-w)                 | 2022 |                    Nature Machine Intelligence                    |
| [Liquid state machine on SpiNNaker for spatio-temporal classification tasks](https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2022.819063/full) | 2022 |                     Frontiers in Neuroscience                     |
|                    [A multi-objective LSM/NoC architecture co-design framework](https://www.sciencedirect.com/science/article/pii/S1383762121001119)                    | 2021 |                  Journal of Systems Architecture                  |
|                               [A hardware aware liquid state machine generation framework](https://ieeexplore.ieee.org/document/9401057)                                | 2021 | 2021 IEEE International Symposium on Circuits and Systems (ISCAS) |


- Analog Circuit-based Implementations

|                                                                                   Paper                                                                                   | Year |                                 Pub.                                 |
|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----:|:--------------------------------------------------------------------:|
|               [LSMR: synergy randomness in liquid state machine and RRAM-based analog-digital accelerator](https://dl.acm.org/doi/10.1145/3676536.3676691)                | 2025 |  IEEE/ACM International Conference on Computer-Aided Design (ICCAD)  |
|        [A neuransistor with excitatory and inhibitory neuronal behaviors for liquid state machine](https://onlinelibrary.wiley.com/doi/abs/10.1002/adma.202419122)        | 2025 |                          Advanced Materials                          |
| [Multilayer reservoir computing based on ferroelectric α-In2Se3 for hierarchical information processing](https://onlinelibrary.wiley.com/doi/abs/10.1002/adma.202108826)  | 2024 |                          Advanced Materials                          |
|                          [Leaky FinFET for reservoir computing with temporal signal processing](https://pubs.acs.org/doi/10.1021/acsami.3c02630)                          | 2023 |                  ACS Applied Materials & Interfaces                  |
| [Reservoir computing with biocompatible organic electrochemical networks for brain-inspired biosignal classification](https://www.science.org/doi/10.1126/sciadv.abh0693) | 2021 |                           Science Advances                           |
|                   [Toward real-time, at-home patient health monitoring using reservoir computing CMOS IC](https://ieeexplore.ieee.org/document/9617636)                   | 2021 | IEEE Journal on Emerging and Selected Topics in Circuits and Systems |
|                       [Spatial-temporal hybrid neural network with computing-in-memory architecture](https://ieeexplore.ieee.org/document/9406054)                        | 2021 |     IEEE Transactions on Circuits and Systems I: Regular Papers      |
|                 [Analog hardware implementation of spike-based delayed feedback reservoir computing system](https://ieeexplore.ieee.org/document/7966288)                 | 2017 |      International Joint Conference on Neural Networks (IJCNN)       |


- Memristor-based Implementations

|                                                                                             Paper                                                                                              | Year |                               Pub.                               |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----:|:----------------------------------------------------------------:|
|               [A memristor-based event-driven reservoir computing system for cardiac arrhythmia detection](https://advanced.onlinelibrary.wiley.com/doi/10.1002/aisy.202500350)                | 2025 |                   Advanced Intelligent Systems                   |
|                [Spatiotemporal reservoir computing with a reconfigurable multifunctional memristor array](https://advanced.onlinelibrary.wiley.com/doi/10.1002/adma.202510635)                 | 2025 |                        Advanced Materials                        |
|                         [Brain-inspired reservoir computing using memristors with tunable dynamics and short-term plasticity](https://doi.org/10.1021/acsami.3c16003)                          | 2024 |                ACS Applied Materials & Interfaces                |
|                                    [Memristor based liquid state machine with method for in-situ training](https://ieeexplore.ieee.org/document/10478203/)                                     | 2024 |               IEEE Transactions on Nanotechnology                |
|                [A memristor-based analogue reservoir computing system for real-time and power-efficient signal processing](https://www.nature.com/articles/s41928-022-00838-3)                 | 2022 |                        Nature Electronics                        |
|                               [Rotating neurons for all-analog implementation of cyclic reservoir computing](https://www.nature.com/articles/s41467-022-29260-1)                               | 2022 |                      Nature Communications                       |
| [Diffusive and drift halide perovskite memristive barristors as nociceptive and synaptic emulators for neuromorphic computing](https://onlinelibrary.wiley.com/doi/abs/10.1002/adma.202007851) | 2021 |                        Advanced Materials                        |
|                        [Dynamic memristor-based reservoir computing for high-efficiency temporal signal processing](https://www.nature.com/articles/s41467-020-20692-1)                        | 2021 |                      Nature Communications                       |
|                  [A training-efficient hybrid-structured deep neural network with reconfigurable memristive synapses](https://ieeexplore.ieee.org/abstract/document/8866734)                   | 2020 | IEEE Transactions on Very Large Scale Integration (VLSI) Systems |
|                      [Temporal data classification and forecasting using a memristor-based reservoir computing system](https://www.nature.com/articles/s41928-019-0313-3)                      | 2019 |                        Nature Electronics                        |
|                             [Reservoir computing using dynamic memristors for temporal information processing](https://www.nature.com/articles/s41467-017-02337-y)                             | 2017 |                      Nature Communications                       |


- Emerging Physical Implementations

|                                                                                            Paper                                                                                            | Year |                 Pub.                  | Physical Method |
|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----:|:-------------------------------------:|:---------------:|
|    [Reservoir computing based on ZnWO4-x/WO3-x heterojunction optoelectronic memristor for time-series data and static image processing](https://ieeexplore.ieee.org/document/11095265)     | 2025 | IEEE Transactions on Electron Devices |     Hybrid      |
|                         [Quantum fourier transformation using quantum reservoir computing network](https://onlinelibrary.wiley.com/doi/abs/10.1002/qute.202400396)                          | 2025 |     Advanced Quantum Technologies     |     Quantum     |
|                                   [Quantum reservoir computing for photonic entanglement witnessing](https://www.science.org/doi/10.1126/sciadv.ady7987)                                    | 2025 |           Science Advances            |     Hybrid      |
|                            [Ultrafast silicon photonic reservoir computing engine delivering over 200 TOPS](https://www.nature.com/articles/s41467-024-55172-3)                             | 2024 |         Nature Communications         |    Phinonic     |
|                        [Configured quantum reservoir computing for multi-task machine learning](https://www.sciencedirect.com/science/article/pii/S2095927323005807)                        | 2023 |           Science Bulletin            |     Quantum     |
|                                        [Exploring quantumness in quantum reservoir computing](https://link.aps.org/doi/10.1103/PhysRevA.108.052427)                                         | 2023 |           Physical Review A           |     Quantum     |
|   [An optoelectronic synapse based on α-in2se3 with controllable temporal dynamics for multimode and multiscale reservoir computing](https://www.nature.com/articles/s41928-022-00847-2)    | 2022 |          Nature Electronics           |     Hybrid      |
| [Novel nondelay-based reservoir computing with a single micromechanical nonlinear resonator for high-efficiency information processing](https://www.nature.com/articles/s41378-021-00313-7) | 2021 |    Microsystems & Nanoengineering     |     Hybrid      |
|                             [Quantum neuromorphic computing with reservoir computing networks](https://onlinelibrary.wiley.com/doi/abs/10.1002/qute.202100053)                              | 2021 |     Advanced Quantum Technologies     |     Quantum     |
|                                 [Experimental demonstration of reservoir computing on a silicon photonics chip](https://www.nature.com/articles/ncomms4541)                                 | 2014 |         Nature Communications         |    Phinonic     |
|                       [Parallel photonic information processing at gigabyte per second data rates using transient states](https://www.nature.com/articles/ncomms2368)                       | 2013 |         Nature Communications         |    Phinonic     |
|              [Photonic information processing beyond turing: an optoelectronic implementation of reservoir computing](https://opg.optica.org/oe/abstract.cfm?uri=oe-20-3-3241)              | 2012 |            Optics Express             |    Phinonic     |



## Reservoir Computing Software Frameworks

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
|                     conn2res                     | 2024 |               [GitHub](https://github.com/netneurolab/conn2res)               |  √  |  √  |        Python        |
|                   reservoirnet                   | 2025 |  [GitHub](https://github.com/computorg/published-202505-ferte-reservoirnet)   |  √  |  ×  |          R           |
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