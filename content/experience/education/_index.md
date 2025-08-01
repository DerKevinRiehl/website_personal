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
          filename: banner/cv_5.bmp
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
          
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
          date_start: '2018-10-01'
          date_end: '2021-04-30'
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
          filename: banner/cv_5.bmp
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
---
