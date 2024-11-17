---
title: Science Slam
cms_exclude: false
type: landing

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

# Optional header image (relative to `static/media/` folder).
header:
  caption: ''
  image: ''

sections:
  - block: collection
    content:
      title:  
      text: <br><br><br>
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
          filename: banner/banner_slam.png
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: Science Slams
      subtitle: Transporting science with entertainment
      text:
            These are the science slams I performed so far

            * (2024-12-07) - (Science Slam Winterthur) - "Life is not fair - Der Kampf gegen den Stau"

            * (2024-10-16) - (Science Slam Bern) - "Life is not fair - Der Kampf gegen den Stau"

            * (2024-10-11) - (Science Slam Basel) - "Life is not fair - Fighting Traffic Congestion"

            * (2024-04-30) - (FameLab, Basel) - "Life is not fair - 3 Minute Pitch"

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: masonry

  - block: collection
    id: section-1
    content:
      title: Science Slams Videos
      subtitle: Transporting science with entertainment
      # Display content from the `content/post/` folder
      filters:
        folders:
          - collections_personal_scienceslam
      count: 100
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: masonry

---