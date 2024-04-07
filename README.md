[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Shuo-Wen (Auston) Chang
### Student number: 46291539


## 1. Player Experience (~700 words)

Each level section has its own meaning. Level one, which is section one, is the introduction. It gives players the chance to understand the mechanics and the dynamics. It causes the section to be easy but a short level. Level 2 (Section 2) is a level that increases some enemies and requires a bit of skills. It means that you cannot easily pass through it like Section 1. It has a door players need to trigger, and players need to climb up to reach the next key and next level so it helps you to improve players controlling and understanding of the game so players can get prepared for the next level which is Section 3. The final level has many monsters and stuff that needs to be triggered. The map is not very spacious, so enemies get close, making the level more difficult. Players may need some better controlling for them to dodge the attacks. After all the levels, players should already find all the keys and find the way back to the key door otherwise players can still go back the same way because the map is reversible. 

### 1.1. Discovery

Players can learn from the game that they should maintain a steady pace and observe the surrounding environment because all designs have their meaning, so if you accidentally miss any trivial details, you may need to spend more time looking for them or make sure the correction. 

The structure of encounter creation is clear and concise, making it easier for users to understand the game. 

Feedback from your own playtests helps reinforce learning and correct misunderstandings. 

### 1.2. Drama

Start with easier challenges or tasks at the beginning of the game to ease players into the experience. As they become more familiar with the mechanics and gameplay, gradually increase the difficulty to keep their interest and remain challenged. 

Introduce a variety of game mechanics, challenges, and obstacles to keep the experience fresh and engaging. Alternating between diverse types of gameplays helps prevent monotony and adds depth to the overall experience. 

Pay attention to the pacing of your game, ensuring that intense moments are balanced with quieter, more contemplative sections. Monsters in the game do not respawn, so if you kill them, you will have a lot of room to relax. But before that, the monster will not stop attacking at will. 

### 1.3. Challenge

The challenge is making sure the game mechanics are intuitive and easy for inexperienced players to understand. Overwhelming players with complex mechanics or information from the start can lead to frustration and disengagement. To solve this problem, you can introduce mechanics gradually through tutorials, tooltips, or guided gameplay sequences, allowing players to learn at their own pace. 

### 1.4. Exploration

Each section has been carefully designed with a unique aesthetic and layout to create an unforgettable and immersive space. Whether it is a lush forest, a vast cityscape, or a mysterious underground cavern, the visual and spatial design of each level has been carefully crafted to evoke an atmosphere and atmosphere that captivates players and invites them to explore. My level design focuses on creating environments that foster autonomy, encourage exploration, and provide players with a memorable and immersive experience that keeps them engaged from start to finish. 

## 2. Core Gameplay (~400 words)

At the beginning, the player first contacts Passthrough Platforms and Weapon Pickup (Staff). This will let him know that he can pass through this special terrain at will and obtain the first weapon in the game. If the player does not pass through Passthrough Platforms to obtain the weapon, it will cause the player to be trapped in front of him. Obstacles prevent progress. After obtaining the weapon, the player can use the weapon to destroy obstacles and then the player will encounter Chompers. Although Chompers can move, they only attack at close range. At this time, players can use attacks to kill monsters. Next, there will be indestructible obstacles such as Spikes, which will cause the player to lose HP. At this time, the player can only stay away from Spikes. If the player unfortunately encounters Spikes and loses HP, there will be Health Pickups for the player later. It can help the player gain an HP point that will later have Checkpoints because they will encounter Acid on the way. If the player accidentally falls into Acid, they will return to the most recently touched Checkpoints. Players need to wait for the arrival of Moving Platforms. Standing on Moving Platforms allows players to safely navigate dangerous Acid. There will be a Spitters waiting for you when you reach the safe side. The player needs to attack him otherwise he will attack the player from a distance. Just keep walking and you will get the first key. After obtaining the first key, players will find Weapon Pickup (Gun) in level 2, which can perform remote attacks and trigger some Switches to help players break through the Trigger Door and reach the end. 

### 2.1. Passthrough Platforms 

### 2.2. Weapon Pickup (Staff)

### 2.3. Chompers

### 2.4. Spikes

### 2.5. Health Pickups 

### 2.6. Checkpoints

### 2.7. Acid 

### 2.8. Moving Platforms

### 2.9. Spitters

### 2.10. Keys

### 2.11. Weapon Pickup (Gun)

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
![WholeLevel](DocImages/Screenshot 2024-04-07 202839.png)
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1
![Section1](DocImages/Screenshot 2024-04-07 201709.png)
![Section1](DocImages/Screenshot 2024-04-07 230011.png)
### 3.3. Level Map – Section 2
![Section2](DocImages/Screenshot 2024-04-07 201940.png)
![Section2.2](DocImages/Screenshot 2024-04-07 202616.png)
### 3.4. Level Map – Section 3
![Section3](DocImages/Screenshot 2024-04-07 202028.png)

## 4. Iterative Design (~400 words)

In the initial setup of the first prototype, the design was too simple, and the map was too small, so I wanted to expand the map a little and make it more difficult. In the second prototype, although the length of the map was slightly increased and the game difficulty was a little more difficult, the feeling was still far from the complete work, so many other designs were added to the third prototype to make the levels easier to distinguish. In the third prototype, more design was added to the third level and some other minor design flaws. It makes the whole game look more interesting and richer. However, because it was found that the second level was not obvious in the third prototype, the design of the second level was enhanced in the final work and all parts of the map were improved to give players enough time. Enjoy the gradual changes throughout the map and levels. 

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


