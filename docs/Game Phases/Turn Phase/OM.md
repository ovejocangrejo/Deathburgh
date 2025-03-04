---
title: Outnumbered Mechanic
layout: default
parent: Turn Phase
nav_order: 1
---
<link rel="stylesheet" href="style.css">
<h1 style="text-align: center;"><b> Outnumbered Mechanic</b></h1>

At some point in the game, a player may end with more miniatures on the battlefield than the opponent, that usually happens when they start smashing their heads. A player may also run out of miniatures to activate much earlier than the opponent.

● If it’s your turn to activate a miniature, and you have no miniatures left to activate
while your opponent still has two or more miniatures to activate, you may activate
one allied miniature and change its status to Aggressive Mode. This ends your turn.


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Otro Tooltip</title>
    <link rel="stylesheet" href="style.css">
    <style>
        /* Evita que el tooltip salga de la pantalla en pantallas pequeñas */
        @media screen and (max-width: 600px) {
            .tooltip {
                bottom: auto;
                top: 120%; /* Si la pantalla es pequeña, se coloca abajo */
                left: 50%;
                transform: translateX(-50%);
            }
            .tooltip::after {
                top: -10px;
                bottom: auto;
                border-color: transparent transparent rgba(0, 0, 0, 0.8) transparent;
            }
}
    </style>
</head>
<body>
<p> <span class="resaltado">(4) KEEP IN MIND!<span class="tooltip">This mechanic does NOT allow you to activate the miniature you just switched modes this turn. You must end the turn just after changing the miniature's status and then hand it over to your opponent, if it is still in Aggressive mode at the start of your next turn then it can be activated normally. This mechanic has noround restrictions, it can be performed as long as the condition that there are at least 2 opponent's miniatures still to be activated is met.
</span></span></p>
</body>
</html>


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