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
		var unityInstance = UnityLoader.instantiate("unityContainer", "Build/Site.json", {onProgress: UnityProgress}); 
    </script>
	<style>
	.holder {
		background-color: gray;
		height: 100%;
		width: 100%;
		left: 0;
		top: 0;
		overflow: hidden;
		position: fixed;
	}
	button {
		display: block; 
		margin-left: auto; 
		margin-right: auto; 
		margin-top: 12.5%; 
		margin-bottom: auto; 
		width: 50%; 
		height: 50%; 
		background-color: red; 
		color: yellow; 
		float: center;
		font-size: 144px;
	}
	</style>
  </head>
  <body>
    <div class="webgl-content">
      <div id="unityContainer" style="width: 0px; height: 0px"></div>
    </div>
	<div class="holder">
		<button onclick="unityInstance.SetFullscreen(1)"><b>Play</b></button>
	</div>
  </body>
</html>
