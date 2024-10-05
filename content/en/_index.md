---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 이력서 보기
        url: uploads/정석찬이력서_JK.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: profile_bg.png
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: '💻 Junior Developer Jung Seokchan'
      subtitle: ''
      text: |-
        ⚙ I am a backend developer primarily using TypeScript and NestJS. I frequently work with libraries like TypeORM and Swagger, and I have recently implemented Redis in my projects for faster processing.

        🖥 With experience in full-stack projects, I have a solid understanding of frontend development and can collaborate effectively with members in other roles, fostering positive teamwork.

        🔃 I am proficient in managing Agile processes! I have the stamina to handle short, repetitive sprints and scrums without fatigue, and I can communicate smoothly with team members.

        🔥 I am highly focused and passionate about immersing myself in the tasks given! I constantly think about how to achieve the best results, even before going to sleep, and I am capable of finishing tasks independently.
    design:
      columns: '1'

  - block: collection
    id: Profile_Projects
    content:
      title: Profile Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 3

  - block: collection
    id: Certificate
    content:
      title: Certificate
      filters:
        folders:
          - certificate
    design:
      view: article-grid
      columns: 2

  # - block: slides
  #   content:
  #     slides:

  #     - title: <span style="font-size:70%">Development</span>
  #       content: <span style="font-size:70%">TypeScript, Node.js 기반 프레임워크를 활용한 백엔드, 풀스택 개발<span style="font-size:70%">
  #       align: center
  #       background:
  #         image:
  #           filename: Development.jpg
  #           filters:
  #             brightness: 0.4
  #         position: center
  #         color: '#000'

  #     - title: <span style="font-size:70%">Developer</span>
  #       content: <span style="font-size:70%">컴퓨터 공학 계열 학사 전공 및 정보처리기사, SQLD 취득</span>
  #       align: center
  #       background:
  #         image:
  #           filename: Developer.jpg
  #           filters:
  #             brightness: 0.4
  #         position: center
  #         color: '#000'

  #     - title: <span style="font-size:70%">Metaverse</span>
  #       content: <span style="font-size:70%">Web 3.0과 메타버스에 대한 깊은 관심</span>
  #       align: center
  #       background:
  #         image:
  #           filename: metaverse.jpg
  #           filters:
  #             brightness: 0.4
  #         position: center
  #         color: '#000'

  #   design:
  #     # Slide height is automatic unless you force a specific height (e.g. '400px')
  #     slide_height: '350px'
  #     slide_width: '100px'
  #     is_fullscreen: false
  #     # Automatically transition through slides?
  #     loop: true
  #     # Duration of transition between slides (in ms)
  #     interval: 3000

---
