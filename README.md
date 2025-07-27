# 3D-Digital-Twins-Simple-Docs

## Description

This is a documentation is for instructing by my experience, historic of trail and error and work, to anyone interested in 3D Digital Twins on using open source software and proprietary tools, such as [Blender](https://www.blender.org), [Unity](https://unity.com/) and [Unreal Engine](https://www.unrealengine.com/en-US). Considering also the tools that uses all or some of this softwares. Also is listed my progress and what I have found and showing what works and what doesn't on the date of this documentation. So, I hope you can learn with my path, mistake and success while I was learning. Hope you find this documentation useful.

## Introduction

This is based on my learning on my 8 week work, so all this documentation is based on my "journey" to deep dive into the world of 3D Digital Twins, regardless of the tools used. Considering this format, it's going to be to my historic starting on week 1 to 8.

# Week 1

In the first week, I participated in an internship focused on the development and simulation of *Digital Twins*, which are virtual 3D replicas of real-world systems with a particular emphasis on clean energy infrastructure and energy efficiency. In the first week, I was introduced to the core topic through a kickoff meeting and was given learning materials to explore the concept. My task was to research the theme and deliver a presentation summarizing my understanding of Digital Twins, which I completed successfully despite the complexity of the subject.

# Week 2

In the second week, I was assigned to integrate the Visualization Toolkit (VTK) into Blender. Initially, I struggled to understand how such integration would function. Although I found plugins that could support this, they required installing several dependencies manually, which proved to be a tedious and time-consuming process. Additionally, the absence of daily meetings made it difficult to track progress and receive feedback in a timely manner.

# Week 3

The third week presented communication challenges. I was called to attend the workplace in person without prior notice that I would need to present the progress from previous weeks. Unprepared, I had to demonstrate my research history and GitHub activity on the spot. I had not succeeded in integrating VTK into Blender or building a functional Digital Twin. Due to these difficulties, I was reassigned to a new task: exploring Point Cloud visualization as an alternative method. Despite the setback, I redirected my focus to this new challenge.

# Week 4

During the fourth week, daily meetings were reestablished, providing much-needed structure and consistency. This allowed me to fully immerse myself in the Point Cloud Visualization task. I successfully rendered 3D point cloud data in Blender, including the use of real-world datasets to simulate actual structures. Although I had to use an older version of Blender, I was able to achieve stable and meaningful results. The progress marked a turning point, making previously overwhelming tasks manageable.

# Week 5

In the fifth week, I was tasked with simulating autonomous vehicles outside Blender, since the software was no longer suitable for this goal. I evaluated several tools for both Windows and Linux, ultimately choosing Unreal Engine 4.27 on Windows due to better compatibility and performance. I learned that adapting quickly to new development environments would be essential going forward.

# Week 6

The sixth week was fully dedicated to simulation testing. I successfully ran vehicle-driving simulations manually within Unreal Engine 4.27 on Windows, loading maps and controlling cars in a functional environment. However, I had not yet replicated this setup in Linux. Even so, this week yielded concrete and valuable technical outcomes.

# Week 7

In the seventh week, I attempted to improve simulation workflows on both operating systems but ultimately focused solely on Windows, as Linux proved incompatible with key tools like AirSim. I aimed to implement autonomous driving features, but the complexity of the task led me to scale back expectations. I concluded that continuing on Linux was not viable under the current constraints.

# Week 8

In the final week, unable to deliver a working autonomous vehicle model, I shifted focus toward deepening my knowledge of automation and AI within vehicle simulation contexts. I explored Python-based tools and environments, including the Anaconda platform, dedicating time to reading documentation and understanding the technologies. This self-guided study reinforced my foundation for applying these concepts in future projects, personally or professionally. Concluding my internship on a note of technical growth and exploration.

# Conclusion

Throughout these eight weeks, my internship provided a deep and multifaceted learning experience, combining technical challenges, independent research, and real-world problem solving. From my initial exposure to the concept of Digital Twins to the final weeks focused on AI-driven vehicle simulations, each stage of the internship pushed me to expand my understanding of complex technologies and adapt to evolving demands.

I faced significant challenges, ranging from software integration hurdles and lack of initial guidance, to the difficulty of working across different operating systems. However, these obstacles became catalysts for growth, requiring me to troubleshoot, seek solutions proactively, and rethink my approach when necessary. The shift from theoretical research to practical implementation taught me how to navigate ambiguity, manage project expectations, and apply self-discipline in the absence of constant oversight.

By the end of the internship, I had successfully explored tools like Blender, VTK, Point Cloud visualization, Unreal Engine, AirSim, and Python-based platforms such as Anaconda. While I didn’t fully implement an autonomous driving system, I built a strong technical foundation and gained valuable insight into the workflows, tools, and decision-making processes involved in complex simulation environments.

Ultimately, this internship strengthened my problem-solving abilities, broadened my technical skill set, and reaffirmed my motivation to pursue a career that bridges technology, simulation, and innovation. It was not only a step forward in technical capability but also a personal development journey in resilience and adaptability.

# Base softwares:

[![Blender](https://img.shields.io/badge/Blender-%23F5792A.svg?logo=blender&logoColor=white)](https://www.blender.org)
[![Unity](https://img.shields.io/badge/Unity-%23000000.svg?logo=unity&logoColor=white)](https://unity.com/)
[![UE](https://img.shields.io/badge/Unreal%20Engine-0E1128.svg?style=for-the-badge&logo=Unreal-Engine&logoColor=white)](https://www.unrealengine.com/en-US/)

# References

* [Point cloud visualizer Github](https://github.com/uhlik/bpy)
* [AirSim Github](https://github.com/microsoft/AirSim?tab=readme-ov-file)
* [AirSim Autonomous Driving Cookbook Github](https://github.com/Microsoft/AutonomousDrivingCookbook)
* [Tutorial 1 (Autonomous Driving Cookbook)](https://github.com/microsoft/AutonomousDrivingCookbook/tree/master/AirSimE2EDeepLearning)

## Useful Links

This links below are the citations on the documentation:
* [Step 0 (AirSim Github)](https://github.com/microsoft/AutonomousDrivingCookbook/blob/master/AirSimE2EDeepLearning/DataExplorationAndPreparation.ipynb)
* [Step 1 (AirSim Github)](https://github.com/microsoft/AutonomousDrivingCookbook/blob/master/AirSimE2EDeepLearning/TrainModel.ipynb)
* [Step 2 (AirSim Github)](https://github.com/microsoft/AutonomousDrivingCookbook/blob/master/AirSimE2EDeepLearning/TestModel.ipynb)

### Unsupported Tools:

* [LG SVL (Offline and online only)](https://github.com/lgsvl/simulator)
* [Point Cloud Github CSV (For too old Blender version and for unused file format)](https://github.com/LutraRomp/io_mesh_csv)

### Unused Tools:

* [VTK Tool (For Blender)](https://github.com/simboden/BVtkNodes)