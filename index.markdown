---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: 
title: Zachary Gattrell
order: 1
---
<html>
<head>
    <title>Zachary Gattrell</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf" crossorigin="anonymous"></script>
    <link href="{{site.baseurl}}/assets/css/index.css" rel="stylesheet">
    <script type="text/javascript">
  function JavaBlink() {
     var blinks = document.getElementsByClassName('blink-text');
     for (var i = blinks.length - 1; i >= 0; i--) {
        var s = blinks[i];
        s.style.visibility = (s.style.visibility === 'visible') ? 'hidden' : 'visible';
        var colors = ['#ff0000', '#00ff00', '#0000ff'];
        var random_color = colors[Math.floor(Math.random() * colors.length)];
        s.style.color = random_color;
     }
     window.setTimeout(JavaBlink, 100);
  }
  if (document.addEventListener) document.addEventListener("DOMContentLoaded", JavaBlink, false);
  else if (window.addEventListener) window.addEventListener("load", JavaBlink, false);
  else if (window.attachEvent) window.attachEvent("onload", JavaBlink);
  else window.onload = JavaBlink;

 function playAudio(){
  const audio = document.querySelector("audio");
  audio.volume = 0.2;
  audio.play();
  }


</script>
</head>
<body onclick="playAudio()">
    <div class="container py-5 text-center mx-auto">
        <marquee class="blink-text" behavior="alternate"><img src="/assets/img/face.JPG" width="70px">ZACHAYR GATTRELL<img src="/assets/img/face.JPG" width="70px"></marquee>
        <marquee class="blink-text" behavior="alternate" scrollamount="14" ><img src="/assets/img/face.JPG" width="70px">ZACHAYR GATTRELL<img src="/assets/img/face.JPG" width="30px"></marquee>
        <marquee class="blink-text" behavior="alternate" scrollamount="12"><img src="/assets/img/face.JPG" width="70px">ZACHAYR GATTREL<img src="/assets/img/face.JPG" width="70px">L</marquee>
        <h1 class="big-text blink-text">Zachary Gattrell</h1>
        <marquee class="blink-text" behavior="alternate" scrollamount="4"><img src="/assets/img/face.JPG" width="70px">ZACHAYR GATTRELL<img src="/assets/img/face.JPG" width="70px"></marquee>
        <marquee  class="blink-text" behavior="alternate" scrollamount="55"><img src="/assets/img/face.JPG" width="50px">ZACHAYR GATTRELL<img src="/assets/img/face.JPG" width="70px"></marquee>
        <marquee class="blink-text" behavior="alternate" scrollamount="32"><img src="/assets/img/face.JPG" width="70px">ZACHAYR GATTRELL<img src="/assets/img/face.JPG" width="70px"></marquee>

    </div>
    <audio autoplay>
      <source src="https://incompetech.com/music/royalty-free/mp3-royaltyfree/Death%20and%20Axes.mp3">
    </audio>
</body>
</html>
