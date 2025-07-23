# INTRO

**Advanced Driver-Assistance Systems (ADAS)** are a suite of electronic technologies integrated into modern vehicles to assist drivers with driving and parking tasks. These systems rely on advanced sensors—such as cameras, radar, and lidar—to evaluate the environment around the vehicle. 

The **impact of ADAS on the automotive industry is profound and multifaceted**. The introduction of these technologies has led to significant safety improvements, resulting in a notable decrease in road accidents and fatalities. This shift also brings economic benefits like lower insurance costs. Regulatory bodies worldwide are increasingly mandating the inclusion of certain ADAS features in new vehicles, pushing the industry toward higher safety standards. At the same time, ADAS is accelerating the adoption of advanced technologies such as artificial intelligence, IoT, and high-performance sensors, laying the groundwork for future autonomous vehicles. This evolution also generates new business opportunities in software development, sensor manufacturing, data analytics, fleet management, and insurance.

In summary, ADAS represents a transformative step in vehicle design and road safety and serves as a critical foundation for the development of fully autonomous vehicles. As technology matures and regulations evolve, the significance and prevalence of ADAS will continue to grow across the automotive landscape.

# Goals for this Module
## Goal 1: Getting Familiarized with Advanced Driver-Assistance Systems (ADAS)

We seek to become familiar with **Key ADAS features**, including automatic emergency braking (AEB), lane departure warning (LDW), adaptive cruise control (ACC), blind-spot detection, traffic sign recognition (TSR), and parking assistance (PA). 

## Goal 2: Getting Familiarized with Perception, Control, Localization and path-planning, Communication, Simulation

A comprehensive understanding of Perception, Control, Localization and Path-Planning, Communication, and Simulation is essential for developing intelligent driving systems.
- **Perception** involves using sensors (cameras, radar, lidar) and advanced algorithms to interpret the vehicle’s environment and detect obstacles, lanes, signs, and other participants.
- **Control** systems translate perception outputs into physical actions, managing steering, acceleration, and braking to ensure safe and responsive driving.
- **Localization and Path-Planning** provide precise positioning on the road using GPS, map data, and sensor fusion, and generate optimal trajectories for safe navigation.
- **Communication** technologies (V2V, V2I, V2X) allow vehicles to share data with each other and infrastructure, enhancing safety and enabling collaborative, coordinated driving strategies.
- **Simulation** platforms like CARLA support the virtual development and testing of these components in diverse situations, improving both safety and efficiency before real-world deployment. 

Together, these domains form the foundation of advanced ADAS and autonomous vehicle technologies. As the field evolves, it is essential for the group to develop expertise in each area, with a particular focus on control models. As part of this project, your goal is to study, select, and implement a control model—such as PID or Model Predictive Control (MPC)—in your vehicle.

## Goal 3: Getting Familiarized with comprehensive simulation environmnents using platforms like CARLA

Simulation environments like CARLA are game changers in the automotive industry, particularly for the development and testing of Advanced Driver-Assistance Systems (ADAS) and autonomous vehicles. CARLA is an open-source simulator designed specifically for autonomous driving research. It provides a highly realistic, customizable 3D world in which vehicles, sensors, pedestrians, and diverse weather and traffic conditions can be simulated.

In summary, CARLA and similar simulation environments enable safer, faster, and more comprehensive development of driving technologies—serving as essential tools in the push toward safer and more reliable autonomous vehicles.

The objective is for you to install CARLA and set up the necessary configurations to enable testing and validation of your algorithms.

## Goal 4: Getting Familiarized with Advanced Driver-Assistance Systems (ADAS) Algorithms , Artificial Inteligence (AI) , Machine Learning (ML) and Deep Learning

Advanced Driver-Assistance Systems (ADAS) have revolutionized modern vehicles by enhancing safety, convenience, and efficiency. At the heart of this transformation are sophisticated algorithms powered by Artificial Intelligence (AI), Machine Learning (ML), and Deep Learning. These technologies allow vehicles to interpret their surroundings, make complex decisions, and assist or even automate various driving functions.

Our objective is to review and evaluate the available models for autonomous driving and obstacle detection/avoidance.
The group is required to prepare an Architecture Decision Record (ADR) that explains the rationale behind the selection of the model(s) to be implemented in the vehicle.

## Goal 5: Getting Familiarized with GenAI applied to Advanced Driver-Assistance Systems

As part of this project, students are expected to leverage **Generative Artificial Intelligence (GenAI)** tools—such as Generative Adversarial Networks (GANs), Variational Autoencoders (VAEs), diffusion models, and transformer-based architectures—to support the development of their autonomous driving algorithms. This includes using GenAI for tasks like data augmentation, scenario generation, sensor data synthesis, and policy modeling. By incorporating these advanced AI techniques into their workflow, students will enhance the training, testing, and validation of their ADAS solutions, ensuring greater accuracy and robustness in real-world conditions. Mastery of these generative models will be a key component of the project and is essential for preparing students to contribute to cutting-edge research and development in intelligent transportation systems.

## Goal 6: Getting Familiarized with Advanced Driver-Assistance Systems Software orchestration and updates

The ability to update ADAS software throughout a vehicle’s lifetime is increasingly vital. **Over-the-air (OTA) updates** have become a game changer, enabling manufacturers to remotely deliver security patches, introduce new features, and continuously improve system algorithms without necessitating a service visit. Regular OTA updates not only address vulnerabilities and enhance safety, but also ensure that vehicles remain compliant with evolving regulations and user expectations. By minimizing downtime and costs for both manufacturers and vehicle owners, OTA updates support a dynamic, service-oriented approach to vehicle software—similar to practices in smartphones and other connected devices.

As part of this project, you are expected to implement an OTA update mechanism for the ADAS system, thereby ensuring that the vehicle remains secure, up-to-date, and adaptable to future requirements.

---

# What is Expected by the End of this Module


By completing this module, you will:

* Develop and deploy a control model to handle with the acelaration and steering of the car.
* Develop and deploy at raspberry pi 5 a Lane Keep Assistant (LKA) caple of keep the car between the road through a full lap, Basic Cruise Control (CC).
    - Bonus: Adaptative Cruise Control (ACC)
* Develop and deploy at raspberry pi 5 a Object Detection and Avoidance caple to stop the car in case of collision possibillity, Emergency Brake Assist (EBA).
    - Bonus: Truck Platooning;
* Defined proper module requirements using the TSF framework.
* ADR for the Models Selection Decision
* Update a cluster UI using the Qt Framework to integrate the new ADAS features.
* Ensure a testing infrastructure and unit test coverage report generation.
* Gain practical experience with automotive industry-standard tools and workflows, preparing you for real-world automotive software engineering challenges.
* ADR for models selection.

