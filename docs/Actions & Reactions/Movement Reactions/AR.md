---
title: Ambush Reaction
layout: default
parent: Movement Reactions
nav_order: 4
---
<link rel="stylesheet" href="style.css">

<h1 style="text-align: center;">Ambush reaction</h1>

Ambush is a reaction movement triggered when an opponent's miniature takes a move action that doesn’t target you but gets too close to your position or attempts to retreat from combat
prematurely. There is only chance to perform an Ambush if none of your miniature has already declared a reaction against that move action.

If an opponent’s miniature moves more than 2" away from your miniature or within 2" of your miniature (in Aggressive Mode) during its move action, you can spring an Ambush—but only if
your miniature hasn’t been activated yet and isn’t already locked in combat with another opponent’s miniature. If you fail the Ambush you must stay put and change your mode to Defensive.

**➔ Ambush is like a turn swamp.** Until the end of the opponent reaction, If you have been Ambush, your opponent will have the First Word and your miniature will be performing reactions, this means that once the Ambush is over, you are in your turn again and can perform actions as usual.


Here’s how it works:

<body>
<ol>
    <li><b>Declare the Ambush to your opponent</b>
        <ol>The opponent must pause their movement and will give the First Word to you.
</ol>    
    <li><b>Roll one D6"</b>
        <ol>To Ambush, move your miniature up to 1D6” toward the opponent’s miniature following the most straightforward route possible. If you end up base-to-base with the target, go ahead and make an Attack action, If not, stay put, the Ambush is over and you will change to Defensive.
        </ol>
        <ol>If your miniature is equipped with a Ranged Weapon, it can perform a Ranged Attack, but you need to move at least <b>4” away along the shortest path from the target</b>, so you will need at least get a +2 in your roll.
</ol>
    <li><b>If the opponent’s miniature survives</b>
        <ol> If the oponnent's miniatures survives the combat, you will return the First Word and they can continue their turn with their move action as planned.
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
    <p><p class= "right-text">> <span class="resaltado">(7) KEEP IN MIND!<span class="tooltip"> You are not able to react against that move action that trigger the Ambush with any
other miniature because you have already been performing a reaction with the Ambush.
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
