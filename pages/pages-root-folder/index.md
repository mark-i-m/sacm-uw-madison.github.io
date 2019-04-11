---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_home.jpg
widget1:
  title: "Social Acitivities"
  url: '/Events/'
  image: widget-1-302x182.jpg
  text: '<ul><li>TGIF and Boardgames</li><li>Bornfire with Smores</li><li>Picnics</li><li>Coffee Club</li></ul>'
widget2:
  title: "Prospective and New Students"
  url: '/Events/'
  image: widget-github-303x182.jpg
  text: '<ul><li><a target="_blank" href="http://sacm.cs.wisc.edu/welcome/"><strong><u>Prospective Student Welcome Weekend</u></strong></a></li><li><a target="_blank" href="http://sacm.cs.wisc.edu/orientation/"><strong><u>Graduate Student Orientation</u></strong></a></li><li><a target="_blank" href="http://sacm.cs.wisc.edu/transition/"><strong><u>Graduate Student Transition Information</u></strong></a></li></ul>'
widget3:
  title: "Miscellaneous"
  url: '/Events/'
  image: widget-1-302x182.jpg
  text: '<ul><li>gradchat Mail List FAQ</li><li>Nameplate Generator</li><li>COW Award</li></ul>'
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
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
