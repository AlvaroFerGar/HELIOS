# HELIOS
A simple three.js visualization of the nearest stars to our sun

This is the final work I made for a class project. Basically, it's a web page that loads a 3D navigable map of the nearest stars to the Sun. The goal wasn't to create the most precise visualization. I simply want to test the potential of three.js and improve my skills with javascript (and obviously to pass the subject).

# Some references

* The web is programmed in javascript inside HTML files.
* The main library used to create the map is [three.js](https://threejs.org/). I take from it a bunch of code and some .png sprites.
* The data of the stars is from the [HYG Database](http://www.astronexus.com/hyg)
* The implementation of the function that converts the color index of a star to a RGB color(ColorIndex2RGB) is inspired in [the idea of melhosseiny](https://stackoverflow.com/questions/21977786/star-b-v-color-index-to-apparent-rgb-color), a Stackoverflow user.
* Finally, I want to give credit to Michael Chang the creator of [100,000 stars](http://stars.chromeexperiments.com/) that was the main inspiration to make this project.  

# How to navigate?
You can navigate using the "Orbit Controls". The left mouse allows you to orbit, the right mouse to pan and the mousewheel to zoom. Each of the stars on the map can be selected with a double-click. In doing so, an informative text and red lines of positional reference will appear next to it. The upper button bar is used to change the display settings:

   'Inicio'/Start: return to the presentation page.
      
   'Transporte a Sol'/ Travel to the Sun: teleportation to the initial pose.
      
   'Transporte a Estrella'/ Travel to a star: teleportation to the selected star.
      
   'Limpia'/ Clean: clean the info of the star.
      
   'Datos Estrella'/ Star data: configuration of the star data that is shown.
      
   'Constelaciones'/ Constellations: to highlight a selected constellation.
      
   'Buscador de Estrellas'/ Search star: highlight the selected star and teleportation to its pose.
      
# And...that's all folks!

As I'm spanish the code is comented in my language. If you are interested in have more information about my code you only have to ask. I'll be pleased to help you.

Thanks for reading!!!
