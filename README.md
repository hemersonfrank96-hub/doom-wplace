<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Doom 50x50</title>
<style>
body {
    margin:0;
    background:black;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}
canvas {
    image-rendering: pixelated;
}
</style>
<script src="https://js-dos.com/6.22/current/js-dos.js"></script>
</head>

<body>

<div id="doom"></div>

<script>
Dos(document.getElementById("doom"), {
    wdosboxUrl: "https://js-dos.com/6.22/current/wdosbox.js"
}).run("https://js-dos.com/cdn/upload/DOOM-@evilution.zip");
</script>

</body>
</html>
