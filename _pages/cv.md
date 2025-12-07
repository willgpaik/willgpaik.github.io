---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Professional Experience
=====
* HPC Machine Learning Performance Engineer  
*Research Computing, Northeastern University* | Jan 2025 - Present
    * Optimizing ML workloads on HPC clusters
    * Performance analysis and benchmarking for AI/ML applications
    * Supporting researchers with computational workflow optimization

* HPC Software Consultant  
*Institute for Computational and Data Sciences, Penn State* | Jan 2017 - Dec 2024
    * 8 years supporting 500+ researchers across multiple disciplines
    * Cluster performance optimization and user support
    * Developed containerized environments for reproducible research (Singularity Hub contributor)
    * System monitoring, resource allocation, and job optimization

* Parallel Computing Support Application Engineer  
*MathWorks* | Summer 2021 (Internship)
    * Optimized parallel computing toolboxes for MATLAB
    * Developed performance benchmarks for distributed computing
    * Created documentation for HPC integration with MATLAB

Technical Expertise
=====
* HPC and Infrastructure
    * **Schedulers**: Slurm, PBS (Job arrays, dependency chains, resource optimization)
    * **Parallel Computing**: MPI (OpenMPI, Intel MPI), OpenMP, CUDA
    * **Storage Systems**: NFS, parallel filesystems, data management strategies
    * **Containerization**: Singularity/Apptainer, Docker for HPC environments
    * **Automation**: Ansible playbooks, bash scripting, system provisioning
    * **Monitoring**: Performance metrics, resource utilization analysis

*  Software Development
    * **Languages**: Python, C/C++, Fortran, MATLAB, Shell scripting
    * **Version Control**: Git, GitLab CI/CD
    * **Performance Tools**: Profiling, optimization, bottleneck analysis

Projects & Competitions
=====
* Independent HPC Infrastructure Lab (2025 - Present)
    * Multi-node cluster with automated deployment via Ansible
    * Comparative analysis of scheduler configurations
    * Cost-benefit modeling for small-scale HPC deployments
    * Open-source tools for cluster management

* 4D LiDAR SLAM Optimization (2024 - 2025)
    * **Computational Focus**: Parallelized point cloud processing algorithms
    * Optimized memory usage for large-scale sensor data
    * ROS 2 simulation environment with distributed computing

* NIST First Responder UAS Indoor Challenge (2022)
    * Award: 3rd place + First responder's choice (Prize: $80,000)
    * Design and develop a custom built quadcopter for GPS denied indoor scenarios and emergency situations
    * Website: [https://www.nist.gov/ctl/pscr/voxeltk6](https://www.nist.gov/ctl/pscr/voxeltk6)

* Interactive and Collaborative Robot Assist Project (2022)
    * Pennsylvania State University (Robot Ethics and Aerial Vehicles Lab)
    * Design and build robots and research models to evaluate human behavior in simulated environments

* 29th and 30th Annual Intelligent Ground Vehicle Competition (2022 and 2023)
    * Team lead, design and build autonomous ground vehicle that carries up to payload of 20 lbs

* VFS Design-Build-Vertical Flight Student Competition (2021 and 2022)
    * Award: 3rd place (2022), 1st place in preliminary reports + Best Computational Simulation Award (2021) (Prize: $500)
    * Design and build a quadcopter and simulations
    * Website: [https://news.engr.psu.edu/2022/vertical-flight-student-competition.aspx](https://news.engr.psu.edu/2022/vertical-flight-student-competition.aspx)

* 9th and 10th ESA Global Trajectory Optimization Competition (2017 and 2019)
    * Developed parallel algorithms for complex trajectory optimization simulations
    * Website: [https://www.psu.edu/news/academics/story/penn-state-students-compete-solve-problem-trajectory-design](https://www.psu.edu/news/academics/story/penn-state-students-compete-solve-problem-trajectory-design)

Education
=====
* PhD in Aerospace Engineering      Pennsylvania State University (2024)
    * Dissertation: Multiple Gravity-Assist Trajectory Design with Continuous-Thrust Synergetic Maneuvers

* MS in Aerospace Engineering       Pennsylvania State University (2015)
    * Thesis: Optimal Orbit Raising Via Particle Swarm Optimization

* BS in Aerospace Engineering       Pennsylvania State University (2013)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
 
[//]: Resume
[//]: =====
[//]: [Ghanghoon Paik Resume](../files/Ghanghoon_Paik_resume.pdf)
