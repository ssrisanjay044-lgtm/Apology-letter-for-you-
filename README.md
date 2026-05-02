# Apology-letter-for-you-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Quiet Letter</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,400&family=Montserrat:wght@300;400&display=swap');

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: #0a0a0a;
            color: #e0dcd8;
            font-family: 'Montserrat', sans-serif;
            line-height: 1.6;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .container {
            width: 100%;
            max-width: 600px;
            padding: 40px 20px;
        }

        .section {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            margin-bottom: 80px;
        }

        .section h2 {
            font-family: 'Cormorant Garamond', serif;
            font-size: 2.5rem;
            font-weight: 400;
            margin-bottom: 20px;
            color: #ebdcd4;
            font-style: italic;
            border-left: 2px solid #d49b8a;
            padding-left: 15px;
        }

        .main-title {
            font-family: 'Cormorant Garamond', serif;
            font-size: 4rem;
            font-weight: 400;
            color: #ebdcd4;
        }

        .main-title span {
            color: #d49b8a;
            font-style: italic;
        }

        .subtitle {
            font-size: 0.9rem;
            color: #8a8580;
            margin-top: 15px;
            font-style: italic;
        }

        .main-text {
            font-size: 1.1rem;
            margin-top: 20px;
            color: #ebdcd4;
        }

        .accent-text {
            font-size: 0.8rem;
            letter-spacing: 2px;
            color: #555;
            margin-bottom: 20px;
        }

        .heart {
            color: #d49b8a;
            font-size: 1.5rem;
            margin: 30px 0;
        }

        .image-placeholder {
            margin: 30px 0;
            color: #666;
            font-size: 0.9rem;
            font-style: italic;
        }

        /* Bowing Character Animation */
        .bow-figure-container {
            height: 120px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 30px 0;
        }

        .bow-figure {
            width: 60px;
            height: 80px;
            position: relative;
            transform-origin: bottom center;
            animation: bowMotion 4s ease-in-out infinite;
        }

        .head {
            width: 16px;
            height: 16px;
            background-color: #ebdcd4;
            border-radius: 50%;
            position: absolute;
            top: 0;
            left: 22px;
        }

        .torso {
            width: 4px;
            height: 35px;
            background-color: #ebdcd4;
            position: absolute;
            top: 18px;
            left: 28px;
            transform-origin: top center;
        }

        .legs {
            width: 12px;
            height: 30px;
            position: absolute;
            bottom: 0;
            left: 24px;
        }

        .legs::before, .legs::after {
            content: '';
            position: absolute;
            width: 2px;
            height: 30px;
            background-color: #ebdcd4;
        }

        .legs::before { left: 2px; }
        .legs::after { right: 2px; }

        @keyframes bowMotion {
            0%, 100% {
                transform: rotate(0deg);
            }
            30% {
                transform: rotate(35deg); /* Bends forward */
            }
            60% {
                transform: rotate(35deg); /* Holds the pose */
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="section">
            <div class="accent-text">A QUIET LETTER</div>
            <div class="main-title">For <span>You</span></div>
            <div class="heart">&#9825;</div>
            <p class="subtitle">I don't ask you to forgive me.<br>I only want you to know I'm sorry.</p>
        </div>

        <div class="section">
            <h2>"The same hands that held something so small and fragile — with so much care."</h2>
            <p class="subtitle">That’s exactly who you are. You protect the things that need protecting. You always have.</p>
            <div class="image-placeholder">[ Pure like a flower ]</div>
        </div>

        <div class="section">
            <h2>"Pure. Quiet. Unbothered by the world — yet somehow the most beautiful thing in it."</h2>
            <p class="subtitle">That’s what this flower reminded me of. That’s what you remind me of. I should have said it more.</p>
            <div class="image-placeholder">[ Our memories ]</div>
        </div>

        <div class="section">
            <h2>"Every small thing — a colour, a snack, a page — became a memory because you were there."</h2>
            <p class="subtitle">These are not just photos. These are proof that our ordinary days were never ordinary at all.</p>
        </div>

        <div class="section">
            <h2>"Some things stay. Even when everything else changes — some things just remain."</h2>
            <p class="subtitle">That’s what we are to me. Something that remains. Quietly, without needing to explain itself.</p>
        </div>

        <div class="section">
            <div class="accent-text">WITH ALL THE HUMILITY I HAVE</div>
            <h2>"These are memories of us. And I hold every one of them with both hands."</h2>
            <p class="subtitle">I don't take lightly what we shared. I never did. I'm sorry I didn't always show that.</p>
        </div>

        <div class="section">
            <div class="accent-text">I LOWER MY HEAD AND MEAN EVERY WORD</div>
            <h2>"If I could bow to show you how sorry I am — I would. Without hesitation."</h2>
            
            <div class="bow-figure-container">
                <div class="bow-figure">
                    <div class="head"></div>
                    <div class="torso"></div>
                    <div class="legs"></div>
                </div>
            </div>

            <p class="main-text">I spoke from anger, and I hurt you.<br>If I could go back, I would choose kindness every time.</p>
            <p class="subtitle">No excuses. Just the truth — and genuine regret for every word that landed wrong.</p>
        </div>

        <div class="section">
            <p class="main-text">I respect you more than I showed in that moment,<br>and I'm truly sorry for that.</p>
            <p class="subtitle">You deserved patience and care. I forgot that in the worst moment. I hate that I did.</p>
            <br><br>
            <p class="main-text">I'm not here to ask for anything...<br>just to acknowledge my mistake and give you the space you deserve.</p>
            <p class="subtitle">No pressure. No expectation. Only this honest, quiet sorry.</p>
        </div>
    </div>

</body>
</html>

