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

            - 2026 Spring Semester
            
            - 2025 Spring Semester


            **Microscopic Modelling and Simulation of Traffic Operations (101-0492-00L)** 

            - 2025 Autumn Semester
            
            - 2024 Autumn Semester

            
            
            **Projektübung Verkehr / Transportation Engineering Lab (103-0230-00 G)** 

            - 2026 Spring Semester
            
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
        - title: Rasim Ibadov
          company: Bachelor, Computer Science, ETH Zurich
          company_logo: x_student_rasim
          location: Zurich, Switzerland
          date_start: '2025-10-01'
          date_end: '2026-02-28'
          description: '
            **Topic:** Replication Study of a RL-based Traffic Optimization Paper


            **Abstract:** This study replicates and critically evaluates the claims made in the work by Deng et al. (2023), titled “Automated Traffic State Optimization in the Weaving Area of Urban Expressways by a Reinforcement Learning‐Based Cooperative Method of Channelization and Ramp Metering,” [1] published in the Journal of Advanced Transportation. The original study proposes a cooperative method that combines channelization and reinforcement‐learning‐based ramp metering and reports substantial improvements in lane‐wise vehicle speeds in a freeway weaving section. The primary objective of this replication is to verify whether the reported performance improvements can be reproduced under an independently implemented but methodologically faithful setup. To this end, we reconstructed the complete simulation environment and implemented all control strategies from scratch using the SUMO microscopic traffic simulation framework. Beyond a strict replication, this work also establishes a transparent and fully documented benchmarking environment, enabling systematic comparison with both classical and learning‐based controllers in future studies.


            **Profile:** https://www.linkedin.com/in/rasim-ibadov-b4a3b4235/
          '

        - title: Qiyuan Zhang
          company: Master, Electrical Engineering, ETH Zurich
          company_logo: x_student_qiyuanz
          location: Zurich, Switzerland
          date_start: '2025-09-18'
          date_end: '2026-01-05'
          description: '
            **Topic:** Reproduction Study Of RL Control for Intelligent Road Transportation Systems


            **Abstract:** This semester project investigates the reproducibility of two reinforcement learning–based ramp metering approaches proposed by Fares et al. and Wang et al.
          '

        - title: Natcha Jengjirapas
          company: Master, Computer Science, ETH Zurich
          company_logo: x_student_natchaj
          location: Zurich, Switzerland
          date_start: '2025-10-01'
          date_end: '2025-12-31'
          description: '
            **Topic:** Reproduction Study Of RL Control for Intelligent Road Transportation Systems


            **Abstract:** This semester project investigates the reproducibility of two reinforcement learning–based ramp metering approaches proposed by Lu et al. The first uses tabular Q-learning for local ramp metering to minimize total time spent (TTS) under on-ramp queue constraints, while the second extends this framework to coordinated ramp metering by incorporating an equity objective based on the variance of total waiting time (TWT). Both methods are independently reimplemented from the published descriptions using a macroscopic traffic simulation based on the asymmetric cell transmission model, without access to original code or supplementary data. Reproduced results are compared with those reported in the original studies using the same performance metrics and reconstructed demand scenarios. The results show that the baseline Q-learning controller largely reproduces the reported efficiency and queue management behavior, while the equity-aware extension captures the intended efficiency–equity trade-off with some numerical discrepancies. These findings support the main conclusions of the original studies while highlighting reproducibility challenges arising from incomplete methodological specification.


            **Profile:** https://www.linkedin.com/in/njengjir/
          '

        - title: Elyse Winstral
          company: Master, Applied Mathematics, ETH Zurich
          company_logo: x_student_ewinstral
          location: Zurich, Switzerland
          date_start: '2025-09-22'
          date_end: '2026-03-13'
          description: '
            **Topic:** Individual, Urban Trip Reconstruction via BMS and Loop Detector Data


            **Abstract:** Loop detectors and Bluetooth Media Access Control Scanners (BMS) have been used tomeasure various vehicle data in fixed locations and zones respectively. Recently, there has been interest in tracing individual vehicle trips with this data. While loop detectors are relatively common in European cities, BMS offers a more cost-effective way to gather additional information on traffic conditions. The aim of this thesis is to fuse BMS and loop detector data, and subsequently use the enriched data collection to reconstruct individual vehicle trips in a simulated, urban setting with a Markov Decision Process estimation method. Individual trip reconstruction may bolster traffic state analysis and prediction on meso- and macro-scopic levels.


            **Profile:** https://www.linkedin.com/in/elyse-winstral/
          '

        - title: Omar Alami Badissi
          company: Master, Mechanical Engineering, ETH Zurich
          company_logo: x_student_oalami
          location: Zurich, Switzerland
          date_start: '2025-03-15'
          date_end: '2025-09-15'
          description: '
            **Topic:** Coordinated Control Algorithm For Fairness In Ramp Metering


            **Abstract:** Traffic assistance schemes typically tend to focus on global system efficiency which can come at the cost of equity among users of the road. This paper proposes C-ALINEA, a new ramp metering algorithm that makes inter-ramp relationships explicit in order to tackle equity issues without losing throughput. As opposed to classical isolated controllers, C-ALINEA generates a coherent intelligence by connecting each ramp to two upstream and two downstream neighbors. The methodology employs SUMO microsimulations to evaluate the algorithm on the A10 ring road around Amsterdam, a heavily congested urban freeway with complex ramp interactions. C-ALINEA is compared against conventional ALINEA and other state-of-the-art approaches using calibrated traffic demand patterns from the typical A10 ring road. Performance metrics include mainline throughput, ramp waiting times, spatial equity indices, and system resilience. Results have shown that C-ALINEA can achieve a more fair sharing of congestion impacts over different entry points along the A10. With its five-ramp horizon, the algorithm has the possibility to predict downstream bottlenecks and harmonize the response on adjacent ramps. The results are encouraging in that coordination-based ramp metering appears to be a viable approach to socially acceptable traffic management solutions in urban settings.


            **Profile:** https://www.linkedin.com/in/omar-alami-badissi-97489920b/
          '

        - title: Bertola Manon
          company: Master, Civil- & Traffic Engineering, ETH Zurich
          company_logo: x_student_mbertola
          location: Zurich, Switzerland
          date_start: '2025-02-24'
          date_end: '2025-06-30'
          description: '
            **Topic:** Impacts of Transit Detour Traffic on Local Accessibility


            **Abstract:** This thesis investigates how congestion at the Gotthard tunnel’s north portal and resulting detour traffic affect local accessibility in the Urner Valley, and evaluates the effects of a policy restricting transit vehicles to the highway. A calibrated SUMO microsimulation model, based on loop-detector data, replicates traffic patterns for three representative 2024 case study days with varying congestion levels. Accessibility is assessed via simulated travel times to both the regional center (Altdorf) and the urban center (Zurich). Results show that road-based access degrades sharply on high-transit days, particularly in upper-valley towns, where public transport alternatives are weak. The policy experiment has minimal impact on low-demand days but significantly improves local accessibility on congested days, while increasing delays for through traffic. These findings highlight trade-offs between aggregate efficiency and local equity, and suggest the value of targeted, demand-responsive interventions.


            **Profile:** https://www.linkedin.com/in/manon-bertola/
          '

        - title: Justin Weiss
          company: Bachelor, Mechanical Engineering, ETH Zurich
          company_logo: x_student_jweiss
          location: Zurich, Switzerland
          date_start: '2025-02-17'
          date_end: '2025-06-30'
          description: '
            **Topic:** Infrastructural Control Algorithm for Fairness in Road Traffic Engineering


            **Abstract:** This thesis investigates whether fairness and efficiency can be jointly achieved in urban traffic signal control at intersections. While efficiency has traditionally been the primary objective in signal control strategies, the consideration of fairness has received comparatively limited attention. To address this gap, a controller inspired by the adaptive systems SCOOT and SCATS, referred to as SCOSCA, is developed. SCOSCA incorporates the three core optimizers of these systems: an offset optimizer, a cycle length optimizer, and a green phase optimizer. Building upon this foundation, two fairness-augmented variants are introduced: SCOSCAFAIRV1, which integrates a fairness-aware green phase optimizer, and SCOSCAFAIRV2, which additionally includes a secondary real-time fairness controller. The controllers are evaluated on both a synthetic toy model and a realistic arterial road network in a case study, using the microscopic traffic simulation platform SUMO. Several fairness ideologies, Egalitarian, Rawlsian Harsanyian and Utilitarian, are formalized through respective performance metrics. Bayesian Optimization is applied to tune the controllers towards these fairness objectives. The findings show that fairness could be improved with minimal or no loss in efficiency; in the case study, efficiency could even be enhanced. Moreover, the results observed for SCOSCA, SCOSCAFAIRV1 and SCOSCAFAIRV2 under different optimization goals suggest that optimizing for a single performance metric often leads to improvements across multiple fairness indicators. This interdependence highlights the importance of explicitly incorporating fairness into the design of future traffic control algorithms.


            **Profile:** https://www.linkedin.com/in/justin-weiss-36b779269/
          '

        - title: Lea Künstler 
          company: Master, Computer Science, ETH Zurich
          company_logo: x_student_lkuenstler
          location: Zurich, Switzerland
          date_start: '2024-12-01'
          date_end: '2025-06-15'
          description: '
            **Topic:** Fair Perimeter Control using Queue Balancing


            **Abstract:** This thesis investigates the integration of fairness into perimeter control strategies for urban traffic management. While perimeter control effectively reduces congestion by regulating inflow into protected zones, existing approaches typically prioritize system efficiency, often overlooking the equitable distribution of delays across users. A simulation-based evaluation demonstrates that basic perimeter control not only improves total and internal delays but also enhances fairness metrics, including the Gini coefficient and Jain’s fairness index. Building on this, queue balancing strategies inspired by computer network resource allocation were implemented to assess their impact on fairness. Results show that under uniform demand, queue balancing provides no consistent benefits. However, in varied demand scenarios, where certain entry points are more congested, fairness improvements were observed. A real-world scenario using the San Francisco network highlights the practical challenges of implementation, such as queue spillbacks and the need for more adaptive control mechanisms. Overall, the findings suggest that fairness-aware perimeter control is feasible and beneficial under realistic conditions, but further work is needed to ensure consistent and scalable deployment.


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
