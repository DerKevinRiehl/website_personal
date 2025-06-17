---
title: 'Teaching'
date: 2025-06-17
type: landing

design:
  # Section spacing
  spacing: '2rem'

# Page sections
sections:
  - block: collection
    content:
      title:  
      text: <br><br><br><br>
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: banner/cv_3.bmp
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
          
  - block: experience
    content:
      title: Lectures
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Lecturer
          company: ETH AI Center & Institute for Transport Planning & Systems, ETH Zurich
          company_url: 'https://www.ivt.ethz.ch/'
          company_logo: eth
          location: Zurich, Switzerland
          date_start: '2024-09-01'
          date_end: ''
          description: ' 
            
            **Computer Programming & Data Science – An Introduction with Python (101-0720-00L)** 

            - 2025 Spring Semester


            **Microscopic Modelling and Simulation of Traffic Operations (101-0492-00L)** 

            - 2024 Autumn Semester

            - 2025 Autumn Semester
            
            
            **Projektübung Verkehr / Transportation Engineering Lab (103-0230-00 G)** 

            - 2025 Spring Semester
          '

        - title: Tutor
          company: Technische Universität Darmstadt
          company_url: 'https://www.tu-darmstadt.de/'
          company_logo: tudarmstadt
          location: Darmstadt, Germany
          date_start: '2016-10-01'
          date_end: '2017-02-28'      
          description: '
            **Deterministische Signale und Systeme / Signal Processing (Prof. Dr. A. Klein, Prof. Dr.-Ing. M. Pesavento)** 

            - 2016 Autumn Semester
          ' 

    design:
      columns: '2'

          
  - block: experience
    content:
      title: Students / Thesis
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Omar Alami Badissi
          company: Master, Mechanical Engineering, ETH Zurich
          company_logo: x_student_oalami
          location: Zurich, Switzerland
          date_start: '2025-03-15'
          date_end: '2025-09-15'
          description: '
            **Topic:** (Ongoing)


            **Abstract:** (Ongoing)


            **Profile:** https://www.linkedin.com/in/omar-alami-badissi-97489920b/
          '

        - title: Bertola Manon
          company: Master, Civil- & Traffic Engineering, ETH Zurich
          company_logo: x_student_mbertola
          location: Zurich, Switzerland
          date_start: '2025-02-24'
          date_end: '2025-06-30'
          description: '
            **Topic:** (Ongoing)


            **Abstract:** (Ongoing)


            **Profile:** https://www.linkedin.com/in/manon-bertola/
          '

        - title: Justin Weiss
          company: Bachelor, Mechanical Engineering, ETH Zurich
          company_logo: x_student_jweiss
          location: Zurich, Switzerland
          date_start: '2025-02-17'
          date_end: '2025-06-30'
          description: '
            **Topic:** (Ongoing)


            **Abstract:** (Ongoing)


            **Profile:** https://www.linkedin.com/in/justin-weiss-36b779269/
          '

        - title: Lea Künstler 
          company: Master, Computer Science, ETH Zurich
          company_logo: x_student_lkuenstler
          location: Zurich, Switzerland
          date_start: '2024-12-01'
          date_end: '2025-06-15'
          description: '
            **Topic:** (Ongoing)


            **Abstract:** (Ongoing)


            **Profile:** https://www.linkedin.com/in/leakuenstler465b59182/
          '

        - title: Cedric Zeiter
          company: Bachelor, Computational Science and Engineering, ETH Zurich
          company_logo: x_student_czeiter
          location: Zurich, Switzerland
          date_start: '2025-03-01'
          date_end: '2025-05-31'
          description: '
            **Topic:** Diffusion Modelling of Air Quality and Noise - Impacts from Detour Traffic on Uri Residents A Simulation-Based Case Study of Villages near the Gotthard Road Tunnel in Uri, Switzerland


            **Abstract:** Traffic congestion near the northern entrance of the Gotthard Road Tunnel in the Swiss
            canton of Uri often leads to significant detours onto cantonal roads, diverting traffic through
            residential areas and raising concerns about the well-being of residents. While previous
            research and federally funded projects have largely focused on traffic flow optimisation,
            the perspective of affected residents has remained under-explored. This thesis addresses
            that gap by laying the foundation for a quantitative, resident-oriented assessment of the
            environmental externalities caused by traffic detours.
            Using traffic data generated by the SUMO simulation software, extended with a novel
            post-processing pipeline developed specifically for this work, the model estimates exposure
            levels of CO, NO2, PM2.5, and noise across six affected villages in the canton of Uri. The
            implementation is based on an explicit forward Euler scheme with central finite differences.
            Simulations were conducted over the course of a day for different dates, capturing both
            low- and high-congestion scenarios. The results show substantial variation in pollutant
            and noise exposure depending on the village and discuss what a reduction of traffic in Uri
            would change quantitatively.


            **Profile:** https://www.linkedin.com/in/cedric-zeiter/
          '

        - title: Yangle Zhan
          company: Master, Industrial Engineering and Management Engineering, ETH Zurich & UPC Barcelona
          company_logo: x_student_yzhan
          location: Zurich, Switzerland
          date_start: '2024-09-01'
          date_end: '2025-02-28'
          description: '
            **Topic:** Fairness on Ramp Metering - Extending ALINEA for Equitable Access and Congestion Reduction


            **Abstract:** Ramp metering systems effectively reduce freeway congestion but often face public opposition
            due to inequitable delay distribution among users. This study addresses this
            challenge by introducing EqALINEA, a fairness-enhanced extension of the ALINEA algorithm
            designed to balance efficiency and equity in freeway access. Using microsimulations
            in SUMO, we evaluate ALINEA, Upstream ALINEA, and EqALINEA across both a
            simplified network and a real-world case study of Barcelona’s Ronda de Dalt corridor.
            Results indicate that traditional ALINEA prioritizes mainline throughput at the expense
            of spatial equity, disproportionately delaying on-ramp users near bottlenecks. EqALINEA
            mitigates these disparities by incorporating fairness constraints, including maximum
            waiting thresholds and proactive queue management. This approach leads to a more
            balanced distribution of delays while maintaining overall traffic efficiency within the
            simulation time. The algorithm adapts effectively to urban environments such as the
            Ronda de Dalt, where infrastructure limitations and evolving mobility policies require
            equitable traffic management solutions.
            This study demonstrates the feasibility of integrating fairness into decentralized ramp
            metering strategies to improve public acceptance and align with sustainable urban planning
            objectives.


            **Profile:** https://www.linkedin.com/in/yangle-zhan/
          '
          
        - title: Modest Jiang
          company: Master, Civil- & Traffic Engineering, ETH Zurich
          company_logo: x_student_mjiang
          location: Zurich, Switzerland
          date_start: '2024-09-01'
          date_end: '2025-01-27'
          description: '
            **Topic:** Esslingen‘s Traffic Light Upgrade: An Evaluation 


            **Abstract:** Seven traffic light signals received new control systems in the city of Esslingen am Neckar
            in Germany. This thesis investigates the performance and efficiency during peak hours of
            the old and new traffic light control system using SUMO simulations. The older traffic
            light control system is a signal control system that operates based on a predefined Signal
            Phase and Timing (SPaT) schedule but adapts its parameters in response to real-time
            inputs from traffic detectors. The new system is a signal control system that dynamically
            determines traffic signal phases using real-time detector data and an algorithm. The
            evaluation focuses on three critical metrics: travel time, waiting time, and delay. The
            data for the old system was provided in the form of a VISSIM simulation while the
            data for the new system was provided in form of detector data. The simulation runs on
            SUMO demonstrate that the newer traffic light signal control system outperforms the
            existing system across all evaluated metrics, indicating an overall improvement in traffic
            flow efficiency. These findings underscore the benefits of implementing the updated traffic
            light control system to enhance urban mobility and reduce congestion during peak traffic
            periods.


            **Profile:** https://www.linkedin.com/in/modest-jiang/
          '
















    design:
      columns: '2'


  - block: collection
    content:
      title:  
      text: <br><br><br><br>
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: banner/cv_3.bmp
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
---
