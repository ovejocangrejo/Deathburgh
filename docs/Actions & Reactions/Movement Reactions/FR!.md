---
title: Flee Reaction
layout: default
parent: Movement Reactions
nav_order: 3
---
<link rel="stylesheet" href="style.css">

<h1 style="text-align: center;">Flee Reaction</h1>

Flee is a reaction movement that a miniature in Aggressive Mode can perform when being Charged. To initiate a Flee, wait until your opponent declares a Charge against your miniature.

The fleeing miniature moves away but cannot end inside a Control Point or in base-to-base contact with an opponent’s miniature. It remains in Aggressive Mode while fleeing. If the fleeing miniature is attacked this turn, it must perform a mandatory Dodge reaction. At the end of the opponent's turn, its mode switches to Defensive.

Here’s how it works:

<body>
<ol>
    <li><b>Declare the Flee</b>
        <ol>The attacker declares a Charge, rolls 1D6", and moves the miniature—it goes first, moving up to half its charge distance (rounding up).
        </ol>
        <ol>If it is enough distance to be in base to base contact with your model, you will not be able to perform a Flee reaction.
        </ol>
    <li><b>Roll 2D6"</b>
        <ol>Now, the defender rolls 2D6" to determine how far your miniature can move away miniature.
        </ol>
        <ol>Move it and stay put in Aggressive Mode at the end of their move.
</ol>
        <ol><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Otro Tooltip</title>
    <link rel="stylesheet" href="../style.css"> <!-- Llamamos al CSS existente -->
</head>
<body>
    <p><p class= "right-text">> <span class="resaltado">(5) KEEP IN MIND!<span class="tooltip">Moving away means that you may not end this move any closer to the charging miniature than you started it. </span></span></p></p>
</body>
</html>
</ol>
    <li><b>Charging</b>
        <ol>The opponent miniature will now make the rest of its move:
        </ol>
            <ol><b> - Got you!</b> If an opponent miniature ends their Charge base-to-base with your fleeing miniature, a combat will begin, both in Aggressive mode and your miniature will only able to perform a mandatory Dodge reaction to the incoming attacks.
        </ol>
            <ol> <b>- Redirecting Charge:</b>If opponent charging miniature not reaches your fleeing miniature: Opponent miniature can move the other half of their movement until be base-to-base to another enemy miniature or stay put.If there is any of your miniature in reach, the opponent may move the other half or their movement until be base-to-base with your other miniature. Then, will perform their action attack against your other miniature, and a Melee Combat will start.
        </ol>
        <ol> <b>If you don't reach anybody</b>, your Charge is failed and your miniature will move the Charge Distance following the most straight path and will change their mode to Defensive.
</ol>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Otro Tooltip</title>
    <link rel="stylesheet" href="../style.css"> <!-- Llamamos al CSS existente -->
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
    <p><p class= "right-text">> <span class="resaltado">(6) KEEP IN MIND!<span class="tooltip"> Since one of your miniatures has already reacted to the charging movement by fleeing, your second miniature would have to wait for the opponent's charging miniature's mandatory attack action to react to that attack, either with a reaction attack, dodging or casting a skill. For example, if the miniature within range of the second half of the charge move has a ranged weapon, he would not be able to use the Stand and Shoot reaction because Stand and Shoot is an exclusive reaction to a charge move action. He could, however, react to the attack that follows the charge by dodging. Or if it were a melee model, with a reaction attack, or if it had a skill, casting the skill as a reaction to the attack action.
</span></span></p> </p>
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