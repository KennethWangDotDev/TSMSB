---
title: Regarding Timing, Parrying, and the Law of Tempos
layout: blog-post
root: blog
nav-blog: true
date: 2017-01-30
collection:
  - blog

thumbnail: tempo.jpg
author: Kenneth

description: Timing, or the precise instant in which an ability is executed, is one of the most important things to understand to succeed in this game.
---

*Timing*, or the precise instant in which an ability is executed, is one of the most important things to understand to succeed in this game. The timing of an attack in relation to your opponent's position and the frame/hitbox data of your attack determines whether the attack will succeed or fail.

It is also important to note that Rivals of Aether is a read-based game. It is impossible to win solely by relying on your reaction time. For example, let's say that your reaction speed is 0.23ms, which is above average. This converts to 14 frames at 60fps. The majority of moves in this game have active hitboxes well below frame 14, and you will not be able to counter it by reaction. I stress this point because it logically means that each player must *read* the timing of their opponent's moves. To take this line of thinking one step further, it is extremely beneficial to utilize timing mixups to outplay your opponent.

In addition, there is one unique ability that every character has that has the potential to win over every single move -- the parry. Parrying is an extremely strong and beneficial mechanic. A successful parry will allow you to get one free hit on your opponent, and will swing the momentum to your favor. At high percents, a successful parry almost surely leads to a kill.

In this article, I will address how to play around parries, as well as when and why you should parry. To answer those two questions, it is important to deeply understand the underlying logistics and theory behind it all. To do so, I will now introduce a a helpful visual tool called the Tempo Diagram.

<h2 class="margin-top">The Tempo Diagram</h2>

<figure>
<img src="/assets/images/tempo-diagram.png">
<figcaption>On the top axis of the Tempo Diagram are the tempo timings. On the bottom axis, you have the raw frames. A Zero Tempo Parry and a First Tempo Parry are shown.</figcaption>
</figure>

The Tempo Diagram illustrates a duration of time of around 36 frames. On the top axis, I have labeled three "tempos". A tempo is a specific *timing*. The Tempo Diagram starts to take effect as soon as you approach your opponent and that **he must make a read** -- meaning that you can launch a hitbox that is in range to hit him within the next 14 frames. In that situation, your opponent must take one of the following actions: to attack you, to parry, or to evade the attack. In the interest of simplicity, a dodge roll is considered the same as a parry in this article.

Because the tempos are primarily based on parry frames, it is important to know parry frame data as well. There are **2 frames of startup** in a parry. The parry is then **active from frames 3 to 10**. The player is then unable to act until **frame 31 (endlag)**. Dodge roll frame data varies between each character, but is similar to parry frame data.

* **Zero Tempo**: If you strike your opponent immediately without any timing mixups, you are striking in Zero Tempo. Zero Tempo Attacks are the fastest, but are also most the commonly parried. If your opponent parries immediately -- a Zero Tempo Parry -- then the attack will fail and your opponent will come out ahead in the exchange. Any attack whose hitbox comes out within frame 8 is considered a Zero Tempo Attack.

* **First Tempo**: If you predict that your opponent will do a Zero Tempo Parry, you can instead opt to use a slower attack. When you do this, you are attacking in First Tempo. A First Tempo Attack starts at frame 8 of the Tempo Diagram, as soon as the active parry for a Zero Tempo parry ends. A First Tempo Attack will lose to a First Tempo Parry. In addition, it will lose to any attacks whose hitbox comes out in Zero Tempo. Attacks that come out from frame 9 to 16 are considered First Tempo Attacks -- mostly smash attacks and slow aerials. In addition, simply waiting a bit before you use a fast attack works too.

* **Second Tempo**. Second Tempo starts 16 frames after your initial approach. It is the slowest tempo, but also the most flexible one. A Second Tempo move can be a read-attack to win over a First Tempo Parry, but it can also be a reaction based on what your opponent does in Zero Tempo. For example, if your opponent leaves your area of influence in Zero Tempo, you can react to that and decide to not attack at all. A Second Tempo Attack loses to both Zero and First Tempo Attacks, but beats Zero and First Tempo Parries. The most common cases of Second Tempo Attacks are semi-charged smashes, and delayed strikes.  For delayed strikes, it is recommended to dashdance *out* of your opponent's area of influence until the timing of your attack. This has the possibility to evade an attack and gains the opportunity to counterattack.


<h2 class="margin-top">The Law of Tempo</h2>

The Law of Tempo states three rules:
1. A parry will beat out an attack of the same tempo.
2. A parry will lose to an attack of one or two tempos higher.
3. An attack of a lower tempo will beat out an attack of a higher tempo*

<small>\**(with the exception of dash dancing to evade)*</small>

The Law of Tempo will help us answer two hard, but incredibly important questions:

**Because a Zero Tempo Attack will always lose to the mere possibility of a Zero Tempo Parry, isn't it safer to always attack in a higher tempo?**

**Answer:** No. Rule 3 of the Law of Tempo states that an attack of lower tempo will beat out attacks of a higher tempo. Higher Tempo attacks are riskier than lower tempo attacks. By always attacking in a higher tempo, you are playing suboptimally.


**Should I never parry as a read because it loses to attacks of higher tempo?**

**Answer:** No. If you never parry as a read, you are telling your opponents "It's always safe to attack me in Zero Tempo." Zero Tempo is the most optimal tempo since it is the fastest does not lose to attacks of other tempos. You must take the risk of parrying as reads because it injects fear of the parry in the opponent. Even if you never parry as a read again, your opponent will still be on the lookout for it.


It is vital to understand the rock-paper-scissors nature to tempos. A Zero Tempo Parry beats a Zero Tempo Attack. A Zero Tempo Attack beats a First Tempo Attack. A First Tempo Attack beats a Zero Tempo Parry. There is no "unconditonally best option" or "rule of thumb".


<h2 class="margin-top">Tempo Strategy</h2>

Against every opponent, you should have a different tempo strategy. Most players will default to attacking and parrying at a specific tempo. As soon as the game starts, you must begin reading their tempo.

Ask yourself: *"In how many and what ways is my opponent beginning his combos against me? What tempo attacks does he use in what situations? Does he ever parry as a read, and if so, at what timing?"*

Keep a look out for what specific attack tempo when both you and your opponent are grounded on the stage, what attack tempo when he is above you, and what attack tempo when he is below you. Get a grasp of how his attack patterns, and how he reacts to your attacks. Once you have read his tempo, use the rules of the Law of Tempo and counter it.

It should be noted that it is possible for a player to make a conscious effort to change his tempo mid-game. Most players do not have the required practice and skill to do this, but at high level this is not uncommon.


<h2 class="margin-top">Other Notes</h2>

To make this article as complete as possible, I want to mention some other notes and caveats.

* **Clarifying parries**. All written instances of parries in this article are "read-parries" where the hitbox will come out sooner than your rection time. If there is a move that you can react to and parry with no possible timing mixups, then you should *absolutely* parry it. Examples are: Zetterburn's fireball, Kragg's Down B spike 3, Etalus icicle, Etalus Down B.
* **Regarding jab-checks**. Most jab1 hits in this game do not trigger parry stun, so a jab of a tempo will not completely lose to a parry of the same tempo. However, your opponent will gain invincibility frames so he still comes out ahead.
* **Same tempo attacks**. If two attacks are of the same tempo, the one that wins is either the faster one, or the one with a better hitbox. Positioning decides whether it is the latter or the former.



<hr>

Thank you for reading, and I hope you learned something from this! :)

