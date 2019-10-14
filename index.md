<!DOCTYPE html>
<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity WebGL Player | ΦΚΤ Pong</title>
    <link rel="shortcut icon" href="TemplateData/favicon.ico">
    <link rel="stylesheet" href="TemplateData/style.css">
    <script src="TemplateData/UnityProgress.js"></script>
    <script src="Build/UnityLoader.js"></script>
    <script>
      function Start() {
		var unityInstance = UnityLoader.instantiate("unityContainer", "Build/Site.json", {onProgress: UnityProgress}); 
		unityInstance.SetFullscreen(1);
	  }
    </script>
  </head>
  <body>
    <div class="webgl-content">
      <div id="unityContainer" style="width: 1920px; height: 1080px"></div>
    </div>
  </body>
</html>
