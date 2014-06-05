StarlingSwf-Egret
=================

<!DOCTYPE HTML>
<html>
<head>
    <meta charset="utf-8">
    <title>StarlingSwf</title>
    <meta name="viewport" content="width=device-width,initial-scale=1, minimum-scale=1, maximum-scale=1, user-scalable=no,target-densitydpi=device-dpi"/>
    <meta name="apple-mobile-web-app-capable" content="yes"/>

    <meta name="full-screen" content="true"/>
    <meta name="screen-orientation" content="portrait"/>
    <meta name="x5-fullscreen" content="true"/>
    <meta name="360-fullscreen" content="true"/>
    <base href="https://github.com/zmLiu/StarlingSwf-Egret/blob/master/"/>
    
</head>
<body>
<div style="display:inline-block;width:100%; height:100%;margin: 0 auto; background: black; position:relative;"
     id="gameDiv">
    <canvas id="gameCanvas" width="480" height="320" style="background-color: #000000"></canvas>
</div>
<script src="bin-debug/lib/egret_file_list.js"></script>
<script src="launcher/egret_loader.js"></script>
<script src="bin-debug/src/game_file_list.js"></script>

<script>
    egret_h5.preloadScript(egret_file_list, "bin-debug/lib/");
    egret_h5.preloadScript(game_file_list, "bin-debug/src/");
    egret_h5.startLoading();
</script>
</body>
</html>

