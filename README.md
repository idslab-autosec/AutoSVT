<p align="center">
<a href="https://github.com/idslab-autosec/AutoSVT"><img alt="AutoSVT-logo.png" src="https://github.com/idslab-autosec/AutoSVT/blob/main/img/logo-white.jpeg"></a>
</p>
<h2 align="center">AutoSVT:3D Virtual Simulation Framework for SOTIF Validation and Training in Autonomous Driving</h2>
<p align="center">
<a href="https://github.com/idslab-autosec/AutoSVT"><img alt="Static Badge" src="https://img.shields.io/badge/license-Apache2.0-green"></a>
<a href="https://github.com/idslab-autosec/AutoSVT"><img alt="Static Badge" src="https://img.shields.io/badge/release-v0.1.1-blue"></a>
</p>

## **3D Virtual Simulation Framework for SOTIF Validation and Training in Autonomous Driving**

AutoSVT is an open-source framework dedicated to enhancing the Safety of The Intended Functionality (SOTIF) of autonomous driving systems. It provides first-principles based 3D virtual simulation testing tools to discover adverse weather related corner cases.

For more detailed information and examples, please visit [AutoSVT's project website](https://idslab-autosec.github.io/).

## **Table of Contents**
- [Features](#features)
- [Related Components](#related-components)
- [AutoSVT Project Roadmap](#autosvt-project-roadmap)
- [How to Contribute](#how-to-contribute)
- [License](#license)
## **Features**

### **First-principles Based Simulation** 
- Sensor modeling and interaction with the environment, integrated into the CARLA simulator.

### **Discovering Adverse Weather Related Corner Cases** 
- A meta-heuristic algorithm guides seed scenarios and mutations, reducing the search dimensions of scenarios.

### **Synchronization For Multi-agent Collaborative Simulation** 
- An eBPF-based synchronization mechanism bridges ADSes and the simulator, mitigating issues of false positives and negatives in asynchronous simulations.







## **Related Components**

- Simulator: [AutoSVT-Carla](https://github.com/idslab-autosec/AutoSVT-carla)🔩
- Bridge: [AutoSVT-Bridge](https://github.com/idslab-autosec/AutoSVT-Carla-Apollo-Bridge)🔍
- Testing-Algorithm: [AutoSVT-Algorithms](https://github.com/idslab-autosec/AutoSVT-Algorithms)

## **AutoSVT Project Roadmap**

Our goal is to position AutoSVT as the leading and most practical virtual simulation testing platform for autonomous driving. To achieve this vision, we have charted the following key milestones:

### 1. **Enhanced Map Support**:
   - **Test Scenario Maps**: Add detailed maps for more driving scenarios, such as urban areas and highways.
   - **High-Precision Traffic Infrastructure Annotations**: Incorporate precise annotations for key traffic structures like traffic signs and lights within the high-definition maps.

### 2. **Environmental Effects Enhancement**:
   - **Gradient Fog Density**: Simulate fog of varying densities, from light mist to heavy fog, aiding in evaluating sensor performance and driving strategy adaptability.
   - **Snow Effect Simulation**: Examine the impact of snow on various sensors (e.g., radars, cameras) and its influence on vehicle dynamics.

### 3. **Multi-Vehicle Testing Support**:
   - **Addition of Autonomous Driving Agents**: Introduce a variety of preset autonomous driving agents to support multi-vehicle interactions within the same scenario.

### 4. **Enhanced Testing Automation & Reproducibility**:
   - **Automated Openscenario Model Generation**: Enable users to create and share test scenarios more easily.
   - **Testing Algorithms based on Openscenario**: Offer a standardized validation method for simulation testing, grounded in Openscenario.



## **How to Contribute**

We welcome your participation! [Raise an Issue](https://github.com/idslab-autosec/AutoSVT/issues/new) or submit a Pull Request.

## **License**

This project is under the Apache-2.0 license, for agreement please refer to [LICENSE](https://github.com/idslab-autosec/AutoSVT/blob/main/LICENSE).
