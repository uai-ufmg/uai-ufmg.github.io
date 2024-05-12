---
title: Projects
date: 2022-10-24

type: landing

sections:
  - block: markdown
    content:
      title: Projects
      text: >
        <p>Explore the innovative projects that are contributing to future of technology. From practical solutions to visionary concepts, each project reflects our laboratory's commitment to technical excellence and the relentless pursuit of significant advances. In our laboratory, excellence is measured by projects that challenge the boundaries of what is possible. Each initiative reflects not only the advanced application of artificial intelligence and other contemporary technology topics, but also an unwavering commitment to solving complex problems.
        
  - block: slider
    content:
      slides:
      - title: '<a href="{{< ref "/projects/researchProjects" >}}">Research Projects</a>'
        content:
        align: center
        background:
          image:
            filename: bg_projects.png
            filters:
              brightness: 0.7
          position: right
      - title: '[**R&D**](https://www.example.com)'
        content:
        align: center
        background:
          image:
            filename: bg_projects.png
            filters:
              brightness: 0.7
          position: right
      - title: '[**Knowledge &<br>Training**](https://www.example.com)'
        content:
        align: center
        background:
          image:
            filename: bg_projects.png
            filters:
              brightness: 0.7
          position: right

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---