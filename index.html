<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Veux-tu m'épouser? 💕</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Georgia', 'Playfair Display', serif;
            background: linear-gradient(135deg, #FFB6D9 0%, #FFC8E0 50%, #FFD6E8 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            position: relative;
        }

        /* Cœurs animés en arrière-plan */
        .heart-bg {
            position: fixed;
            font-size: 2em;
            opacity: 0.6;
            animation: float 3s ease-in-out infinite;
            pointer-events: none;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(5deg); }
        }

        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.95);
            padding: 60px 40px;
            border-radius: 30px;
            box-shadow: 0 20px 60px rgba(255, 105, 180, 0.3);
            max-width: 600px;
            position: relative;
            z-index: 10;
            animation: scaleIn 0.6s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        @keyframes scaleIn {
            from {
                transform: scale(0.8);
                opacity: 0;
            }
            to {
                transform: scale(1);
                opacity: 1;
            }
        }

        h1 {
            font-size: 3.5em;
            color: #FF1493;
            margin-bottom: 20px;
            letter-spacing: 2px;
            text-shadow: 2px 2px 4px rgba(255, 105, 180, 0.2);
            animation: pulse 2s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        .heart-icon {
            display: inline-block;
            margin: 0 10px;
            animation: heartBeat 1.3s ease-in-out infinite;
        }

        @keyframes heartBeat {
            0%, 100% { transform: scale(1); }
            25% { transform: scale(1.3); }
            50% { transform: scale(1); }
        }

        .subtitle {
            font-size: 1.3em;
            color: #FF69B4;
            margin-bottom: 40px;
            font-style: italic;
        }

        .buttons-container {
            display: flex;
            gap: 20px;
            justify-content: center;
            margin-top: 40px;
            position: relative;
            height: 60px;
        }

        button {
            padding: 15px 40px;
            font-size: 1.2em;
            font-weight: bold;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-family: 'Georgia', serif;
            position: relative;
            z-index: 20;
        }

        #yesBtn {
            background: linear-gradient(135deg, #FF1493, #FF69B4);
            color: white;
            box-shadow: 0 10px 25px rgba(255, 20, 147, 0.4);
        }

        #yesBtn:hover {
            transform: scale(1.1);
            box-shadow: 0 15px 35px rgba(255, 20, 147, 0.6);
        }

        #yesBtn:active {
            transform: scale(0.95);
        }

        #noBtn {
            background: linear-gradient(135deg, #FFB6D9, #FFC8E0);
            color: #FF1493;
            border: 2px solid #FF1493;
            box-shadow: 0 10px 25px rgba(255, 20, 147, 0.2);
        }

        #noBtn:hover {
            background: linear-gradient(135deg, #FFC8E0, #FFD6E8);
            transform: scale(1.05);
        }

        .success-message {
            display: none;
            text-align: center;
            animation: fadeIn 0.8s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .success-message h2 {
            font-size: 2.5em;
            color: #FF1493;
            margin-bottom: 20px;
        }

        .confetti {
            position: fixed;
            pointer-events: none;
        }

        .emoji-rain {
            position: fixed;
            font-size: 3em;
            animation: fall 3s linear forwards;
            pointer-events: none;
        }

        @keyframes fall {
            to {
                transform: translateY(100vh) rotate(360deg);
                opacity: 0;
            }
        }

        .decoration-line {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin: 20px 0;
            font-size: 1.5em;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>
            <span class="heart-icon">💕</span>
            Veux-tu m'épouser?
            <span class="heart-icon">💕</span>
        </h1>
        
        <div class="decoration-line">
            💑 💐 💍 💐 💑
        </div>

        <p class="subtitle">Je ne serais plus ton pire cauchemar</p>

        <div id="question-section">
            <div class="buttons-container">
                <button id="yesBtn">❤️ OUI ❤️</button>
                <button id="noBtn">Non</button>
            </div>
        </div>

        <div class="success-message" id="successMessage">
            <h2>🎉 Félicitations! 🎉</h2>
            <p style="font-size: 1.5em; color: #FF69B4; margin: 20px 0;">
                Nous sommes officiellement MARIÉS! 👰💒🤵
            </p>
            <div class="decoration-line">
                💕 💍 💕 💍 💕
            </div>
            <p style="font-size: 1.1em; color: #666; margin-top: 20px;">
                Je suis le plus heureux du monde! 
            </p>
        </div>
    </div>

    <script>
        const yesBtn = document.getElementById('yesBtn');
        const noBtn = document.getElementById('noBtn');
        const questionSection = document.getElementById('question-section');
        const successMessage = document.getElementById('successMessage');

        let noHoverCount = 0;

        // Bouton OUI - affiche le message de victoire
        yesBtn.addEventListener('click', function() {
            questionSection.style.display = 'none';
            successMessage.style.display = 'block';
            createConfetti();
            playSuccess();
        });

        // Bouton NON - s'échappe à chaque fois qu'on essaie de cliquer
        noBtn.addEventListener('mouseenter', function() {
            noHoverCount++;
            
            // Position aléatoire
            const randomX = Math.random() * (window.innerWidth - 150);
            const randomY = Math.random() * (window.innerHeight - 100);
            
            // Animation du bouton qui s'échappe
            noBtn.style.position = 'fixed';
            noBtn.style.left = randomX + 'px';
            noBtn.style.top = randomY + 'px';
            noBtn.style.transition = 'all 0.3s ease';
            
            // Après quelques tentatives, affiche un message amusant
            if (noHoverCount > 5) {
                const messages = [
                    "Oh non! 😄",
                    "Tu ne peux pas m'échapper! 💕",
                    "J'insiste! 🥰",
                    "Le destin nous unit! ✨",
                    "Dis oui! 🎀"
                ];
                const randomMsg = messages[Math.floor(Math.random() * messages.length)];
                yesBtn.textContent = randomMsg;
                
                setTimeout(() => {
                    yesBtn.textContent = '❤️ OUI ❤️';
                }, 2000);
            }
            
            // Crée des cœurs autour du bouton qui s'échappe
            createHearts();
        });

        // Fonction pour créer des confettis
        function createConfetti() {
            const colors = ['💕', '💍', '💐', '👰', '💒', '🤵', '💑'];
            
            for (let i = 0; i < 30; i++) {
                setTimeout(() => {
                    const emoji = colors[Math.floor(Math.random() * colors.length)];
                    const x = Math.random() * window.innerWidth;
                    const y = -50;
                    
                    const confetti = document.createElement('div');
                    confetti.className = 'emoji-rain';
                    confetti.textContent = emoji;
                    confetti.style.left = x + 'px';
                    confetti.style.top = y + 'px';
                    confetti.style.animationDuration = (2 + Math.random() * 2) + 's';
                    
                    document.body.appendChild(confetti);
                    
                    setTimeout(() => confetti.remove(), 4000);
                }, i * 100);
            }
        }

        // Fonction pour créer des cœurs volants
        function createHearts() {
            const heart = document.createElement('div');
            heart.className = 'heart-bg';
            heart.textContent = '💕';
            heart.style.left = Math.random() * window.innerWidth + 'px';
            heart.style.top = Math.random() * window.innerHeight + 'px';
            heart.style.animationDelay = Math.random() * 0.5 + 's';
            
            document.body.appendChild(heart);
            
            setTimeout(() => heart.remove(), 3000);
        }

        // Fonction pour jouer un succès (feedback auditif optionnel)
        function playSuccess() {
            // Son de succès avec l'API Web Audio (optionnel)
            try {
                const audioContext = new (window.AudioContext || window.webkitAudioContext)();
                const now = audioContext.currentTime;
                
                // Notes de succès en Do majeur
                const notes = [262, 330, 392, 523]; // Do, Mi, Sol, Do
                
                notes.forEach((freq, index) => {
                    const osc = audioContext.createOscillator();
                    const gain = audioContext.createGain();
                    
                    osc.frequency.value = freq;
                    osc.connect(gain);
                    gain.connect(audioContext.destination);
                    
                    gain.gain.setValueAtTime(0.3, now + index * 0.1);
                    gain.gain.exponentialRampToValueAtTime(0.01, now + index * 0.1 + 0.2);
                    
                    osc.start(now + index * 0.1);
                    osc.stop(now + index * 0.1 + 0.2);
                });
            } catch (e) {
                console.log('Son non disponible');
            }
        }

        // Crée des cœurs en arrière-plan au chargement
        window.addEventListener('load', function() {
            for (let i = 0; i < 10; i++) {
                setTimeout(() => {
                    const heart = document.createElement('div');
                    heart.className = 'heart-bg';
                    heart.textContent = '💕';
                    heart.style.left = Math.random() * window.innerWidth + 'px';
                    heart.style.top = Math.random() * window.innerHeight + 'px';
                    heart.style.animationDelay = Math.random() * 2 + 's';
                    document.body.appendChild(heart);
                }, i * 200);
            }
        });
    </script>
</body>
</html>
