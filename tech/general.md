---
title: General Tech
description: 
published: true
date: 2025-02-04T14:40:34.735Z
tags: 
editor: markdown
dateCreated: 2024-02-09T12:40:46.013Z
---

>This page is unfinished{.is-warning}

Automata has a lot of idiosyncrasies in it's mechanics and how they interact. Because of that there are a lot of things we can exploit and use to our advantage in a speedrun. To better understand the underlying mechanisms also refer to [Game Behaviour](/lookUp/behaviour). This page is about all the tech that is neither clearly [Combat](/tech/combat) or [Movement](/tech/movement) tech in itself, but can require or augment them.
# Slow-mo
Slow-mo is a very escential technic that has a wide range of uses. It helps in combat and with movement, as well as some other aplications. It is used to **slow down** most aspects of the **game world** excluding the player.
### Execution
**Hold** the **Pod Program** Button to charge your Pod Program, during the first few seconds of crage up the world will be slowed. To refresh the slow-mo when it runs out **cancel** the program and immediatly **charge it again**.

The easiest way to cancel a Pod Program is by briefly using Pod Fire.
It can also be canceled by letting go of the button while SD is held, or during the start of a dash.
A Pod Program is also not discharged after fully self destructing.
### Requirements
A **chargeable Pod Program** has to be equiped on the active Pod (first aquired during the Marx 1 fight) and it has to be **off cooldown**.
The majority of all Pod Programs are chargeable, exceptions are: Wire
*(editor note: check for more)*
### Additional Notes
- The Quick access Menu cannot be used during Slow-mo, redering you temporarily unable to use Healing items or switch weapon sets while Slow-mo is held
- Toggleing fashlight to taunt is still possible during Slow-mo
- Holding Slow-mo during an aerial combo makes the player unable to glide with the Pod or Podspin
- Slow-mo can be performed simultaniously with holding SD

# Self Destruct
If there is one universally useful and powerful tool at our disposal, the **Self Destruct** function or **SD** for short would be a top contender. Playing casually some people might use it to blow up 2B's skirt, but then most likely never touch it again.
Due to it's properties however it is a very versitile ability that enables a wide variaty of tech.
### Requirements
SD becomes available **immediatly after completing the Prologue** of the game. (actually even before the start-up menu sequence)
Since Self Destruct is used so much and being able to press it for very short durations at a time is very important, it is **highly recommended to rebind** it to a button that is comfortable to press.
Most Runners will have it bound to either **Bumper** (more commonly L1 / LB) or the **D-Pad**.
### Applications
- When tapped SD will cancel any action the chracter is currently in and return them to an idle state. 
	It can therefor also be used to asure an idle player state or comming to a dead stop at any time.
- Letting go of SD when tapping or previously holding it will instantly kill all momentum the character has except for falling momentum.
- When the player already has momentum when starting to hold SD (eg. from a Plunge) the momentum will be maintained until the button is released.
- Repeatedly tapping SD while falling prevents the character from going into a belly flop animation and additionally negates all fall damage.
- When canceling an attack with SD the combo will still be advanced, so it can skip to later attacks in any combo.
- Canceling most combo attacks before their conclusion will reset the attack enableing the player to repeatedly use it.
 (eg. used for Spear Dashing)
- Can be used to cancel and perform an additional heavy attack during an Aerial combo.
- Fully executing a self destruct deals a large amount of damage to anything around the character and reduces HP to 1.
SD damage is increased by WAU (weapon attack up) chips and Melee attack buffs, as well as taunt.
A full SD is most commonly used just before a cutscene, since that gets around the long stagger afterwards.
### Additional Notes
- Being in a state of SD stagger or holding SD when a cutscene starts diables pausing for that cutscene.
The only way to skip the cutscene in that case is with holding B / Circle.

# Dialogue
Most Categories have a large amount of timesave that is all about avoiding, canceling or getting around dialogue that would slow down progression, or at least get through it quickly.
Therefor there is a lot of ways of dealing with different kinds of dialogue.
### Mashing
Mashing buttons fast to get through text boxes is pretty obvious, but there are some specifics about text in Automata.
**Text boxes** have **two stages** for each line:
1. the **Printing Stage** (the line is being printed to the text box one character at a time)
2. the **Completed Stage** (the full line is finished printing)

For this reason each line requires two inputs to be skiped: the first to skip the Printing Stage and complete the line and the second to skip said line. However there is a short **delay after a button is pressed** until that same button is accepted to advance dialogue again. To get around this pressing a different dialogue advancing button will work and get rid of the delay for the first input. Another property of most text boxes (except for novels) is that they only accept **one input at a time**.

This makes mashing **A and B** or **X and Circle** in an **alternating** pattern that fastest way of getting through text.

Finally the **declining option** for all choice dialogue gets **automatically selected** by pressing B or Circle, while the confirming option has not such shortcut.
Because of that each time an option needs to be declined a normal mashing pattern will do so automatically.
### (Partner) Dialogue Cancels
One of the most common ways to cancel dialogue is done by having **two dialogues "collide"**. This means that one dialogue is already active while another is triggered. In a case like this the game doesn't know what to do and closes both dialogues. (advances in case of text dialogue resulting in it staying open if it has enough lines)

Most of the time this is achived by **stopping** to **talk** to the **partner character** and **walking into another dialogue trigger** right afterwards; or **talking to an NPC** while in an animation that moves the player into a dialogue trigger shortly after.

In some cases cancels will also happen "automatically" by getting to a trigger fast enough that **story related dialogue is still playing**.
### Pod Pats & God Pat
Patting the Pod also **triggers dialogue** that can be used to cancel another one. Additionally when Pod patting the character bends over making their **hitbox extend behind** them which can be used to touch triggers with a Pod Pat.

The **normal Pod Pat** dialogue has a **low dialogue strengh** and can only cancel some dialogues, however after **patting the Pod 50 times** a special **higher strengh** dialogue is triggers, which is refered to as the **God Pat**. Currently there are no uses of the God Pat in runs.
### Dialogue Shortcut buffering
In some cases it is beneficial to have **voiced dialogue** end with a **specific timing** relative to in game animations.
This can be influenced with the **Shortcut Menu**. When the Shortcut Menu is opend the game will be paused instantly, but dialogue keeps playing for a short time.
By opening and closing Shortcuts quickly any **dialogue almost doesn't stop** at all while the **game gets frozen** for a **brief moment**. To allign the end of a dialogue with an animation this is repeated as manny times as required to get the right timing, this is called **Shortcut buffering**.

Most famosly this is used at the end of Prologue to make the dialogue there end just before one of Engel's attacks, to trigger the next cutscene instantly.
### Cutscenes
Ongoing dialogue is also canceled when **colliding** with a **cutscene**. Cutscenes are **strong canlcels** that instantly get rid of most text boxes even when they have multible lines.
There are exceptions to this however: if a text box contains a pop-up it can be brought trough cutscenes in some cases, but said cutscene **cannot** be skipped without closing the dialogue as well. (eg. EDS)
Most of the time cutscene cancels are very **situation specific** for obvious reasons, but they can get very flexible in some categories that aquire **Picture Books**. (refer to Picture Book section below)
### E-Drugs & Voice Changer
There are two ways to speed up voiced dialogue significantly: E-Drugs and Voice Changer.
- **E-Drugs:** 2 of the random effects of E-Drugs add an effect to voice lines that makes them multible times faster.
Use E-Drugs until you hear a high pitched use sound and the screen turns either retro green or get transparent graphical glitches at the sides.
- **Voice Chanager:** will be unlocked after completing ending A. The different settings change how the player charactzer speaks. Set this to one bar off of maximum for the fastest voice lines after completing A ending.
# Animation cancels
There are a few specific options for canceling animations in cases where SD will not work.
### Slow Walks
A slow walk animation normally plays whenever the player enters a cutscene trigger, this takes a few seconds until the cutscene will play. If the the player is either in an attck annimation or airborne this animation will be skipped.
### Button Press
To skip button presses animation and activate it inastantly interact with the prompt either during an aerial attack or while dropping out of an aerial dash.
# Warping
Several different types of warping are used in speedruns. These are mostly used in cases where transporting has not been unlocked yet, prior to negotiations or to otherwise advantageously dislocate the player character.
### Save scums
**Save scums** are used to quickly travel to an **activated transporter** of the save area you are currently in.
To perform a save warp simply **quick save** and **load** the save file afterwards. A save scum takes around 12 sec to perform (loadless) and saves time if the movement time saved exceeds that.
### Death warps
With **Death Warps** you can quickly travel **back to the transporter** last saved at or the **last checkpoint**.
Is commonly used in situations that need backtracking or to leave remote areas of the map, as well as some specific exploits.
A Death Warp is simply a **death on purpose** to respawn at a prior location. Note that you keep all progress except **exp** since last save and **equipped non system plugin chips** when death warping.
### Voidouts
The Void mechanic is a failsave that places the character back on solid ground when falling out of bounds. When voiding out the camera will face the direction the player model last faced before the void, this can be used to pre-setup the camera.
The time it takes for the character to void out depends on the distance traveled out of bounds as well as a general time frame.
Voidouts are commonly used to unload areas by falling far enough distance or to return to a starting point after hitting a trigger.
### Drown warps
Drown Warps happen when the player touches a drown trigger (usually water plains or around them). Upon drowning the Pod places the player back at a specific location either specified by the drown trigger or a checkpoint. Sometimes a drown can place the character back at the last location with solid ground, they can be distinguished from void outs by the pod animation and the player taking damage.
Drown warps are used to teleport to new areas just by reaching the drown trigger or to move further along the direction headed in.
# Misc 
A variety of different tech that doesn't fit other categries fully.
### Picture Books
### Mid-air System Menu
Usually the game just gets paused when trying to access the system menu in mid air or an attack animation. However there are two specific ways to open the system menu mid air:
- **SD method:** Fully self destruct, after you regain some control in a stumble animation the menu can be opened even in mid air. This is sometimes useful to load a save when getting stuck due to the game falsely interpreting a location as solid ground after a void out even though it will not refresh your movement and cause you to fall again.
- **Plunge Glitch method:** This version does not currently have any practical usecase, but it is possible to open the menu in one of the two frames you can use to input the heavy for a plunge glitch.
