# Goals for this Module

## Goal 1: Getting Familiarized with Advanced Driver-Assistance Systems (ADAS)

**Advanced Driver-Assistance Systems (ADAS)** are a suite of electronic technologies integrated into modern vehicles to assist drivers with driving and parking tasks. These systems rely on advanced sensors—such as cameras, radar, and lidar—to evaluate the environment around the vehicle. 

The **impact of ADAS on the automotive industry is profound and multifaceted**. The introduction of these technologies has led to significant safety improvements, resulting in a notable decrease in road accidents and fatalities. This shift also brings economic benefits like lower insurance costs. Regulatory bodies worldwide are increasingly mandating the inclusion of certain ADAS features in new vehicles, pushing the industry toward higher safety standards. At the same time, ADAS is accelerating the adoption of advanced technologies such as artificial intelligence, IoT, and high-performance sensors, laying the groundwork for future autonomous vehicles. This evolution also generates new business opportunities in software development, sensor manufacturing, data analytics, fleet management, and insurance.

In summary, ADAS represents a transformative step in vehicle design and road safety and serves as a critical foundation for the development of fully autonomous vehicles. As technology matures and regulations evolve, the significance and prevalence of ADAS will continue to grow across the automotive landscape.

So we would like to be familiar with the **Key ADAS features** include automatic emergency braking (EBA), lane departure warnings (LDW), adaptive cruise control (ACC), blind-spot detection, traffic sign recognition (TSR), and parking assistance (PA). 

## Goal 2: Getting Familiarized with Perception, Control, Localization and path-planning, Communication, Simulation

Understanding the fundamentals of Perception, Control, Localization and Path-Planning, Communication, and Simulation is key to grasping how intelligent driving technologies operate and evolve.

Perception refers to the vehicle’s ability to sense and interpret its surroundings using data from cameras, radar, lidar, and ultrasonic sensors. Advanced algorithms process this sensor data to detect obstacles, identify lane markings, recognize traffic signs, and track other vehicles or pedestrians. Accurate perception is foundational for all subsequent decision-making within an ADAS.

Control systems are responsible for executing driving actions in response to perception insights and planned paths. This involves real-time management of steering, acceleration, and braking to ensure the vehicle follows desired trajectories smoothly and safely, even as environmental conditions change. Some exampl

Localization and Path-Planning ensure the vehicle knows its precise location on the road and can determine optimal, safe routes. Localization fuses GPS, map data, and sensor information for centimeter-level accuracy. Path-planning algorithms then generate feasible routes or maneuvers, allowing the vehicle to navigate complex environments, avoid obstacles, and comply with traffic rules.

Communication plays an increasingly critical role, enabling vehicles to exchange information with each other (V2V), with infrastructure (V2I), and with the wider digital ecosystem (V2X). Reliable communication enhances situational awareness, helps anticipate hazards, and supports collaborative driving strategies, all contributing to more intelligent and coordinated traffic systems.

Simulation environments, such as CARLA or similar platforms, allow for rapid, risk-free testing and development of all these systems. Through simulation, developers can create and evaluate numerous scenarios—from everyday traffic flows to rare or hazardous situations—significantly accelerating the validation and refinement of ADAS algorithms.

In combination, these five pillars underpin the next generation of automotive technology. Mastery of them is essential for engineers, developers, and stakeholders working toward advanced, safe, and connected mobility solutions. As ADAS continues to mature, the integration and evolution of these domains will remain at the forefront of automotive innovation.

For this goal we expected to you be familiar with control models like Proportional–integral–derivative controller (PID) and Model Predictive Control (MCP).

## Goal 3: Getting Familiarized with comprehensive simulation environmnents using platforms like CARLA

Simulation environments like CARLA are game changers in the automotive industry, particularly for the development and testing of Advanced Driver-Assistance Systems (ADAS) and autonomous vehicles. CARLA is an open-source simulator designed specifically for autonomous driving research. It provides a highly realistic, customizable 3D world in which vehicles, sensors, pedestrians, and diverse weather and traffic conditions can be simulated.

In summary, CARLA and similar simulation environments enable safer, faster, and more comprehensive development of driving technologies—serving as essential tools in the push toward safer and more reliable autonomous vehicles.

Our goal here is to you to install CARLA and create the necessary configurations to allow you to start test and valide your algorithms.

## Goal 4: Getting Familiarized with Advanced Driver-Assistance Systems (ADAS) Algorithms , Artificial Inteligence (AI) , Machine Learning (ML) and Deep Learning

Advanced Driver-Assistance Systems (ADAS) have revolutionized modern vehicles by enhancing safety, convenience, and efficiency. At the heart of this transformation are sophisticated algorithms powered by Artificial Intelligence (AI), Machine Learning (ML), and Deep Learning. These technologies allow vehicles to interpret their surroundings, make complex decisions, and assist or even automate various driving functions.

**ADAS algorithms** process real-time data from multiple vehicle sensors, including cameras, radar, and lidar. These algorithms are responsible for functions such as lane keeping, automatic emergency braking, pedestrian detection, adaptive cruise control, and traffic sign recognition. Traditional rule-based approaches have given way to AI-powered solutions, allowing systems to learn from vast datasets and adapt to increasingly complex driving scenarios.

**Artificial Intelligence (AI)** provides the overarching framework, simulating human-like reasoning and decision-making. **Machine Learning (ML)**, a subset of AI, enables ADAS systems to improve their performance over time by learning from data—such as distinguishing between pedestrians, cyclists, and other vehicles. **Deep Learning**, a branch of ML, excels in recognizing patterns and features within large volumes of unstructured data, such as images and videos. This is crucial for tasks like real-time object detection, scene interpretation, and driver monitoring.

Integrating these advanced algorithms into ADAS is reshaping the automotive industry. Vehicles are becoming increasingly adept at preventing accidents and responding to dynamic road conditions, significantly reducing the rate of traffic incidents caused by human error. Automakers and technology firms are investing heavily in AI research and development to push the boundaries of safety and automation. Furthermore, regulatory agencies are beginning to draw up new frameworks to ensure that these AI-driven systems are tested and validated to stringent standards, ensuring reliability and public trust.

Your goal is study the available models for autonomous driving and obstacles avoidance/detection. 
The group needs to create an ADR explanning the reason for the selection of model/s into car.

## Goal 5: Getting Familiarized with GenAI applied to Advanced Driver-Assistance Systems

**Generative Artificial Intelligence (GenAI)** is rapidly emerging as a transformative technology within Advanced Driver-Assistance Systems (ADAS). GenAI refers to AI models capable of creating new data, predictions, or solutions by learning patterns from extensive datasets. When applied to the automotive context, GenAI brings unprecedented capabilities to ADAS, enabling more adaptive, robust, and intelligent systems.

GenAI enhances ADAS by powering a wide range of applications, from environment simulation to real-time decision-making. By leveraging GenAI, automotive engineers can generate highly realistic driving scenarios for testing and validating ADAS algorithms, ensuring better preparation for rare or hazardous events that are challenging to capture in conventional datasets. 

Moreover, GenAI-driven ADAS systems are able to recognize and respond to complex driving situations by synthesizing inputs from multiple sensors and predicting possible outcomes. For instance, GenAI can fill in gaps in sensor data, enhance low-quality images, and hypothesize about obstacles or traffic participants that are temporarily hidden. It can even help predict pedestrian intentions or potential hazards based on subtle signs in the environment.

The integration of GenAI into ADAS is accelerating the automotive industry's trajectory toward fully autonomous vehicles. Automotive manufacturers, technology companies, and mobility startups are increasingly leveraging GenAI to enhance the scope and safety of their intelligent driving systems. This technology also supports regulatory compliance by improving the testing, validation, and explainability of AI algorithms in safety-critical contexts.

As the market evolves, the adoption of GenAI in ADAS is expected to grow swiftly, driving further advancements in road safety, vehicle reliability, and user comfort. GenAI is not only an enabler for safer, smarter driving assistance but also a cornerstone for the future of autonomous mobility.

## Goal 6: Getting Familiarized with Advanced Driver-Assistance Systems Software orchestration and updates

Modern vehicles increasingly depend on complex software to power Advanced Driver-Assistance Systems (ADAS). As these systems become more sophisticated, the efficient orchestration and continual updating of their software have become critical to maintaining performance, safety, and user experience. **Software orchestration** refers to the management, coordination, and integration of diverse software modules that control various ADAS functionalities such as lane keeping, adaptive cruise control, emergency braking, and blind-spot detection.

In a typical ADAS environment, multiple software components must interact seamlessly, processing data from various sensors (cameras, radar, lidar, ultrasonic sensors) and executing safety-critical decisions in real time. Software orchestration ensures these components cooperate reliably, are properly prioritized, and efficiently utilize vehicle computing resources. This orchestration involves robust middleware, real-time operating systems, and standardized communication protocols to synchronize functionalities and maintain system integrity under all driving conditions.

The ability to update ADAS software over a vehicle’s lifetime is equally essential. **Over-the-air (OTA) updates** have become a game changer, allowing manufacturers to remotely deliver security patches, introduce new features, and continuously improve system algorithms without requiring a service visit. Regular updates not only address vulnerabilities and enhance safety but also keep vehicles compliant with evolving regulations and user expectations. OTA updates reduce downtime and costs for both manufacturers and vehicle owners—enabling a dynamic, service-oriented approach to vehicle software much like that seen in smartphones and other connected devices.

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

