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
    - title: 👋 Thanks for checking us out!
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: group-image-ac.png
    - title: Game, Create, and Learn ☕️
      content: 'Share your knowledge with the group and explore exciting new topics together!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: 4opt.png
    - title: Want in?
      content: 'Schedule for a interview!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: discord
        icon_pack: fas
        text: Join Us
        url: https://discord.gg/EbDaQK4xbz
---
