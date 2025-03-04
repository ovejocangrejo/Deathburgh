---
title: Miniature profile
layout: default
parent: Factions and Miniatures
nav_order: 1
---
<link rel="stylesheet" href="style.css">

<h1 style="text-align: center;"> Miniature Profile </h1>

From the basic troop to a Leader, all miniatures come with a set of attributes and values used to perform movement, action, reactions or skills. This is an example of a Miniature Profile in Deathburgh:

Melee Follower  of the Royal Rotten Society: Mathieu 'Blackmouth' du Marais

<img style="display: block; margin: 0 auto;" src="imagenes\progile.png" alt="Miniature Profile" width="500" height="300">

**Follower:** During your turn, after this miniature’s activation, instead of giving the turn to your opponent,
you may activate an allied miniature with the Follower keyword that has not yet activated this round to
perform an additional turn.

<h1 style="text-align: center;"> Movement (M) </h1>

The Movement represents how far your miniature may move on its turn, measured in inches.
Your miniature can only move once per turn - either action movement or reaction movement-,
and only if the miniature is in Aggressive Mode -it has not been activated yet-. Your miniature may rotate and change direction when performing a movement without penalty.

<h1 style="text-align: center;"> Aggressiveness (A/A+)</h1>

**The first number (A)** of this attribute shows the maximum damage a miniature in Aggressive
Mode can deal. It determines the number of dice you can roll for actions or reactions—the
higher the Power, the more dice you get to roll.**The second number (A+)** is the target number your rolled dice must meet or exceed for a successful action or reaction while in Aggressive Mode. The value is shown with a ‘+’ sign.

<h1 style="text-align: center;"> Defence (D/D+)</h1>

This attribute represents how strong the miniature is while in Defensive Mode. **The first value (D)** is the dice, it represents the number of dice you can roll to perform in a reaction. The higher this value is, the bigger the number of dice you can roll. **The second value (D+)** represents the score your rolled dice must equal or exceed in order for the miniature to achieve a successful reaction while in Defensive Mode.

The value is shown with a ‘+’ sign.

<h1 style="text-align: center;"> Wounds (W)</h1>

This is the number of wounds a miniature can endure before collapsing. Each wound is caused
by a successful attack, or ‘Hit.’

**Wounded:** When a model suffers a wound, place a die next to it with the total number of
wounds inflicted on the model.

**Wasted Mode:** In Deathburgh, your companions do not die as such. They simply remain
sentient remains. When a miniature’s wounds reach 0, it’s considered a miniature in a
“Wasted” Mode—lay it down and **the owner will collect 1 Soul’s Dice.**

You can not place a miniature on a Wasted miniature. Keep all tokens attached to the miniature until is removed from the game at the end of the round.

Remove all miniature in Wasted Mode at the end of the round.

If that model somehow recovers its wounds during the course of a round, it will stand on its feet in **Defensive Mode** as if said wounds had not occurred.

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