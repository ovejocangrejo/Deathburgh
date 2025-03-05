---
title: Charge Action
layout: default
parent: Movement Actions
nav_order: 2
---
<link rel="stylesheet" href="style.css">

<h1 style="text-align: center;">Charge Action</h1>

Charge is a special type of movement action that lets your miniature
engage an opponent in combat. It consists of two parts: the movement towards the target and the mandatory Attack action that follows.

Here’s how it works:

### 1) **Declare** which miniature is going to perform **the Charge** and which
opponent’s miniature is going to be the valid target.

- a) A valid target must be in the line of sight.

- b) A valid target must be in the most straight path possible to be the target of the Charge. The most straight path = minimum distance Charge require to be done by the Attacker to be base to base with the target.

- c) This distance has to be possible to perform before to declare a Charge over the target.




### 2) **Charge Distance:** roll **1D6”** and add it to your movement profile for just this movement.

- a) If you don’t reach, your Charge is failed and your miniature will
move the Charge Distance following the most straight path and
will change their mode to Defensive.

- b) If your Charge Distance is equal or over the most straight path,
    move your miniature inch by inch, meaning that one inch of
    your move implies one inch closer to the target, following your
    desire path and end your movement base to base with the
    opponent.
- c) You are allowed to move and pivot around the opponent miniature, but you must end up being base to base with the
    opponent’s miniature.
  

### 3) **Attack Action**: Roll your Aggressive dice to attack the target of your
charge.

- a) Bonus: If the opponent’s miniature is more than 2” from the charging miniature, the Attacker gets an instant 6! to their roll which removes one of the attack dice they have to roll for that attack.

➢ If an obstacle interrupts a straight-line charge, you can always go around it or try to go
through it.

➢ Every charge is always followed by an Attack that will start a Melee Combat.

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