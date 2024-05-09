---
title: My page
type: landing

sections:
  - block: hero
    content:
      title: About us
      #image:
        # Reference an image in your `assets/media/` folder
        # filename: icon.png
      text: |-
        A little about us, our history and our area of research

        Developing safe and beneficial AI systems is a mission that involves curious minds from diverse disciplines. We invite you to discover more about LabUAI.

  - block: features
    content:
      title: What we do
      text: >
        The Uncertainty in Artificial Intelligence (LABUAI) Laboratory is dedicated to the exploration and advancement of cutting-edge techniques within the realm of AI. Our primary focus lies in delving into the uncertainties inherent in artificial intelligence, and our research spans various applications with a strong connection to the intricate world of AI.
        Our endeavors encompass the development of innovative approaches to Machine Learning and Image Processing, with a particular emphasis on navigating the uncertainties that AI presents. Our main research topics are:<br><br>
      items:
        - name: Artificial Intelligence
          description: Artificial Intelligence (AI) is a field of computer science that seeks to develop systems capable of performing tasks that traditionally require human intelligence. These systems use algorithms and models to learn from data, recognize patterns and solve problems autonomously.
          icon: ia
          icon_pack: custom
        - name: Machine Learning
          description: Branch of artificial intelligence based on the idea that systems can learn from data and make decisions with minimal human intervention. The objective is to enable machines to perform autonomous tasks, such as pattern recognition and result prediction, with applications in data analysis, voice recognition and optimization of industrial processes.
          icon: ml
          icon_pack: custom
        - name: Lore ipsum
          description: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
          icon: ml
          icon_pack: custom

  - block: slider
    content:
      slides:
        - title:
          content:
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: DCC_view.png
              filters:
                brightness: 0.7
            position: right
            color: '#666'

    design:
      columns: '2'
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

---
