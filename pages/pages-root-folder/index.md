---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
sidebar: left
header:
  image_fullwidth: banners/ImranMilkyWay.png


widget1:
  title: "Vision"
  url: '/about/'
  image: magneticsquare.jpg
  text: "Read about the NSF-Simons SkAI Institute's vision for the future of AI in astronomy"
widget2:
  title: "People"
  url: '/people/'
  text: 'Meet the team behind the NSF-Simons SkAI Institute'
  image: Hancock_small.jpg
widget3:
  title: "News & Events"
  url: '/news/'
  image: supernova.png
  text: 'Recent news and upcoming events at the NSF-Simons SkAI Institute'

#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://docs.google.com/forms/d/e/1FAIpQLSfiTXFlutPyQgVWfjiZ6pFtIs2j1BwtkRNJiTvaT_n0KXBAPQ/viewform?usp=sf_link
  text: Sign up for email updates on new SkAI developments ›
  style: success

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
