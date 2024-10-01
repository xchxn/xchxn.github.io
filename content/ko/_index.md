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
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: wave.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: '💻 개발자 정석찬은?'
      subtitle: ''
      text: |-
        저는 매 순간 더 나은 결과를 위해 노력하는 개발자입니다. 백엔드 개발자로 취업하기를 희망하지만 풀스택 개발을 즐겨합니다.
        
        제가 관심있는 분야에서 웹개발을 하는 것이 즐겁습니다.

        채용을 원하신다면 언제든지 연락주세요😄
    design:
      columns: '1'

  - block: collection
    id: Projects
    content:
      title: My Project
      filters:
        folders:
          - projects
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
      columns: 3

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
