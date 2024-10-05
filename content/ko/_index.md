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
        url: uploads/개발자정석찬이력서.pdf
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
      title: '💻 개발자 정석찬'
      subtitle: ''
      text: |-
        <aside>
        ⚙ TypeScript와 Nestjs를 주로 사용하는 백엔드 개발자입니다. TypeORM과 Swagger와 같은 라이브러리를 자주 사용하고, 최근 고속 처리를 위해 Redis를 프로젝트에 적용했습니다.
        </aside>

        <aside>
        🖥 풀스택 프로젝트를 진행해 본 경험으로 프론트엔드에 대한 이해가 뛰어나며, 다른 역할의 구성원들과 긍정적인 협업을 기대할 수 있습니다.
        </aside>

        <aside>
        🔃 애자일 프로세스의 진행에 능숙합니다! 짧은 기간 반복적인 스프린트와 스크럼에도 지치지 않는 체력을 가지고 있으며 구성원과의 원활한 소통이 가능합니다.
        </aside>

        <aside>
        🔥 주어진 일에 몰입하는 것을 잘하고 좋아합니다! 늘 어떻게 해야 최선의 결과를 도출할 수 있는지를 잠들기 전까지 고민하고 스스로 끝맺음을 할 수 있습니다.
        </aside>
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
