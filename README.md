# Software Engineering for Automotive and Mobility Ecosystems - Seame course 2025 edition

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


# Course Contents

![Course roadmap](![Image](https://private-user-images.githubusercontent.com/38940615/460765466-cf3ad66f-f6fe-4fd5-bc17-06a2fc191d05.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTEzMjAwNjcsIm5iZiI6MTc1MTMxOTc2NywicGF0aCI6Ii8zODk0MDYxNS80NjA3NjU0NjYtY2YzYWQ2NmYtZjZmZS00ZmQ1LWJjMTctMDZhMmZjMTkxZDA1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA2MzAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNjMwVDIxNDI0N1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTJhMGE4MWU3ODI5NWQwNzM2MmU2NDAxYzFjNGUzMzZlYTZmMmEwNDAwNTNlMjIyNWVlMmJhOTg5MWQxOGU4N2UmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.zRjItWTiJ7TEZxwIEZEm2a_a8_sFeHR_idZSCpYwOIM))

# Hardware list

Throughout the course you will be using different hardware components to achieve the intended goals. The following is a non-extensive list of hardware components which will be critical to achieve the project goals:

- Raspberry Pi 5 - to work as central computing unit.
- Servo motors - for steering.
- DC motors - for propulsion.
- Display - to enable a UI / UX elements.
- Microcontroller (TBD which) - Running RTOS to enable safety critical functionality.
- Hailo AI Hat - to perform machine learning inference at high speed.
- Camera and other sensors - understanding environment to enable ADAS functions.
- etc.
