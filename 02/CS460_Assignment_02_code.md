<html>
  <head>
    <meta content="text/html;charset=utf-8" http-equiv="Content-Type">
    <meta content="utf-8" http-equiv="encoding">
    <title>CS460 Assignment 2</title>
    <style>
      body {
        background-color: black;
        color: white; /* font color */
        font-family: sans-serif;
        margin: 0;
        padding: 0;
        height: 100%;
        overflow: hidden !important;
      }

      #logo {
        position: absolute;
        right: 10px;
        top: 10px;
      }
    </style>
    
    <script type="text/javascript" src="http://get.goXTK.com/xtk_edge.js"></script>

    <script type="text/javascript">

    window.onload = function() {

      // this gets called when the site is ready

      // create a new scene and renderer
      r = new X.renderer3D();
      r.init();

      for (var i=0; i<7; i++) {

        var c = new X.cube();
        
        c.center = [25*i, 0, 0];
      
        r.add(c);

      }

      for (var i=0; i<7; i++) {

        var c = new X.cube();
        
        c.center = [25*i, 25, 0];
      
        r.add(c);

      }

      for (var i=0; i<7; i++) {

        var c = new X.cube();
        
        c.center = [25*i, 75, 0];
      
        r.add(c);

      }
      
      for (var i=0; i<1; i++) {

        var c = new X.cube();
        
        c.center = [50, -50, 0];
      
        r.add(c);

      }

      for (var i=0; i<1; i++) {

        var c = new X.cube();
        
        c.center = [75, -50, 0];
      
        r.add(c);

      }

      for (var i=0; i<1; i++) {

        var c = new X.cube();
        
        c.center = [100, -50, 0];
      
        r.add(c);

      }

      for (var i=0; i<1; i++) {

        var c = new X.cube();
        
        c.center = [25, -25, 0];
      
        r.add(c);

      }

      for (var i=0; i<1; i++) {

        var c = new X.cube();
        
        c.center = [50, -25, 0];
      
        r.add(c);

      }

      for (var i=0; i<1; i++) {

        var c = new X.cube();
        
        c.center = [100, -25, 0];
      
        r.add(c);

      }

      for (var i=0; i<1; i++) {

        var c = new X.cube();
        
        c.center = [125, -25, 0];
      
        r.add(c);

      }

      setInterval(function() {
        var c2 = new X.cube();
        c2.color = [1, 0, 0]
        c2.center = [25, 50, 0];
      
        r.add(c2);
      }, 1000);

      setInterval(function() {
        var c2 = new X.cube();
        c2.color = [1, 0, 0]
        c2.center = [50, 50, 0];
      
        r.add(c2);
      }, 1000);

      setInterval(function() {
        var c2 = new X.cube();
        c2.color = [1, 0, 0]
        c2.center = [100, 50, 0];
      
        r.add(c2);
      }, 1000);

      setInterval(function() {
        var c2 = new X.cube();
        c2.color = [1, 0, 0]
        c2.center = [125, 50, 0];
      
        r.add(c2);
      }, 1000);



      for (var i=0; i<6; i++) {

        var c = new X.cube();
        
        c.center = [0, 25*i, 0];
      
        r.add(c);

      }

      for (var i=0; i<6; i++) {

        var c = new X.cube();
        
        c.center = [150, 25*i, 0];
      
        r.add(c);

      }

      for (var i=0; i<1; i++) {

        var c = new X.cube();
        
        c.center = [75, 50, 0];
      
        r.add(c);

      }

      for (var i=0; i<2; i++) {

        var c = new X.cube();
        
        c.center = [25*i, 100, 0];
      
        r.add(c);

      }

      for (var i=0; i<1; i++) {

        var c = new X.cube();
        
        c.center = [125, 100, 0];
      
        r.add(c);

      }

      

      // var c2 = new X.cube();
      // c2.center = [75, 50, 0]
      // r.add(c2);


      // var c = new X.cube();
      // r.add(c); 
     
      // set camera further away!
      r.camera.position = [0, 0, 500];

      // render everything!
      r.render();

    };

    </script>
  </head>
  <body>
    <h1>CS460 Assignment 2</h1>
    <div id="logo"><img style="height:60px" src="gfx/cs460.png"></div>
  </body>
</html>
