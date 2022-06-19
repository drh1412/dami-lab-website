---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title:  Welcome to the group
      content: In one sentence, we summarize our research interests and objectives to provide computational tools for neuroscience research driven by experimental data.
      align: center
      background:
        position: right
        color: '#999'
        brightness: 0.2
        media: danao.jpg
    - title: Develop automated tools ️
      content: The data collected by modern neuroscience shows explosive growth in both complexity and scale. The traditional data analysis methods will take a huge time or be powerless at all. Therefore, we need to develop fully automated and intelligent algorithms for specific problems to create a complete automation process of data collection, storage, visualization, automatic processing and statistical analysis.
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: zhihu.jpg
    - title: Interpret data
      content: The work of the brain depends on the complex connection and synergy between a large number of neurons, but the data we record in the brain are all isolated neurons. It is not direct to find the law of interaction between these neurons. Therefore, I will develop some machine learning methods to mine hidden features in data, or statistical models to interpret data.
      align: right
      background:
        position: center
        color: '#555'
        brightness: 0.5
        media: danao2.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
