---
title: Game Mode
layout: default
has_children: true
nav_order: 11
---
<link rel="stylesheet" href="style.css">

<h1 style="text-align: center;"> Domination</h1>

Domination is Deathburgh’s twist on Tug of War. This game runs for 4 Rounds.

 Both players start at opposite ends of the balance track at position 0 of 7 slots.
- As you earn Victory Points—through Control Points or other
means—you advance along the track toward the centre.
- If you land on a spot already occupied by your opponent, you take over that
space.


At the end of Round 4, the player who has advanced the furthest along the track wins.
However, if a player fills the entire track before the end of the game, they achieve an instant
victory, ending the game immediately



















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








