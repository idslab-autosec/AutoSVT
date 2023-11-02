<p align="center">
<a href="https://github.com/idslab-autosec/AutoSVT"><img alt="AutoSVT-logo.png" src="https://github.com/idslab-autosec/AutoSVT/blob/main/img/logo-white.jpeg"></a>
</p>
<h2 align="center">AutoSVT:3D Virtual Simulation Framework for SOTIF Validation and Training in Autonomous Driving</h2>
<p align="center">
<a href="https://github.com/idslab-autosec/AutoSVT"><img alt="Static Badge" src="https://img.shields.io/badge/release-v0.1.1-blue">
</a>
</p>

## 3D Virtual Simulation Framework for SOTIF Validation and Training in Autonomous Driving

AutoSVT is an open-source framework dedicated to enhancing the Safety of The Intended Functionality (SOTIF) of autonomous driving systems. It provides first-principles based 3D virtual simulation testing tools to discover adverse weather related corner cases.

For more detailed information and examples, please visit [AutoSVT's project website](https://idslab-autosec.github.io/).

## Table of Contents
- [Features](#features)
- [Related Components](#related-components)
- [Frequently Asked Questions](#QA)
- [How to Contribute](#how-to-contribute)
- [License](#license)
## Features

### First-principles Based Simulation 
- Sensor modeling and interaction with the environment, integrated into the CARLA simulator.

### Discovering Adverse Weather Related Corner Cases 
- A meta-heuristic algorithm guides seed scenarios and mutations, reducing the search dimensions of scenarios.

### Synchronization For Multi-agent Collaborative Simulation 
- An eBPF-based synchronization mechanism bridges ADSes and the simulator, mitigating issues of false positives and negatives in asynchronous simulations.







## Related Components

- Simulator: [AutoSVT-Carla](https://github.com/idslab-autosec/AutoSVT-carla)🔩
- Bridge: [AutoSVT-Bridge](https://github.com/idslab-autosec/AutoSVT-Carla-Apollo-Bridge)🔍
- Testing-Algorithm: [AutoSVT-Algorithms](https://github.com/idslab-autosec/AutoSVT-Algorithms)

## Maintainers



## How to Contribute

We welcome your participation! [Raise an Issue](https://github.com/idslab-autosec/AutoSVT/issues/new) or submit a Pull Request.

## License

This project is under the Apache-2.0 license, for agreement please refer to [LICENSE](https://github.com/idslab-autosec/AutoSVT/blob/main/LICENSE).