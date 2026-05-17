<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forgive Me, My Mommy Manisha 💕</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;700&family=Poppins:wght@300;400;600&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 50%, #fecfef 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow-x: hidden;
            position: relative;
        }
        
        body::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><radialGradient id="a" cx="50%" cy="50%"><stop offset="0%" stop-color="%23ffffff" stop-opacity="0.1"/><stop offset="100%" stop-color="%23ffffff" stop-opacity="0"/></radialGradient></defs><circle cx="20" cy="20" r="2" fill="url(%23a)"><animate attributeName="cy" values="20;80;20" dur="3s" repeatCount="indefinite"/></circle><circle cx="50" cy="50" r="1.5" fill="url(%23a)"><animate attributeName="cy" values="50;90;50" dur="4s" repeatCount="indefinite"/></circle><circle cx="80" cy="10" r="2.5" fill="url(%23a)"><animate attributeName="cy" values="10;70;10" dur="2.5s" repeatCount="indefinite"/></circle></svg>') repeat;
            animation: sparkle 20s linear infinite;
            pointer-events: none;
        }
        
        @keyframes sparkle {
            0% { transform: translateY(0) rotate(0deg); }
            100% { transform: translateY(-100px) rotate(360deg); }
        }
        
        .container {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 30px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.2);
            padding: 60px 40px;
            max-width: 600px;
            text-align: center;
            position: relative;
            animation: fadeInUp 1s ease-out;
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 3.5em;
            color: #e91e63;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
        
        .heart {
            font-size: 4em;
            color: #ff4081;
            animation: heartbeat 1.5s ease-in-out infinite;
            margin-bottom: 20px;
        }
        
        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }
        
        .message {
            font-size: 1.3em;
            line-height: 1.8;
            color: #333;
            margin-bottom: 30px;
            font-weight: 300;
        }
        
        .apology {
            background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
            padding: 30px;
            border-radius: 20px;
            margin: 30px 0;
            border-left: 5px solid #ff6b9d;
            font-style: italic;
        }
        
        .name-highlight {
            font-family: 'Dancing Script', cursive;
            font-size: 1.5em;
            color: #e91e63;
            font-weight: 700;
        }
        
        .promise {
            font-size: 1.2em;
            color: #4a148c;
            font-weight: 600;
            margin-top: 20px;
        }
        
        .btn-forgive {
            background: linear-gradient(135deg, #ff6b9d 0%, #c44569 100%);
            color: white;
            border: none;
            padding: 15px 40px;
            font-size: 1.2em;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-top: 30px;
        }
        
        .btn-forgive:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(255, 107, 157, 0.4);
        }
        
        .hearts {
            position: absolute;
            top: -20px;
            right: -20px;
            font-size: 2em;
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-10px) rotate(10deg); }
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 40px 30px;
                margin: 20px;
            }
            
            h1 {
                font-size: 2.8em;
            }
            
            .heart {
                font-size: 3em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="hearts">💖💕💗</div>
        <h1>My Dearest Mommy Manisha</h1>
        <div class="heart">💝</div>
        
        <p class="message">My love, my everything... I know I hurt you by replying late. It breaks my heart to think I made you wait, even for a moment. You are the light of my world, the beat in my chest, and I can't bear the thought of you feeling unloved or forgotten.</p>
        
        <div class="apology">
            <p>I got stuck in some work, my Mommy. It wasn't intentional – I swear on our love. Every second without talking to you feels like an eternity. You are my safe haven, my sweet escape, and I promise to cherish every message, every call, every moment with you like the treasure it is.</p>
        </div>
        
        <p class="promise">Please forgive your baby. Let me hold you close again, whisper how much I adore you, and make up for every lost second with endless kisses and hugs. I love you more than words can say, forever and always. 💕</p>
        
        <button class="btn-forgive" onclick="forgiveMe()">I Forgive You, My Love 💋</button>
    </div>

    <script>
        function forgiveMe() {
            confettiEffect();
            document.querySelector('.btn-forgive').innerHTML = 'Thank You, Mommy! I Love You Forever ❤️';
            document.querySelector('.btn-forgive').style.background = 'linear-gradient(135deg, #4caf50 0%, #45a049 100%)';
        }
        
        function confettiEffect() {
            // Simple confetti burst
            for (let i = 0; i < 50; i++) {
                setTimeout(() => {
                    const confetti = document.createElement('div');
                    confetti.innerHTML = ['💖', '💕', '💗', '🌹', '✨'][Math.floor(Math.random() * 5)];
                    confetti.style.position = 'fixed';
                    confetti.style.left = Math.random() * 100 + 'vw';
                    confetti.style.top = '-10px';
                    confetti.style.fontSize = '20px';
                    confetti.style.pointerEvents = 'none';
                    confetti.style.zIndex = '1000';
                    confetti.style.animation = 'float 3s ease-out forwards';
                    document.body.appendChild(confetti);
                    
                    setTimeout(() => confetti.remove(), 3000);
                }, i * 20);
            }
        }
    </script>
</body>
</html># sorrymommy
