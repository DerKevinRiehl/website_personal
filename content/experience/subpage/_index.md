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
          filename: banner/cv_6.png
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: collection
    content:
      title:  Technologies
      text: 
            <h2> <i class="fa-solid fa-hammer"></i> Operating Systems </h2>
            <marquee behavior="scroll" direction="left">
              <table>
                <tr> 
                  <td> Python </td>
                  <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </td>

                  <td> Java </td>
                  <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </td>
                </tr>
                <tr>
                  <td> <img src="/media/icons/devicon/python.svg" /> </td> <td> </td>

                  <td> <img src="/media/icons/devicon/java.svg" /> </td>
                   
                </tr>
              </table>
            </marquee>
            
            <h2> <i class="fa-solid fa-hammer"></i> IDEs </h2>
            <marquee behavior="scroll" direction="left">
              <table>
                <tr> 
                  <td> Spyder </td>
                  <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </td>
                  <td> VSCode </td>
                  <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </td>
                  <td> Eclipse </td>
                  <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </td>
                  <td> PyCharm </td>
                  <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </td>
                  <td> Jupyter </td>
                  <td> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </td>
                </tr>
                <tr>
                  <td> <img src="/media/icons/devicon/spyder.svg" /> </td> <td> </td>
                  <td> <img src="/media/icons/devicon/vscode.svg" /> </td> <td> </td>
                  <td> <img src="/media/icons/devicon/eclipse.svg" /> </td> <td> </td>
                  <td> <img src="/media/icons/devicon/pycharm.svg" /> </td> <td> </td>
                  <td> <img src="/media/icons/devicon/jupyter.svg" /> </td> <td> </td>
                </tr>
              </table>
            </marquee>
      filters:
        folders:
          - project

  - block: skills
    content:
      title: 'Hard Skills'
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '3'

  - block: skills
    content:
      title: 'Soft Skills'
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin2_softskills
    design:
      columns: '3'

  - block: skills
    content:
      title: 'Soft Skills'
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin2_softskills
    design:
      columns: '3'
    
  - block: contact
    id: contact
    content:
      title: Contact Me
      email: kriehl@ethz.ch
      directions: Institute for Transport Planning and Systems (IVT)
      address:
        street: Visit Me - Stefano-Franscini-Platz 5, HIL F 36.2, ETH Zurich
        city: Zurich
        postcode: '8093'
        country: Switzerland
        country_code: CH
      office_hours:
      - 'Monday to Friday, 08:00 to 18:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '47.40866436774559'
        longitude: '8.506809749712739'  
      contact_links:
      - icon: x
        icon_pack: fab
        name: Follow Me
        link: https://x.com/derriehl
      - icon:  devicon/pycharm
        icon_pack: custom
        name: Subscribe Me
        link: https://www.youtube.com/@derKevinRiehl
      - icon: github
        icon_pack: fab
        name: Fork Me
        link: https://github.com/DerKevinRiehl
      - icon: google-scholar # Alternatively, use `google-scholar` icon from `ai` icon pack
        icon_pack: ai
        name: Cite Me
        link: https://scholar.google.com/citations?user=-91B6EgAAAAJ&hl=de&oi=ao
      - icon: linkedin
        icon_pack: fab
        name: Link Me
        link: https://www.linkedin.com/in/kevin-riehl-07819a156/
      - icon: orcid
        icon_pack: ai
        name: orcID Me
        link: https://orcid.org/0000-0003-4620-8379
      - icon: scopus
        icon_pack: ai
        name: SCOPus Me
        link: https://www.webofscience.com/wos/author/record/JCO-7267-2023
    design:
      columns: '2'
---
