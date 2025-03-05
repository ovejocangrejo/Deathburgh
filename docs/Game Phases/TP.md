---
title: Turn Phase
layout: default
parent: Game Phases
has children: True
nav_order: 3
---
<link rel="stylesheet" href="style.css">
<h1 style="text-align: center;"><b> Turn Phase</b></h1>

Once roles are set, the Attacker kicks off the Turn Phase. In this phase, players take turns activating their miniatures, one at a time, until all miniatures have had a go.

During the Turn Phase, miniatures can perform actions, while opponent miniatures can respond with reactions to keep things interesting.

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Otro Tooltip</title>
    <link rel="stylesheet" href="../style.css"> <!-- Llamamos al CSS existente -->
</head>
<body>
<p> <span class="resaltado">(3) KEEP IN MIND!<span class="tooltip">Whenever you have the opportunity to activate a miniature because it is in Aggressive mode at the start of your turn you must activate it. This indicates that you cannot spend the turn with miniatures still in Aggressive mode, unless it is because of the Outnumbered rule.
</span></span></p>
</body>
</html>

&nbsp;

The player with the highest result gets to choose to be the attacker or the defender. The player with the lowest result gets one Soul’s Dice.

- In the first Round of the game, the Defender gets to choose the deployment zone and will deploy their miniatures first.

- The Attacker deploys the miniatures in second place but initiates the Turn Phase by activating a miniature in first place. The Turn Phase will continue as usual afterwards.

At the beginning of following Rounds, players will repeat this roll to determine the Attacker and the Defender. Remember the compensation Soul’s Dice for being the Defender.

The Attacker will initiate the Turn Phase by activating a miniature in first place. The Turn Phase will continue as usual afterwards.

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Go Back Button</title>
    <style>
        #goBackBtn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            padding: 10px 20px;
            background-color:rgb(255, 0, 200);
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        #goBackBtn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
       <button id="goBackBtn" onclick="window.scrollTo(0, 0);">Back to Top</button>
</body>