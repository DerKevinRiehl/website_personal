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
      text: <br><br><br><br><br><br><br><br>
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

  - block: collection
    id: section-1
    content:
      title: Science Slams
      subtitle: Transporting science with entertainment
      # Display content from the `content/post/` folder
      filters:
        folders:
          - collections_personal_scienceslam
      count: 100
      sort_by: 'Date'
      sort_ascending: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: masonry

---