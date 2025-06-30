# Introduction

Over recent decades, we've witnessed a significant evolution in automotive systems driven largely by electronic innovation. Initially, electronics played a role in controlling only a handful of critical vehicle functions. Today, however, virtually every aspect of a vehicle—from basic engine operations to advanced driver-assistance systems—depends on sophisticated electronic control systems.

The expansion in the number of Electronic Control Units (ECUs) within vehicles highlights this progression clearly. What started with just a few ECUs now routinely involves dozens, and in some advanced models, more than a hundred individual control units. These ECUs manage everything from simple tasks like window controls to highly complex functions such as collision avoidance systems, adaptive cruise control, and autonomous driving capabilities.

To take matters into perspective, the average cost of electronic systems within a vehicle has grown from a few percent in the middle of the 20th century, to 35% in 2020, and is estimated to grow to 50% by the end of this decade.

![Share of cost](https://www.embitel.com/wp-content/uploads/Bar-graph.png)

Parallel to the increase in quantity, automotive systems have also significantly grown in computational power and complexity. This boost in computing capability has enabled vehicles to perform tasks such as real-time data analysis for active safety systems, navigation guidance, and autonomous driving algorithms.

As a result, the software running inside modern vehicles has reached staggering levels of complexity, often exceeding 100 million lines of code per vehicle. To put this into perspective, that's more code than is found in many advanced commercial aircraft or modern operating systems.

However, complexity brings risks, especially when automotive software controls safety-critical functions. Any software malfunction could pose serious dangers to passengers and others on the road. Thus, the automotive industry maintains exceptionally high standards for software reliability, safety, and quality assurance.

Original Equipment Manufacturers (OEMs) must not only deliver reliable software initially but also support, maintain, and provide warranties for these complex systems throughout the vehicle's life—often spanning more than a decade. To achieve this reliability, automotive software development processes adhere to strict and rigorous guidelines, standards, and best practices, such as **ISO 26262** for functional safety and **Automotive SPICE** (Software Process Improvement and Capability Determination) for software quality.

![Software Development Process](https://www.jamasoftware.com/media/2021/07/Screen-Shot-2021-07-21-at-2.27.03-PM.png)

Throughout this course, you'll learn and apply key automotive software engineering principles and processes. We'll delve into how these standards and guidelines help ensure cutting-edge functionalities are delivered reliably and safely. By understanding and practicing these automotive-specific methods, you'll gain insights and skills to produce software that meets the exacting demands of one of the most stringent industries worldwide.

---

# Goals for this Module

## Goal 1: Getting Familiarized with PiRacer Robot and Hardware

Your journey begins by assembling your very own **PiRacer** robot. This small-scale autonomous vehicle is powered by **Raspberry Pi 5**, a versatile mini-computer, and equipped with sensors, motors, and a display. You'll explore fundamental hardware components including:

- Raspberry Pi 5 setup 
- Servo motors for steering  
- DC motors for propulsion  
- Display interface  

Additionally, you'll develop a simple graphical user interface (GUI) application using the **Qt** framework. This will run directly on the PiRacer display, giving you hands-on experience with embedded UI design.

## Goal 2: Implementing Scrum and Agile Methodologies

Agile methodologies like **Scrum** provide flexible, iterative approaches to software development. You'll:

- Organize into small collaborative teams  
- Set up sprint cycles, stand-up meetings, and retrospectives
- Creating and maitaining a Scrum board that reflects sprint goals and progress accurately.
- Learn how Agile fosters better communication, continuous feedback, and incremental improvements  

This practical experience will help you appreciate the power of Agile in real-world automotive software projects.

## Goal 3: Learning Git and GitHub

Version control systems like **Git**, and collaboration platforms like **GitHub**, are vital tools in modern software engineering. During this module, you will:

- Understand basic Git concepts such as commits, branches, merges, and resolving conflicts  
- Collaborate effectively using GitHub repositories, issue tracking, pull requests, and code reviews  
- Establish best practices to manage code efficiently and safely within a team environment  
- Leverage GitHub Actions to enable continuous development and integration.

Mastering Git and GitHub will enable your team to collaborate seamlessly and maintain high-quality code.

## Goal 4: Getting Familiarized with Trustable Software Framework (TSF)

The **Trustable Software Framework (TSF)** is critical in automotive software development due to stringent safety and reliability requirements. TSF helps you:

- Clearly define and refine software requirements  
- Maintain traceability between requirements, architecture, implementation, and testing  
- Ensure robust software design, thorough testing, and proper documentation  

Hands-on exercises using TSF tools will illustrate how trustable software development processes prevent errors and ensure compliance with automotive industry standards.

## Goal 5: GenAI Pair Programming

Generative AI tools, such as advanced code assistants, can significantly boost developer productivity. During this module, you'll explore:

- Techniques for effective pair programming with generative AI  
- Best practices for reviewing AI-generated code  
- Integration strategies to seamlessly incorporate AI assistance into your workflow  

Embracing AI-driven tools early in your learning journey will enhance your coding skills, help solve complex problems faster, and prepare you for future industry practices.

---

# What is Expected by the End of this Module

- **Assembled** the PiRacer robot 
- **Set up** a GitHub repository that hosts a simple program capable of launching a basic Qt application, displaying static graphical elements on the PiRacer’s built-in screen  
- **Implemented** the Trustable Software Framework (TSF) within GitHub:
  - Defined initial software requirements  
  - Created traceability links between requirements, architecture, and test cases  
- **Maintained** an organized sprint plan and backlog  
- **Actively participated** in Scrum ceremonies to manage the team’s workflow effectively
- **Established** remote control functionality allowing the control of the PiRacer's motors 
