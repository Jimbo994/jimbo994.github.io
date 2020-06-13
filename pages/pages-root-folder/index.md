---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: banner.jpg
widget1:
  title: "Radio Astronomoy"
  url: '/highlights/'
  image: fig_project3b_s.png
  text: 'An active field of research in astronomy deals with recognising rare features in data streams from space obervations in (almost) real time. This challenging task arises from the massive imaging surveys of the sky carried our at a wide range of wavelengths (optical, radio, X-ray). The purpose is no longer just to find objects that are there all or most of the time, but also to spot so-called ‘transient’ objects that appear only fleetingly.'
widget2:
  title: "Liquid Chromatography"
  url: '/highlights/'
  image: fig_project2.png
  text:'Two-dimensional liquid chromatography (2DLC) is a powerful technique to separate and detect trace molecular compounds in complex samples such as food contaminants, industrial production streams, urine, or blood, to name but a few examples. However, successful implementation requires time-consuming experiment-specific optimization of many parameters. Machine learning can aid with data-analysis and the acceleration of optimization.'  
widget3:
  title: "Gravitational Waves"
  url: '/highlights/'
  image: fig_project1.png
  text: 'The breakthrough discovery of the first gravitational wave signal in September 2015 (Nobel Prize 2017) has opened a new window to the Universe. Analyses of the signal waveforms during the initial inspiral, merger and final ringdown phase provide crucial information about the properties of superheavy stellar objects.'
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
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
#permalink: /index.html
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
