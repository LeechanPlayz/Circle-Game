# Circle-Game
<html>
<head>
<script src='http://code.jquery.com/jquery-latest.min.js'></script>

<script src='etc.js'></script>
<script src="circle-game.js"></script>
<script type='text/javascript'>
  $(document).ready(function() {
    if(isCanvasSupported())
      cg.init()
    else
      $(document.body).html("<style type='text/css'>p {text-align: center} body {padding: 10px}</style><p>You browser does not support HTML5, which is required to run this game.</p><p>I recommend Google Chrome <br /><a href='http://www.google.com/chrome'><img src='http://www.onlinecomputerfixes.com/wp-content/uploads/2010/10/google-chrome-logo.jpg' /></a></p>")
  })
</script>
<style type='text/css'>
body {
  margin: 0;
  padding: 0;
}
canvas {
  background-color: black;
}
</style>
</head>
<body>
<canvas></canvas>
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-37833732-3', 'auto');
  ga('send', 'pageview');

</script>
</body>
</html>
