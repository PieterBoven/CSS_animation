# CSS_animation

file:///home/pieter/Desktop/becode_projects/Learning_Environtment/css_animations/anime.html

<!DOCTYPE html>

<html>

  <head>

    <style>
    @keyframes  anime {
0% {background-color: white;}
25% {background-color: blue;}
50% {background-color: red;}
75% {background-color: black;}
100% {background-color: white;}
}

html {
position: relative;
background-color: white;
animation-name: anime;
animation-duration: 6s;
animation-delay: 2s;
animation-iteration-count: infinite;
}

img {
  width: 200px;
  height: 250px;
  background-color: inherit;
  animation-name: mouse;
  animation-duration: 10s;
  animation-duration: infinite;
  position: relative;
}

@keyframes mouse {
0% {top: 0px; left: 0px; background-color: white;}
25% {top: 0px; left: 500px; background-color: blue;}
50% {top: 500px; left: 500px; background-color: red;}
75% {top: 500px; left: 0px; background-color: black;}
100% {top: 0px; left: 0px; background-color: white;}
animation-iteration-count: infinite;
}
    </style>

  </head>

  <body>

    <img src="Biker Mouse.jpg">

  </body>

</html>
