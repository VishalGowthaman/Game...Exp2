## Unreal-EX-NO-02-Create-a-player-movement-using-pawn-collectable-player-health-and-score-
## EX NO-02
## Create a player movement using pawn,collectable,player health and score 
## AIM:
### TO Create a player movement using pawn,collectable,player health and score.
## STEPS REQUIRED:
### 1)Create a new Unreal project and select a suitable template. Depending on the type of game you want to create, you may choose the third-person template, the side-scrolling template, or any other template that suits your needs.
### 2)Create a new level for your game. This level will be where you place the coins and any other objects that the player can interact with.
### 3)Create a new Unreal project and select a suitable template. Depending on the type of game you want to create, you may choose the third-person template, the side-scrolling template, or any other template that suits your needs.
### 4)Create a new level for your game. This level will be where you place the coins and any other objects that the player can interact with.
### 5)Add a player character to the level. This character will be the avatar that the player controls to collect the coins. You can either use a default character provided by Unreal or create a custom one using Unreal's character creation tools.
### 6)Place coins in the level. You can use Unreal's mesh editor to create coin models or import them from external software. Place the coins in various locations throughout the level.
### 7)Set up the coin collecting mechanics. Create a blueprint for the coins that enables them to detect when the player character collides with them. When a collision occurs, the coin should disappear and the player's score should increase. You can use Unreal's visual scripting language, Blueprint, to create this behavior.
### 8)Create a scoring system. Keep track of the number of coins the player has collected using a variable in the player character blueprint. Display the score on the screen using a UI widget.
### 9)Create a new level for the main menu UI. In this level, create a new widget blueprint for the main menu UI. Use the widget editor to add buttons for starting a new game, viewing high scores, and exiting the game.
### 10)Create a new level for the health UI. In this level, create a new widget blueprint for the health UI. Use the widget editor to add an image or text to display the player's health, as well as any other information you want to convey to the player.
### 11)Add a reference to the health UI widget in the player character blueprint. This will allow you to update the health display based on the player's current health.
### 12)Add a reference to the main menu UI widget in the game mode blueprint. This will allow you to switch between the main game level and the main menu level.
### 13)Add a button to the health UI that allows the player to return to the main menu. When the player clicks this button, set a variable in the game mode blueprint that triggers a level change to the main menu level.

## OUTPUT:
## Pawn Movement Event Graph:
  ![image](https://github.com/Prethiveerajan/Unreal-EX-NO-02-Create-a-player-movement-using-pawn-collectable-player-health-and-score-/assets/94233064/48de8e1f-c4a4-4489-a7fe-957e30d8d03f)
![image](https://github.com/Prethiveerajan/Unreal-EX-NO-02-Create-a-player-movement-using-pawn-collectable-player-health-and-score-/assets/94233064/e9b90413-1443-4f5c-af80-a0b01aee4840)



## Collision Event Graph:
![image](https://github.com/Prethiveerajan/Unreal-EX-NO-02-Create-a-player-movement-using-pawn-collectable-player-health-and-score-/assets/94233064/c4c207e1-c078-4692-90bf-a0682f16985b)

 

## MENU UI :	
![image](https://github.com/Prethiveerajan/Unreal-EX-NO-02-Create-a-player-movement-using-pawn-collectable-player-health-and-score-/assets/94233064/f2a8f797-55e6-427c-8f82-690b5e864683)

 
## STARTING PAGE: 
![image](https://github.com/Prethiveerajan/Unreal-EX-NO-02-Create-a-player-movement-using-pawn-collectable-player-health-and-score-/assets/94233064/c7142380-68b7-46d6-a870-4efa8b65d426)
![image](https://github.com/Prethiveerajan/Unreal-EX-NO-02-Create-a-player-movement-using-pawn-collectable-player-health-and-score-/assets/94233064/97227f88-8e84-4d09-b0e3-6cb69860fa29)

 


## SCORE INCREASING:
![image](https://github.com/Prethiveerajan/Unreal-EX-NO-02-Create-a-player-movement-using-pawn-collectable-player-health-and-score-/assets/94233064/23e4ff9e-bf0d-43a6-97ba-18e75d648ad0)


 
## RESULT:
Thus, we Created a player movement using pawn ,collectables ,player health and score.
