---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: gallery-example-1.jpg

widget1:
  title: "Nuestro propósito"
  url: 'https://danimtb.github.io/info/'
  text: '<em>Mountain Signals</em> ofrece tecnología de medición y monitorización para entornos rurales o de difícil acceso.<br/>1. Sin necesidad de cobertura móvil ni internet<br/>2. Bajo impacto y mantenimiento.<br/>3. Transmisión de datos de largo alcance.<br/>4. Adaptable a cada necesidad.'
  image: logo-ms.png
widget2:
  title: "Proyecto PeakSense Valle de Benasque"
  url: 'https://danimtb.github.io/peaksense/'
  image: peaksense-benasque.jpg
  text: '<em>PeakSense Benasque</em> es un proyecto pionero que ofrece mediciones en tiempo real de los picos del valle de de Benasque gracias a la tecnología de Mountain Signals.'
widget3:
  title: "Nuestro blog"
  url: 'https://danimtb.github.io/blog/'
  image: blog.png
  text: 'Aquí enocntraras noticias y avances de nuestros proyectos, referencias a nuestra tecnología y dispositivos, así como casos de usos y aplicaciones.'
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
  url: https://danimtb.github.io/contact
  text: ¿Interesado en lo que hacemos? Cuéntanos más! >>
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
