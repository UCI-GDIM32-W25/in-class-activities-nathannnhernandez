# GDIM32 In Class Activities

## W1
### Activity 1
- Get started on the minigame asap after it is assigned

### Activity 2
- Q1: 10

- Q2: 2
  
- Q3: prints "hello world" every frame
  
- Q4: Monobehaviour
  
- Q5: "x = 10"
  
- Q6: argument and its purpose is to fulfill a required parameter in a function
  
- Q7: Transform is calling a class and not a variable
  
- Q8: replace Transform with _playerTransform

### Activity 3
[MG1 Breakdown Table 8](https://docs.google.com/document/d/1UQTlTMUv7OoSRXdfaYn3iWpCgYABL-kNvOKmFYxCaUk/edit?usp=sharing)


## W2
### Activity 1
![image](https://github.com/user-attachments/assets/925cefb8-75c1-4494-b76c-d0bebd2c8f27)
### Activity 2
Created the player movement, made coins move, created space, instantiated coins.

[Commit Link
](https://github.com/nathannnhernandez/mg2-nathannnhernandez/commit/161804af2f6154b28f86d142dfa4297962ff9648)


## W3
### Activity 0
Carl
### Activity 3
![1](https://github.com/user-attachments/assets/c7cb6b6a-a2e4-4673-bed4-aabff9a79ceb)


## W4
### Activity 0
Kai
### Activity 1
The locator objects should be destroyed, so that only one singleton remains
### Activity 2
![IMG_0080](https://github.com/user-attachments/assets/c0368fc9-8572-4c8c-b6ad-9a4e3fcb8785)
### Activity 3
[Commit link...I wasnt able to actually do anything becaause I was having some troubles but I was able to create the project](https://github.com/UCI-GDIM32-W25/HW4/commit/54ec6fb1cf3f3f8b12fdb57de159f5532a4b8870)

## W5
### Activity 1
If I were to make a project like this I would keep the code mostly the same. I can access the IBreakable interface which allows me to manage weapon durability systems. From here I can individually assign stats to the child classes themseleves, which allows similar behaviour but dissimilar characteristics. This is especially helpful for unbreakable items, as I have the choice to avoid inherenting from IBreakable completely, without interferring with the parent class. This simplifies the elven sword class greatly, making the code cleaner and easier to read. Items, being an abstract class, allows me to do most of the coding from the child classes to generate specific behaviour. Because some characteristics of the item classes are shared unilaterally among child classes, it might be worth it to consider replacing the abstract class with one that houses more concrete behaviours.

### Activity 2
The model part is represented by the enemystats and itemdemo scripts. The player script represents the control, and the view part is represented by the dialogue displayed on screen.

### Activity 3
All of these design patterns are applicable to each scenario
  1. A finite state machine can be used before and after the player clicks the assigned button to determine when the beat must be hit relative to the timing in the song.
  2. A model view controller is relevent to a team shooter because the model is the weapon and ability stats, the controller would be carrying out the abilities, and the view would be the UI used       for activiating abilities
  3. State can be useful for the mining and planting behaviours because they can determine what state the player is in currently.

### Activity 4
Attendence: Nathan, Marcelo, Kai

[Proposal Form Link](https://docs.google.com/document/d/1IXMcedZDubU3jHOIg-ZRwtj0N-xMFaV7MpOOSQTA65Q/edit?tab=t.0)

## W6
### Activity 1
Gizmos: Our game is going to have platforming elements, which means that colliders are going to be a significant component. Using Gizmos can help indicate issues regarding kinematics and the interactions between game object colliders.

Unity Profiler: Because we are going to be using free assets, its important that we are aware of GPU usage. By using the profiler, we can identify the causes of frame drops and other performance issues stemming from assets.

Break Points: Break points can be helpful for any Unity project. As beginner programs, we make many errors. For more complex systems such as Inheritence, there are multiple interacting classes, and therefore more potential causes of any particular bug.Using break points, we can quickly identify the root cause of a bug. 

Merging: For the most part our group is inexperienced with GitHub, aside from what we have learned in 31 and 32. Understanding how to correct merging errors will be vital in our development process, as we are surely going to run into repository-related issues.

### Activity 2
Nathan Hernandez, Marcelo Thomas Esposo Tolosa, Kai Meng (came late due to game dev week)

## W7
### Activity 1
- raycast is used for line of sight
- physics.raycast used in code to create and modify the attributes of raycast
- ray cast often times cannot vertically detect obstacles
- use sphereccast to detect objects not detected by ray cast
- state machine for pursuit and wandering states

### Activity 2
Kai, Marcelo, Nathan

### Activity 3
![IMG_0245](https://github.com/user-attachments/assets/36745548-e26e-46b0-8353-f98f16c2efc8)

### Activity 4
[Trello Board Link](https://trello.com/b/SrpWWxTm/in-too-deep?utm_source=eval-email&utm_medium=email&utm_campaign=board-invite)

## W8
### Activity 1
- altering already rendered objects to improve their visual appearence
- effects, colors, retouching
- using a color filter can make a game more visually cohesive (color grading inspector)
- make sure that effects work with rendering pipeline

### Activity 2
 Kai Meng, Marcelo Thomas Espinosa Tolosa, Nathan Hernandez

### Activity 3
Kai:
I did not say anything to the playtesters at first, and they did not know that you could charge your character's jump. After telling them, they
found the mechanic to be difficult yet enjoyable. While the movement mechanic is still WIP, it seems to be working well. 
Around 50% of the playtesters' jumps resulted in their death, but they gradually decreased their margin of error. They encountered a bug where
the player can indefinitely suspend themselves in midair if colliding with the side of a platform. Playtesters suggested that the player should be 
able to move while falling -- it would make the game more forgiving.

# I recovered my account, but my W9 devlog isn't here :(

## W10
### Activity 1
Kai, Nate, Celo

### Activity 2
Celo: figured out easily how to consume food. The bar made it helpful to visually see the charge of the jump. Had trouble making it to islands at the beginning, sometimes slipped off of the islands. Had trouble going down the tower, kept dying to fall damage, possibly make the tower a little easier. Add lighting, trees make the shade too dark all around, add possible lanterns. Camera fixes, character moves right before camera does.

### Activity 3
[Trello Board](https://trello.com/b/SrpWWxTm/in-too-deep)

### Activity 4
[Commit Link](https://github.com/Nedajist/GDIM32-Final/commit/09185f45d671998319fee2b9bbd6d56f0d401143)

Finished up the rest of the level. Took advantage of coffee + double jump mechanics. BIG slope obstacle. Altered tower slightly.
