# programmer shub
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Nature Theme Webpage</title>
<style>
    body {
        margin: 0;
        overflow: hidden;
        font-family: Arial, sans-serif;
    }

    /* Background Sky */
    .sky {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: linear-gradient(#87CEEB, #e0f7ff);
        z-index: -3;
    }

    /* Mountains */
    .mountains {
        position: fixed;
        bottom: 150px;
        width: 100%;
        height: 250px;
        background: url('https://i.imgur.com/8s5CqNI.png') repeat-x;
        background-size: contain;
        z-index: -2;
    }

    /* Trees */
    .trees {
        position: fixed;
        bottom: 60px;
        width: 100%;
        height: 200px;
        background: url('https://i.imgur.com/hf5o0QF.png') repeat-x;
        background-size: contain;
        z-index: -1;
    }

    /* Flowing Water */
    .water {
        position: fixed;
        bottom: 0;
        width: 100%;
        height: 80px;
        background: url('https://i.imgur.com/dcQO6V1.png') repeat-x;
        background-size: cover;
        animation: flow 5s linear infinite;
    }

    @keyframes flow {
        0% { background-position: 0 0; }
        100% { background-position: -800px 0; }
    }

    /* Title */
    .title {
        position: absolute;
        top: 30px;
        width: 100%;
        text-align: center;
        font-size: 40px;
        color: #0b3d0b;
        font-weight: bold;
        text-shadow: 2px 2px 5px white;
    }
</style>
</head>
<body>

<div class="sky"></div>
<div class="mountains"></div>
<div class="trees"></div>
<div class="water"></div>

<h1 class="title">Welcome to My Nature Webpage 🌿</h1>

</body>
</html>
