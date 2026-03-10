<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Messi – Struggle & Achievements</title>

<style>
    body {
        margin: 0;
        font-family: "Poppins", sans-serif;
        background: #eef7ff;
        overflow-x: hidden;
    }

    /* Floating animation */
    @keyframes float {
        0% { transform: translateY(0); }
        50% { transform: translateY(-15px); }
        100% { transform: translateY(0); }
    }

    /* Sky background */
    .sky {
        background: linear-gradient(#8fd0ff, #e6f6ff);
        width: 100%;
        height: 100vh;
        position: relative;
        overflow: hidden;
    }

    /* Floating clouds */
    .cloud {
        position: absolute;
        width: 220px;
        opacity: 0.9;
        animation: float 6s ease-in-out infinite;
    }
    .cloud1 { top: 80px; left: 100px; }
    .cloud2 { top: 150px; right: 150px; animation-duration: 8s; }

    /* Title */
    .title {
        position: absolute;
        top: 40px;
        width: 100%;
        text-align: center;
        font-size: 50px;
        color: #003566;
        font-weight: 800;
        text-shadow: 2px 2px 5px white;
        animation: float 5s infinite;
    }

    /* Content section */
    .content {
        padding: 60px 10%;
        background: white;
        margin-top: -40px;
        border-radius: 40px 40px 0 0;
        position: relative;
        z-index: 10;
        box-shadow: 0 -10px 30px rgba(0,0,0,0.15);
    }

    h2 {
        color: #003566;
        font-size: 32px;
        margin-bottom: 10px;
        font-weight: 700;
    }

    p {
        font-size: 18px;
        line-height: 1.7;
        color: #333;
    }

    /* Floating footballs */
    .ball {
        position: absolute;
        width: 70px;
        animation: float 6s infinite;
        opacity: 0.8;
    }
    .ball1 { top: 180px; left: 40px; }
    .ball2 { top: 250px; right: 60px; animation-duration: 7s; }

</style>
</head>
<body>

<div class="sky">
    <h1 class="title">The Journey of Messi ⚽</h1>

    <!-- Clouds -->
    <img src="https://i.imgur.com/V7bWJ8m.png" class="cloud cloud1">
    <img src="https://i.imgur.com/V7bWJ8m.png" class="cloud cloud2">

    <!-- Floating balls -->
    <img src="https://i.imgur.com/7kMWQ7Z.png" class="ball ball1">
    <img src="https://i.imgur.com/7kMWQ7Z.png" class="ball ball2">
</div>

<div class="content">

    <h2>🌪 Messi’s Struggles</h2>
    <p>
        As a child, :contentReference[oaicite:2]{index=2} was diagnosed with a growth hormone deficiency. 
        Many clubs rejected him because they didn’t want to pay for his treatment. 
        His family struggled financially, believing his dream might never come true.
    </p>
    <p>
        But Messi never gave up. He worked harder than anyone, trained every single day, 
        and stayed focused even when others thought he was “too small” to succeed in football.
    </p>

    <h2>🏆 Messi’s Achievements</h2>
    <p>
        Despite the challenges, Messi became one of the greatest players in football history.  
        He has won **multiple Ballon d’Or awards**, created countless records, and inspired millions worldwide.  
        With his unbelievable dribbling, vision, and leadership, he led **Argentina to win the FIFA World Cup 2022**, 
        completing one of the greatest comeback stories in sports.
    </p>
    <p>
        Messi’s journey proves that **hard work and passion can overcome any struggle**.
        His success is not just about trophies—it’s about resilience, dedication, and heart.
    </p>

</div>

</body>
</html>
