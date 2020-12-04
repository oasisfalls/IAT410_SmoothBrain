# IAT410_SmoothBrain

:crown:[Aneeta's Blog](https://github.com/oasisfalls/Aneeta_IndividualBlog)<br>
:peach:[Caleb's Blog](https://github.com/CalebTaylor/410-blog)<br>
:round_pushpin:[Louis' Blog](https://github.com/SergeantDlou/IAT-410-Personal-Blog)<br>
:fries:[Radu's Blog](https://github.com/Raadds/IAT410_Personal-Blog_RaduOrlandea)

# Team Blog

## Week 12 - FINAL WEEK

Our game is complete!!! We worked incredibly hard to polish the final game by adding in the tutorial, sound effects, music, bosses, new menu screen, game over screen, credits, and overall UI improvements. There are now borders for the timer bars that distinctly show which power up it is attached too, a border around the momentum bar, health bars for all the enemies, limited vision on level 2, and adjusting the overseer enemies line of sight where it won't start chasing if there is a wall between the smooth brain and the enemy. We also implemented the background music that we actually had original scores for and sound effects as well to enhance the overall experience of the game.

At this stage we do feel that we could develop this further since we were pressed for time and were not able to incorporate the keys in the puzzle room component that we originally wanted, although it wasn't a necessity for the game. It was a tough semester but we are proud of what we have accomplished with this class!!

> *December 4th, 2020*


## Week 11

This week we pushed hard to polish our Beta code, and although we did not accomplish everything that we wanted to, we are aware of the next steps to be taken towards our final polish. After the lab session and the multiple playtests that we had, we gained a lot of insight on how to possibly ramp our game better as it was quite difficult from the very first level. 

We were able to implement two new enemies, updated character designs, added a full map of rooms for each level which have much better ramping throughout, the final boss, updated environmental sprites, and added some UI visual feedback elements that will be replaced with clearer visuals. These feedback elements include a diegetic indication of when it is the best time for the player to bounce off of any walls which is currently a blue border around the player, and we also have other HUD elements such as the momentum bar and countdown timers to indicate when the power-ups will be gone.

Our playtesters really enjoyed these new updates, although the biggest thing that we were unable to implement is the tutorial, which based on our playtests, definitely would've helped a lot, although we were happy to hear that players still thoroughly enjoyed the game thus far. 

The tutorial will for sure be implemented in the final version which will give a better idea of the narrative for the players. We will be adding health bars for the enemies, and are currently having an original score composed for the entire game that we will add as well. Sound effects are likely to be added as well to enhance the feedback for the players and sprite characters will be animated. We left the animation of the sprite characters for very last incase we revised the design along the way. A lot of progress will be made this weekend towards the final!

###### Bomb Brain
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/bomg_brain.png)
when touching this brain, the player immediately dies and the bomb brain will also chase the player when it is in close proximity

###### Turret Brain
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/Gun_brain.png)
this brain will shoot projectiles towards the brain in whichever direction the player is

###### Uncle Brain
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/uncle_brain.png)

###### Smooth Brain Update
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/new_brain.png)

###### Level 2 Mini-Map
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/14.png)

###### Level 3 Mini-Map
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/27.png)

###### Screenshot of a Level 2 room and Turret Brain
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/level2.jpg)

###### Screenshot of Level 3 room and Bomb Brain
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/level3.jpg)

> *November 26th, 2020*



## Week 10

During our meeting this week we created a to-do list and brainstormed what we wanted to implement for our beta code which included an RNG version to test, rooms for each floor, adding soft blocks to some rooms, new enemies such as a turret enemy and a self-harm exploder, environmental hazards such as a moving block, updating old enemies, boss types for each floor, visual feedback elements such as taking damage, enemies being slowed, and diegetic UI such as the brain having a hat and having it fill up with a color to show how much momentum it has built up, as well as the brain looking more beat up as it takes damage. 

Sprite were another big portion to tackle as we are creating new enemies, re-working our previous characters, adding enemy tints when the ice powerup is picked up, and also animating the sprites as well.

After figuring out what we want to achieve we split up roles accordingly and got to work, then checked in on Monday. As of right now we don't have any visuals to show other than a sprite for our final boss, who is also known as uncle brain, but we do have a way of implementing RNG rooms, although there are still aspects of that to figure out such triggering the doors to go between rooms since the RNG version is all on one scene in Unity. 

###### Uncle Brain Boss
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/week10_uncleBrain.png)

> *November 19th, 2020*


## Week 9

We did not make any progress this week as we were not able to have a meeting, but will be having a meeting Thursday morning.

> *November 11th, 2020*


## Week 8

It was a very busy week as we worked up until the minute of our deadlines. We began by reconvening Monday evening. We didn't get everything that we wanted to get done for this prototype but we did make a lot of progress. The tile sprites have been revamped, there are new sprites for the power ups, added a cooldown for the clicks, added an arrow that appears when clicking and holding to gives visual feedback for our players to know what direction they will be launching their brain in, added entrances/exits for the rooms so that the player is able to go back and forth once enemies in a room have been defeated, implemented our new powerups, and when the player gets to a new room, their health will replenish. We created a temporary Home Screen and Game Over screen, and also included a tutorial splash screen that appears when clicking the instructions from the home screen. We do intend to create a full narrative tutorial level instead of the splash screen and have a full narrative set aside but it was not a priority this week, for this prototype we just wanted to ensure that we had some teaching component. 

Some very clear visual changes are in the doors appearing in the rooms and the mini map that we have in the corner of each room. The doors appear only when the player has successfully gotten all of the enemies to concuss themselves, and the use of the mini map in the corner allows the player to know where they are on that floor, and how far away they are from reaching the next one. 

A very big critique that we recieved and fixed this week was the contrast in size between the characters and the room. Previously, the rooms were very large and our characters seemed very small, giving a feeling of imbalance, but we have now adjusted the sizes of the room and characters to create a more aesthetically balanced room.

For this prototype we have the rooms hardcoded in a specific order, although we do intend to make them RNG so that the player does not know what to expect everytime they play. Momentum was another aspect that we made sure to add - so the faster the brain continues to bounce off of the walls, the faster it will go because it is building momentum, however, when the longer the brain trails off, the slower it will get. If the brain eventually comes to a full stop in an area that has no nearby walls for it to bounce off of, it has the ability to bounce in any direction, at the price of losing some HP points. 

We worked on the GDD and did 5 playtesting runs with various different players this round which gave us some very insightful feedback for our next prototype.

###### Power Ups

![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/shield.png)
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/ice.png)
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/heart.png)<br>

###### Direction Arrow
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/dial.png)

###### Mini Map
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/1.png)

###### New Room Tiles Added
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/proto2.jpg)


> *November 4th, 2020*

## Week 7

This week the most progress we made was new wall sprites and different state sprites for one of our enemies and environment. Our entire team unfortunately fell very busy with other classes and did not get to accomplish what we had planned, but we did have a meeting on Tuesday evening and set internal deadlines and specific tasks that needed to be done, as well with others that were low priority, so that we could make sure to have the requirements complete for the next milestone.

> *October 29th, 2020*

## Week 6

With more time to work on our next prototype, our team got together on Sunday evening to discuss feedback that we recieved from our classmates, TA, and prof during our lab, how we want to implement that, and other changes we would like to have done for the next prototype as well. We made quite a long list and noted some points that would be a much lower priority than others such as the story to incorporate into our tutorial level as we aim to have animations for that, but the mechanics are the main focus that we want to complete these coming weeks. We assigned roles for every member, Caleb will handle sprites, creating soft block tiles and an angry state for the skateboard enemy sprite, Louis will handle general coding, Radu will work on more level design and refining our current levels in Unity, and Aneeta will handle the supplementary documents going towards the next hand-in such as the GDD and setting up Playtesting templates. We will be refining what we want done and what tasks each team members will be doing/assisting others with when we have a check-in meeting on Friday.

> *October 21st, 2020*

## Week 5

This week we ended up having three meetings. During our first meeting on Friday evening we discussed initial thoughts on our prototype to prepare for playtesting sessions, and then decided on what to change/add to be ready for our playtesting session. Since we could not progress further with an updated GDD, we had our second meeting on Sunday evening to finalize the prototype and decided how many playable levels we'd incorporate since we had hand drawn many level designs. 

We had our final meeting on Tuesday in two sessions. First was to brush up the prototype such as adding the ability to reset back to level 1 once the player dies and so that when the player is at a low enough speed and isn't near a all, it will be able to launch itself again at the cost of health. One of our team members then ran the playtesting sessions, and then we regrouped to discuss the outcomes and completed the GDD along with the Playtesting sheet. We have some updated sprites to add this week as well such as two enemy types to differentiate it from the main player, and the walls. 


![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/patrol.png)
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/overseer.png)
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/image1.png)
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/image2.png)
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/image3.png)
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/121620525_3562808593776523_2709045946983355320_n.png)

> *October 14th, 2020*

## Week 4

We had nothing necessarily due this week, but to prepare for the upcoming playtesting our group had a meeting on Monday evening to really solidify the mechanics of our game after the critique that we got in the previous lab. We had assigned specific things for each teammate to do and aimed to have our prototype done by Thursday. 

Some details that we figured out were that each time our brain character kicks off of a wall it was increase their momentum, which will be calculated by vector equations. Friction is always at play, and we incorporated ways to restore health during levels such as using the idea of having it in a hard to reach corner or area of the room where it will only spawn at a certain time. We are not sure if we want this game to be realtime yet although we are leaning towards it, but ultimately we will decide after playtesting. 

Otherwise, the prototype has begun, team members are learning to code and learn the engine to assist our head developer, and the artwork and level design is slowly progressing as well.

> *October 6th, 2020*


## Week 3
Our team had two meetings this week, one on Monday to discuss and complete our first version of the GDD, and then one on Tuesday to create our presentation. During our Monday meeting our team discussed and agreed upon how our movement mechanics would work, which is using the mouse and right clicking to briefly stop time to allow the player to choose a direction to go in for their smooth brain. A rough idea of this concept is shown below.

![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/movement.png)

Majority of the GDD was quite straight forward from our proposal but we decided to create very rough ideas of what our gameplay would look like including the home and game over screen so that we had more visuals for ourself and also for our presentation. After our GDD was completed we worked on the slides for our presentation in figma and then created a script. The idea of basing the levels off of parts of the brain was brought up in the meeting and so far we all like the idea but have not gone into details about how the levels would be crafted yet or how they would exactly look. The artwork for the characters and a potential power up was created as well.

**Bruised Brain**<br>
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/120287939_328342851923026_532575373114201167_n.png)<br>
**Smooth Brain**<br>
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/120290944_1474990312711948_7814499561616464042_n.png)<br>
**Ice**<br>
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/ice.png)<br>
**Home Screen**<br>
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/home.jpg)<br>

**Options Screen**<br>
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/options.jpg)<br>
**Game Over Screen**<br>
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/gameOver.jpg)<br>

**Game Play Designs**<br>
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/example.png)
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/example2.png)<br>

**Figma file for presentation**<br>
![myImage](https://raw.githubusercontent.com/oasisfalls/IAT410_SmoothBrain/master/weeklyPics/Figma.png)<br>

> *September 30th, 2020*



## Week 2 
Following the greenlight presentation during lecture, we noted down the critiques that we recieved and then had a very brief meeting on Monday evening to discuss them while refining specific points such as the camera angle and movement. Movement seemed to be something that we haven't narrowed down entirely yet, so we have agreed to brainstorm 2 - 3 ways of movement that we would like to implement for our next meeting, where we will also address any critiques that have been given on canvas from the game proposal submission.<br>
> *September 23rd, 2020*


## Week 1 
This week we formed our team, created our team contract and established communication methods through a Discord server and a Facebook group chat. We had our first meeting on Monday evening to work on the game proposal and prior to the meeting we made sure that each team member came with 2-3 rough ideas for the game so that we could all brainstorm and discuss. Details about the meeting were also jotted down. The game proposal document was then polished and submitted, and then we prepared our presentation for the lecture.<br>
> *September 16th, 2020*



