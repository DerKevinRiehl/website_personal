---
title: 'Experience & Vita'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title:  
      text: <br><br>
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
          filename: banner/cv_5.bmp # oemydyls.bmp # bo2r586o.bmp # CV_banner.bmp
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
          
  - block: markdown
    content:
      title: Curriculum Vitae
      subtitle: My experience & vita
      text: On this page you will find my...<ul><li>Certifications</li><li>Skills</li><li>Work Experience</li><li>Awards</li><li>Education</li></ul>
    design:
      columns: 2

  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '3'
      
  - block: experience
    content:
      title: Work Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Doctoral Researcher
          company: ETH AI Center & Institute for Transport Planning & Systems, ETH Zurich
          company_url: 'https://www.ivt.ethz.ch/'
          company_logo: eth
          location: Zurich, Switzerland
          date_start: '2023-11-01'
          date_end: ''
          description: ''

        - title: Senior Software Engineer
          company: Credit Suisse / Swiss IT Security Group
          company_url: 'https://www.credit-suisse.com/'
          company_logo: creditsuisse
          location: Zürich, St Gallen, Switzerland
          date_start: '2022-10-01'
          date_end: '2023-10-31'      
          description: '• Design & Implementation & Integration of Applications (Java, Python, Go) & Pipelines (Jenkins, Gitlab) 
                        • Clean Code & Software Refactoring • Requirements Engineering and Stakeholder Management 
                        • Software Test Automation for backend systems (client finance industry) and browser based GUIs (selenium) 
                        • Development of Gateway software for financial transactions (SIC5 instant payments) for client in finance industry' 

        - title: Dev-Quant and Consultant
          company: UBS
          company_url: 'https://www.mckinsey.com/'
          company_logo: ubs
          location: Zürich, Switzerland
          date_start: '2021-10-01'
          date_end: '2022-09-30'      
          description: '• Quant Support in developing and optimizing financial, risk, big data and ML models within UBS 
                        • Software Development & Testing, Microsoft Azure migration of LNF Models in Group Treasury (Python, Spark, Databricks) 
                        • Development of clients to establish software testing framework according to ISTQB standard 
                        • Consultant to support build-up of in-house consulting, organizer of L&D series “QuantSpire”' 

        - title: Intern in Strategy Consulting
          company: McKinsey & Company
          company_url: 'https://www.mckinsey.com/'
          company_logo: mckinsey
          location: Frankfurt am Main & Berlin, Germany
          date_start: '2021-05-01'
          date_end: '2021-07-31'      
          description: '• Digital Platform scale-up project for a US client based in public healthcare industry.
                        • User Engagement strategy, event strategy and data warehouse integration.' 

        - title: Intern in Strategy Consulting
          company: AT Kearney
          company_url: 'http://www.kearney.com/'
          company_logo: kearney
          location: Düsseldorf, Germany
          date_start: '2020-10-01'
          date_end: '2020-12-31'      
          description: '• International digitalization project at market leader in FTL logistics, Digital Transformation, Product customization and integration.
                        • Interviewing of more than 40 stakeholders, Requirements Engineering, UML design of software customization.' 

        - title: Intern in Investment Banking
          company: DZ Bank AG
          company_url: 'https://www.dzbank.de/'
          company_logo: dzbank
          location: Frankfurt am Main, Germany
          date_start: '2020-04-01'
          date_end: '2020-07-31'      
          description: '• Data Science, Programming, Process Optimization.
                        • Business intelligence, process management, algorithm development, big data analysis.
                        • Analysis of derivatives trading data, optimization of automated process and IT infrastructure.' 

        - title: Working Student & Researcher
          company: Fraunhofer IGD
          company_url: 'https://www.igd.fraunhofer.de/'
          company_logo: fraunhoferigd
          location: Darmstadt, Germany
          date_start: '2019-04-01'
          date_end: '2020-01-31'      
          description: '• Biometrics, Machine Learning, Privacy Enhancement.
                        • Worked on cutting edge research on machine learning, face recognition and privacy enhancement.
                        • Analytic and software, development, implementation and evaluation of PE-MIU algorithms in Python.' 

        - title: Research Assistant
          company: Technische Universität Darmstadt
          company_url: 'https://www.tu-darmstadt.de/'
          company_logo: tudarmstadt
          location: Darmstadt, Germany
          date_start: '2017-01-01'
          date_end: '2017-09-30'      
          description: '• Research assistant, chair of international economics, Dr. Johannes Rode.' 

        - title: Tutor
          company: Technische Universität Darmstadt
          company_url: 'https://www.tu-darmstadt.de/'
          company_logo: tudarmstadt
          location: Darmstadt, Germany
          date_start: '2016-10-01'
          date_end: '2017-02-28'      
          description: '• Tutor, chair of communications enginering lab, Prof. Dr. Marius Pesavento, course "Signal Processing".' 

        - title: Research Assistant
          company: Technische Universität Darmstadt
          company_url: 'https://www.tu-darmstadt.de/'
          company_logo: tudarmstadt
          location: Darmstadt, Germany
          date_start: '2016-02-01'
          date_end: '2019-10-31'      
          description: '• Research assistant, chair of international economics, Prof. Dr. Volker Nitsch.' 

        - title: Intern in Technical Project Management & Agile Coaching
          company: VW China / CRM Factory
          company_url: 'https://www.mcon-group.com/#global'
          company_logo: volkswagen
          location: Beijing, China
          date_start: '2018-06-01'
          date_end: '2018-09-30'      
          description: '• Project manager and SCRUM master for team of 12 stakeholders at customer Volkswagen China.
                        • IT product development and intranet deployment of test-automation software application at customer site.' 

        - title: Intern in Electrical Engineering & Robotics
          company: Continental
          company_url: 'https://www.continental.com/de/'
          company_logo: continental
          location: Frankfurt am Main, Germany
          date_start: '2018-01-01'
          date_end: '2018-03-31'      
          description: '• Assembly & programming of turtlebot2i robot, combined with LIDAR sensor.
                        • Linux usage. 
                        • Robot Operating System (ROS).
                        • Evaluation of simultaneous localization and moving (SLAM) algorithms for ROS on Ubuntu.' 

        - title: Intern in Electrical Engineering & Chip Design
          company: Robert Bosch GmbH
          company_url: 'https://www.bosch-home.com/'
          company_logo: bosch
          location: Reutlingen, Germany
          date_start: '2014-07-01'
          date_end: '2014-07-31'      
          description: '• Visiting micro-chip design & manufacturing plant as part of the competition-price of "Invent A Chip". ' 

        - title: Intern in Electrical Engineering & Chip Design
          company: invenio Engineering Services GmbH
          company_url: 'https://www.invenio.net/'
          company_logo: invenio
          location: Rüsselsheim am Main, Germany
          date_start: '2013-07-01'
          date_end: '2013-07-31'      
          description: '• Using laboratory facilities for participation in competition "Invent A Chip", to manufacture and solder PCB circuits.' 

        - title: Intern in Electrical Engineering
          company: invenio Engineering Services GmbH
          company_url: 'https://www.invenio.net/'
          company_logo: invenio
          location: Rüsselsheim am Main, Germany
          date_start: '2012-10-01'
          date_end: '2012-10-31'      
          description: '• Electrical engineering, circuit design, and PCB layout design. 
                        • Manufacturing of PCB platina using acid, soldering of components.' 

        - title: Intern in Modell Building & Prototyping
          company: Adam Opel AG
          company_url: 'https://www.opel.com/'
          company_logo: opel
          location: Rüsselsheim am Main, Germany
          date_start: '2011-07-01'
          date_end: '2011-07-31'      
          description: '• Visiting the modell building & prototyping workshop.
                        • Learn to use different tools to work with wood and other materials.
                        • Learn about CNC machines and 3D printing.' 

        - title: Intern in Quality Management
          company: Adam Opel AG
          company_url: 'https://www.opel.com/'
          company_logo: opel
          location: Rüsselsheim am Main, Germany
          date_start: '2011-01-01'
          date_end: '2011-01-31'      
          description: '• Quality Management along the car manufactoring process. 
                        • Visiting and analysis of the whole manufacturing line and factory area.
                        • Participation in test driving, physical inspection, and quality management with robots.' 
    design:
      columns: '2'
      
  - block: experience
    content:
      title: Education
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Doctoral Researcher
          company: ETH AI Center & Institute for Transport Planning & Systems, ETH Zurich
          company_url: 'https://www.ivt.ethz.ch/'
          company_logo: eth
          location: Zurich, Switzerland
          date_start: '2023-11-01'
          date_end: ''
          description: ''

        - title: Master Thesis, Bioinformatics & Computational Biology
          company: University of Cambridge
          company_url: 'https://www.cam.ac.uk/'
          company_logo: unicambridge
          location: Cambridge, United Kingdom
          date_start: '2020-10-01'
          date_end: '2021-04-30'
          description: 'Studies on bioinformatics, computational biology, transposon research, machine learning.'

        - title: Master of Science, Industrial Engineering (Electrical Engineering, IT & Finance)
          company: Technische Universität Darmstadt
          company_url: 'https://www.tu-darmstadt.de/'
          company_logo: tudarmstadt
          location: Darmstadt, Germany
          date_start: '2014-10-01'
          date_end: '2017-12-31'
          description: 'Focus studies on artificial intelligence, machine learning, scientometrics, natural lanugage processing, advanced control theory, econometrics.'

        - title: Bachelor of Science, Industrial Engineering (Electrical Engineering, IT & Finance)
          company: Technische Universität Darmstadt
          company_url: 'https://www.tu-darmstadt.de/'
          company_logo: tudarmstadt
          location: Darmstadt, Germany
          date_start: '2014-10-01'
          date_end: '2017-12-31'
          description: 'Fundamentals of higher math, electrical engineering, control theory, system dynamics, corporate finance, economics, statistics.'

        - title: Highschool Student / German Abitur
          company: Max Planck Gymnasium Rüsselsheim
          company_url: 'https://www.max-planck-schule.de/'
          company_logo: maxplanckschule
          location: Rüsselsheim am Main, Germany
          date_start: '2006-06-01'
          date_end: '2014-06-01'
          description: 'Best Abitur (high school diploma) of the year in school, and best exam in physics examination of the year in Hessen.
                        Focus studies: Physics & Math.'

        - title: Propaedeutic course, Math for Business
          company: Young Business School
          company_url: 'https://www.ybs.de/'
          company_logo: youngbusinesschool
          location: Heidelberg, Germany
          date_start: '2011-01-01'
          date_end: '2012-12-30'
          description: ''
    design:
      columns: '2'

---
