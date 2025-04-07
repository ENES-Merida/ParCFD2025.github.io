---
layout: page
title: Advancing CI/CD Methodologies in Computational Fluid Dynamics
subtitle: Mini-Symposia I
hero_image:  /img/plazaGrandeSideB.png
hero_height: is-halfheight
hero_darken: true
show_sidebar: false
---

{% include notification.html message="Site under construction, information will be updated very soon." %}

Damien Dosimont, Guillaume Houzeaux and Dennis Hoppe

**Abstract:**

*Adopting Continuous Integration/Continuous Deployment (CI/CD) methodologies has become essential in modern software development and deployment. This approach has proven beneficial in enhancing the stability, reproducibility, portability, and performance of Computational Fluid Dynamics (CFD) applications. Building on the success of earlier efforts, this symposium seeks to explore cutting-edge advancements and strategies across all stages of the CI/CD pipeline, emphasizing their critical impact on the scientific and engineering aspects of CFD applications.*

*We invite contributions on the following evolving topics in the CI/CD pipeline for CFD:*

**Efficient Build Systems for CFD**

- **Innovative Build Processes:** Delving into state-of-the-art build systems tailored to CFD-specific needs.

- **Portability Strategies:** Ensuring compatibility across different compilers, architectures, CPU/GPU configurations, and programming standards.

- **Containerization and Code Versioning:** Techniques for managing multiple code versions and achieving portability through containerization.

**Advanced Testing for CFD Simulations**

- **Automated Testing Frameworks:** Integration of cutting-edge automated testing methodologies into CI/CD pipelines to enhance simulation accuracy.

- **Large-Scale Parallel Testing Challenges:** Addressing issues with testing large, parallel CFD simulations and ensuring their reliability.

- **Interdisciplinary Testing Collaboration:** Best practices for collaborative testing within multidisciplinary CFD research teams.

**Seamless Deployment of CFD Applications**

- **Deployment Strategies for Scalability:** Examining deployment approaches that ensure seamless and reliable distribution of CFD applications across diverse computing environments.

- **Versioning and Adaptability:** Solutions for handling version control, deployment consistency, and ensuring application adaptability to new platforms.

**Continuous Monitoring and Performance Enhancement**

- **Real-Time Monitoring:** Developing methodologies for continuous performance monitoring, identifying bottlenecks, and ensuring the efficient execution of CFD applications.

- **Code Instrumentation for Optimization:** Techniques to integrate performance analysis and identify areas for optimization through intelligent code instrumentation.

**General Strategies for Modular CFD Software Design**

- **Modularity and Maintainability:** Approaches for creating scalable, modular CFD software that remains maintainable over time.

- **Case Studies and Success Stories:** Showcasing successful case studies that illustrate the effective implementation of CI/CD pipelines in real-world CFD research groups.

This second iteration aims to broaden the scope, further emphasize the importance of
collaboration and scalability, and highlight new strategies emerging in CI/CD practices
for CFD applications.

---

<img loading="lazy" src="/ParCFD2025.github.io/img/damien.png" alt="Invited Speakers" style="width: 200px; height: auto; display: block; margin: 0 auto"/>

## Damien Dosimont - Barcelona Supercomputing Center, Computer Applications in Science and Engineering (CASE) Department

Dr. Damien Dosimont obtained a BSc in Electronics (2009) and MSc in Computer Science from Université Pierre et Marie Curie - Paris VI (2011) and holds a Ph.D. in Computer Science from the Université Grenoble-Alpes (2015), done within Inria Rhône-Alpes, in the MOAIS team. He is currently working as a researcher at the Barcelona Supercomputing Center since 2015. His main scientific interests focus on the performance analysis of complex HPC systems through innovative methods based, for instance, on data aggregation and information theory, topics such as I/O optimization, CPU/GPU co-execution, and machine learning. He is currently the main developer and DevOps leader of the multiphysics simulation code Alya.

---

<img loading="lazy" src="/ParCFD2025.github.io/img/guillaume.png" alt="Invited Speakers" style="width: 200px; height: auto; display: block; margin: 0 auto"/>

## Guillaume Houzeaux - Barcelona Supercomputing Center, Computer Applications in Science and Engineering (CASE) Department

Since 2005, Dr. Guillaume Houzeaux has led the ”Physical and Numerical Modeling” team at the Barcelona Supercomputing Center in Spain. He is a key architect of the Alya HPC simulation code, which is applied in fields such as aeronautics, combustion, wind energy, and biomedicine. His research is centered on High Performance Computational Mechanics, with a particular focus on high-performance computing with applications in biomedicine. This involves physical modelling, mathematical algorithms, adaptive mesh refinement, code development following a CI/CD methodology and code optimization, all driven by the objective of efficient use of parallel resources.

---

<img loading="lazy" src="/ParCFD2025.github.io/img/dennis.png" alt="Invited Speakers" style="width: 200px; height: auto; display: block; margin: 0 auto"/>

## Dennis Hoppe - High-Performance Computing Center (HLRS) of the University of Stuttgart, Converged Computing Department

Dennis Hoppe is head of the Converged Computing department at the High Performance Computing Center Stuttgart (HLRS). He is also the project manager of the AI factory HammerHAI and the technical lead of the Centre of Excellence, HiDALGO 2. He is also coordinating the realization of the EuroHPC CI/CD pilot platform. With more than a decade of experience in high-performance computing, cloud technologies, and AI, his work focuses on integrating novel technologies with HPC, supporting industrial adoption, and contributing to national and European AI and HPC initiatives.

---

<!--

<img loading="lazy" src="/ParCFD2025.github.io/img/2025_mexico.jpg" alt="Invited Speakers" style="width: 200px; height: auto; display: block; margin: 0 auto"/>

## Lennart Schneiders - SIEMENS Digital Industries Software

Lennart Schneiders is a Software Engineer and researcher at Siemens Digital Industries Software. He received his PhD from RWTH Aachen University in 2017. Until 2022, he was a postdoctoral researcher at RWTH Aachen, Jülich Aachen Research Alliance, and California Institute of Technology. Lennart is currently a developer of the multiphysics CFD software Simcenter STAR-CCM+. His research interests lie in numerical method development, turbulent multiphase flow, and high-performance computing.

**Title of Lennart&#x27;s keynote lecture:** *The intricacies of adaptive unstructured mesh refinement for industrial flows.*

**Abstract:**

*The simulation of industrial flows is associated with significant uncertainties arising from the quality of the computational mesh. In many industries, meshing therefore is considered an expert job. With the advances in parallel computing and GPU hardware reducing solver times, meshing can become a bottleneck in certain industrial workflows. While adaptive mesh refinement (AMR) is an intriguing approach to alleviate some of those problems, developing such a technique in a robust form is a challenge in its own.*

*In this talk, the intricacies of developing a general purpose AMR scheme are discussed. This includes the definition of generic solution-based refinement strategies. And it will be demonstrated that refining an unstructured mesh does not automatically guarantee lower truncation errors, but can even lead to the opposite.*

---

<img loading="lazy" src="/ParCFD2025.github.io/img/2025_mexico.jpg" alt="Invited Speakers" style="width: 200px; height: auto; display: block; margin: 0 auto"/>

## Christian Hasse - Technical University Darmstadt, Simulation of reactive Thermo-Fluid Systems

Christian Hasse is full professor in the Department of Mechanical Engineering at Darmstadt University of Technology. He holds the chair of Simulation of reactive Thermo-Fluid Systems. He has supervised successfully more than 30 PhD students and currently 25 PhD students and post-docs are working in his group. He has more than 270 peer-reviewed publications and has served in multiple editorial boards and as associate/guest editor. He is organizer of scientific workshops and conferences focusing on sustainable combustion to achieve net zero emissions.

Prof. Hasse is elected Fellow of the Combustion Institute for his contributions on turbulent combustion, solid fuel combustion, multi-phase flow and soot formation. He has been elected to the Board of Directors of the International Combustion Institute in 2024. His main research interests are modeling and high-fidelity simulation of reactive and non-reactive flows, especially for CO2-free and CO2-neutral fuels such as hydrogen, ammonia, biomass, E-fuels and metals. In addition to fundamental studies on flame structures and dynamics, he also actively works on transferring these results to real-world applications including (aero-)engines, boilers and processes chemical engineering. For these topics, his group has developed a number of high-fidelity software applications that are deployed national Tier-2 and European Tier-0/1 supercomputers. In 2024 he has received an ERC Advanced Grant on aluminum steam combustion in which he aims to unravel the fundamental properties of pressurized Al-steam flames for the entire scientific chain, from single particles to turbulent flames with millions of particles, through a well-orchestrated combination of high-fidelity simulations, advanced modeling, and tailored experiments.

**Title of Christian&#x27;s keynote lecture:** *How high-fidelity simulations of hydrogen combustion on supercomputers accelerate the energy transition.*

**Abstract:**

*Reactive Computational Fluid Dynamics (rCFD) has become an indispensable tool in fundamental and applied research. In addition, rCFD is used in industrial design, such as aero engine combustors or gas turbines. This success is based on the combination of decades of scientific model development, efficient numerics and ever-increasing computing power. This situation is about to change as both the energy system (1) and the HPC architecture (2) are undergoing disruptive changes.*

*First, the urgent need to shift from fossil fuels to renewable fuels such as hydrogen requires the redesign of energy conversion systems due to the completely different combustion characteristics of renewable fuels. Combustion models for high-fidelity simulations are lacking and must be developed based on in-depth physical understanding. Second, the next generation of supercomputers will be mostly based on GPUs rather than CPUs. Efficient use of these systems will require a new class of CFD software with specialized numerics.*

*In this talk I will first introduce the role of rCFD in combustion system design before I highlight the role of hydrogen in the energy transition and how it differs from conventional fuels. After discussing the impact of GPU-based supercomputers on rCFD software development, I will present how GPU-based direct numerical simulations can unravel the complexities of hydrogen combustion.*

*In summary, in a rapidly changing environment, simulations on upcoming Exascale systems will provide physical insights that were deemed impossible just a few years ago. This will increase the impact of rCFD on the entire spectrum from fundamental science to industrial design of innovative systems.*

-->