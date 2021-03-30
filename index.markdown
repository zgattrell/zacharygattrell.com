---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: 
title: Zachary Gattrell
order: 1
---
<html>
<head>
    <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-KWGX20HFV7"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-KWGX20HFV7');
</script>
    <title>Zachary Gattrell</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous" />
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf" crossorigin="anonymous"></script>
    <link href="/assets/css/index.css" rel="stylesheet" />
    <link rel="stylesheet" type="text/css" href="//fonts.googleapis.com/css?family=Homemade+Apple" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class = "navbar-brand p-3 vl-right" href="">Zachary Gattrell</a>
  </nav>  
  <div>
    <script src="https://threejs.org/build/three.js"></script>
    <script>
        const scene = new THREE.Scene();
        scene.background = new THREE.Color( 0x727272 );
        const camera = new THREE.PerspectiveCamera( 75, window.innerWidth / window.innerHeight, 0.1, 1000 );
        const renderer = new THREE.WebGLRenderer();
        renderer.setSize( window.innerWidth, window.innerHeight - 200 );
        document.body.appendChild( renderer.domElement );

        const BoxGeometry = new THREE.BoxGeometry();
        const boxWireFrame = new THREE.WireframeGeometry(BoxGeometry);
        const boxLine = new THREE.LineSegments(boxWireFrame);
        const cube = new THREE.Mesh( BoxGeometry);
        scene.add( cube );

        camera.position.z = 5;

        const geometry2 = new THREE.SphereGeometry( 2, 2, 2 );

        const wireframe = new THREE.WireframeGeometry( geometry2 );

        const line = new THREE.LineSegments( wireframe );
        line.material.depthTest = false;
        line.material.opacity = 0.25;
        line.material.transparent = true;

        scene.add( line );

        function animate() {
	        requestAnimationFrame( animate );
	        renderer.render( scene, camera );
          line.rotation.x -= 0.01;
          line.rotation.y -= 0.01;
          cube.rotation.x += 0.01;
          cube.rotation.y += 0.01;
        }
  animate();
    </script>
  </div>
  <div class="container py-5 text-center">
    <h2>WEB DEVELOPMENT | UX DESIGN | DATA ANALYTICS</h2>
    <br/>
    <p>I am a Junior Management Information Systems Student at the University of Alabama hoping to graduate in the Spring of 2023 with a Masters of Science in Management Information Systems. I have a passion for Front End Web Development, UX Design, and Data Analytics, specifically Natural Language Processing. </p>
  </div>
 <!-- <div class="container-fluid bg-secondary full-width">
    <div class="container py-5 text-center">
    <h2>Personal Projects:</h2>
    <br/>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum</p>
    </div>
  </div>
  -->
    <div class="container py-5 text-center">
    <h2>Connect With Me</h2>
    <br/>
      <a href="https://www.linkedin.com/in/zachary-gattrell/" class="fa fa-linkedin"></a>
      <a href="https://github.com/zgattrell" class="fa fa-github"></a>
      <a href="#" class="fa fa-twitter"></a>
  </div>
</body>
</html>
