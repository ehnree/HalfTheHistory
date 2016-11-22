---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: hth.png
widget1:
  title: "Belinda\'s Petition"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: belinda.jpg
  text: 'Belinda, born in Africa, kidnapped, and brought to America, petitioned the Massachusetts Legislature in 1783 for her Freedom. <em>Belindas petition</em> conveys the inhumanity of the institution of slavery and the mental and physical confinement that a slave experiences.'
widget2:
  title: "Half the History"
  url: 'https://www.youtube.com/watch?v=RRKeeW-55W8'
  text: '<em>Half the History </em> highlights under-told stories of women in American history. Become part of the movement to include equality in history books, sites, historic preservation, and media. Be inspired by one of the women in this video or on the HTH website or Facebook page. Produced by Five Sisters Productions (www.fivesisters.com) with Tufts Production Team.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="images/hth.png" width="302" height="182" alt=""/></a>'
widget3:
  title: "Download Theme"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. Grab the <a href="https://github.com/Phlow/feeling-responsive/tree/bare-bones-version">Bare-Bones-Version</a> for a fresh start or learn how to use it with the <a href="https://github.com/Phlow/feeling-responsive/tree/gh-pages">education-version</a> with sample posts and images. Then tell me via Twitter <a href="http://twitter.com/phlow">@phlow</a>.'
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/RRKeeW-55W8" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
