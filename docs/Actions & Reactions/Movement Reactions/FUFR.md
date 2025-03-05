---
title: Flee Under Fire Reaction
layout: default
parent: Movement Reactions
nav_order: 5
---
<link rel="stylesheet" href="style.css">

<h1 style="text-align: center;">Flee under fire</h1>

This is a movement reaction to a Ranged Attack. When an opponent’s miniature declares a ranged attack against a miniature in Aggressive Mode, the Defender, may respond running and looking for a place to hide.

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
    <p><p class= "right-text">> <span class="resaltado">(8) KEEP IN MIND!<span class="tooltip"> Since a miniature can only make one move per activation, you can't Flee under Fire! if
you are being ambushed! Because in order for your opponent to Ambush, you must first perform a Move
action!
</span></span></p> </p>
</body>
</html> 

Here’s how it works:


<body>
<ol>
    <li><b>Apply Attack Bonuses</b>
        <ol>Any bonuses the Attacker has for the ranged attack are applied before the Defender’s response.
</ol>    
    <li><b>Declare response</b>
        <ol><b>1st</b> The Defender rolls <b>2D6”</b> and moves the rolled distance as a reaction.
        </ol>
        <ol><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Otro Tooltip</title>
    <link rel="stylesheet" href="../style.css"> <!-- Llamamos al CSS existente -->
</head>
<body>
    <p><p class= "right-text">> <span class="resaltado">(9) KEEP IN MIND!<span class="tooltip">You can not end the movement base to base with the Attacker miniature.</span></span></p></p>
</body>
</html>
        </ol>
        <ol><b>2nd.</b> After moving, the Defender collects their bonuses.
        </ol>
        <ol><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Otro Tooltip</title>
    <link rel="stylesheet" href="../style.css"> <!-- Llamamos al CSS existente -->
</head>
<body>
    <p><p class= "right-text">> <span class="resaltado">(10) KEEP IN MIND!<span class="tooltip">This rule allows you to replace a miniature while fleeing. If the miniature ends its movement in a Take Cover! position or gains benefits from faction rules that provide bonuses to Dodge, these bonuses will apply to help dodge incoming ranged attacks once the moment.</span></span></p></p>
</body>
</html>
</ol>
    <ol><b>3rd.</b> Then, Attacker will roll their attack in Aggressive Mode and defender their dodge reaction in Aggressive Mode.
    </ol>
    <ol><b>4rd.</b> Determine Successes: Each Dodge ‘s successes by the Defender cancels one Attacker Success. Any remaining Attacker Successes will inflict wounds on the Defender.
    </ol>
        <li><b>End of Exchange</b>
        <ol> Both miniatures switch to Defensive Mode at the end of this exchange.
        </ol>

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