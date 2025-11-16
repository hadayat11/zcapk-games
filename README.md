<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZCAPK Games - Free Car Racing Games</title>
    <meta name="description" content="Play free car racing games on ZCAPK. No download required. HTML5 games for mobile and PC.">
    
    <!-- AdMob Ads -->
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-7565219102608844" crossorigin="anonymous"></script>
    
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #1a1a2e, #16213e);
            color: white;
            line-height: 1.6;
        }
        .container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
        
        /* Header */
        .header { 
            background: rgba(0,0,0,0.9); 
            padding: 1rem 0; 
            position: fixed; 
            width: 100%; 
            top: 0; 
            z-index: 1000;
        }
        .logo { 
            font-size: 2rem; 
            font-weight: bold; 
            color: #ffd700; 
            text-decoration: none; 
        }
        
        /* Hero Section */
        .hero { 
            background: rgba(0,0,0,0.7); 
            padding: 120px 0 80px; 
            text-align: center; 
            margin-top: 60px;
        }
        .hero h1 { font-size: 2.5rem; margin-bottom: 1rem; color: #ffd700; }
        .btn { 
            background: #ffd700; 
            color: black; 
            padding: 12px 30px; 
            text-decoration: none; 
            border-radius: 25px; 
            font-weight: bold;
            display: inline-block;
            margin-top: 1rem;
        }
        
        /* Games Grid */
        .games { padding: 3rem 0; }
        .games-grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); 
            gap: 1.5rem; 
            margin: 2rem 0;
        }
        .game-card { 
            background: rgba(255,255,255,0.1); 
            padding: 1.5rem; 
            border-radius: 10px; 
            text-align: center;
            border: 2px solid transparent;
            transition: all 0.3s ease;
        }
        .game-card:hover { 
            border-color: #ffd700; 
            transform: translateY(-5px);
        }
        .game-card h3 { color: #ffd700; margin: 1rem 0; }
        .play-btn { 
            background: #4CAF50; 
            color: white; 
            border: none; 
            padding: 10px 20px; 
            border-radius: 20px; 
            cursor: pointer;
            margin-top: 1rem;
        }
        
        /* Ads */
        .ad-banner { 
            background: #2d3748; 
            height: 90px; 
            display: flex; 
            align-items: center; 
            justify-content: center; 
            margin: 2rem 0;
            border-radius: 5px;
        }
        
        /* Footer */
        .footer { 
            background: rgba(0,0,0,0.9); 
            padding: 2rem 0; 
            text-align: center; 
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header class="header">
        <div class="container">
            <a href="#" class="logo">ZCAPK GAMES</a>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>🎮 FREE CAR RACING GAMES</h1>
            <p>Play Online | No Download | Mobile Friendly</p>
            <a href="#games" class="btn">START PLAYING</a>
        </div>
    </section>

    <!-- Ad Banner -->
    <div class="container">
        <div class="ad-banner">
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-7565219102608844"
                 data-ad-slot="1292543169"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
        </div>
    </div>

    <section class="games" id="games">
        <div class="container">
            <h2 style="text-align: center; color: #ffd700; font-size: 2rem;">🚗 OUR GAMES</h2>
            
            <div class="games-grid">
                <div class="game-card">
                    <div style="font-size: 3rem;">🚗</div>
                    <h3>Infinite Car Race</h3>
                    <p>Endless racing adventure</p>
                    <button class="play-btn" onclick="loadGame()">PLAY NOW</button>
                </div>
                
                <div class="game-card">
                    <div style="font-size: 3rem;">🏁</div>
                    <h3>Speed Racer</h3>
                    <p>High-speed challenges</p>
                    <button class="play-btn" onclick="loadGame()">PLAY NOW</button>
                </div>
                
                <div class="game-card">
                    <div style="font-size: 3rem;">🚓</div>
                    <h3>Police Chase</h3>
                    <p>Exciting car chase</p>
                    <button class="play-btn" onclick="loadGame()">PLAY NOW</button>
                </div>
            </div>
            
            <!-- Game Display -->
            <div id="game-display" style="background: rgba(0,0,0,0.5); padding: 2rem; border-radius: 10px; text-align: center; min-height: 200px;">
                <h3 style="color: #ffd700;">SELECT A GAME TO PLAY</h3>
                <p>Click any game above to start playing</p>
            </div>
        </div>
    </section>

    <!-- Middle Ad -->
    <div class="container">
        <div class="ad-banner">
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-format="fluid"
                 data-ad-layout-key="-gw-3+1f-3d+2z"
                 data-ad-client="ca-pub-7565219102608844"
                 data-ad-slot="1292543169"></ins>
            <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
        </div>
    </div>

    <footer class="footer">
        <div class="container">
            <h3>ZCAPK GAMES</h3>
            <p>Free Online Gaming Platform</p>
            <p style="margin-top: 1rem; color: #666;">&copy; 2024 ZCAPK Games. All rights reserved.</p>
        </div>
    </footer>

    <script>
        function loadGame() {
            const display = document.getElementById('game-display');
            display.innerHTML = `
                <h3 style="color: #ffd700;">🎮 GAME LOADING...</h3>
                <div style="background: #2d3748; height: 300px; border-radius: 10px; display: flex; align-items: center; justify-content: center; margin: 1rem 0;">
                    <div style="text-align: center;">
                        <div style="font-size: 4rem;">🚗</div>
                        <p>Car Racing Game Would Load Here</p>
                        <p style="color: #ffd700; margin-top: 1rem;">Your actual game would be embedded here</p>
                    </div>
                </div>
                <button class="play-btn" onclick="startGame()" style="background: #ff6b6b;">LAUNCH GAME</button>
            `;
            display.scrollIntoView({behavior: 'smooth'});
        }
        
        function startGame() {
            alert('🎯 Game would start here!\n\nIn real website, your actual HTML5 game would launch.');
        }
        
        // Initialize ads
        (adsbygoogle = window.adsbygoogle || []).push({});
    </script>
</body>
</html>
