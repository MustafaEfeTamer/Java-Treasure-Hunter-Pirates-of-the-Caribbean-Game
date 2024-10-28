### The Purpose of The Game : The character must start from a point and collect all the treasures on the map, but when he collects all the treasures, he must have traveled the shortest path at the end of the program. This is achieved with the shortest path algorithm we have established.


##### When the program is first launched, an interface with a button named "Go to Game Screen" and an image from the movie Pirates of the Caribbean greets us. If we click the button, it will take us to the game screen.
![image](https://github.com/user-attachments/assets/57719dfc-a666-484c-b8ea-8625d6aa2c38)


##### In the game interface, there are three buttons. The first button is "create new map," the second is "start," and the third is "results." When the first button is pressed, the map is randomly regenerated, and all obstacles, treasures, and the character's positions are randomly determined. When the second button is pressed, the character starts moving and leaves a green trail behind as it moves. The character's goal is to collect all the treasures on the map and ensure that by the end of the game, the character has taken the shortest path. As the character collects each treasure, the treasure disappears from the map, and the type and coordinates of the collected treasure are displayed in the top right corner of the interface. Once all the treasures on the map are collected, the character stops. The character must avoid colliding with dynamic and static obstacles while moving.
![image](https://github.com/user-attachments/assets/c96a3148-6f0d-4faf-8bf3-7499994ef486)


##### In the results interface, there are three fields. The first field contains "treasures discovered in order of priority," the second contains "traveled coordinates," and the third contains "total number of steps." In the first field, treasures and their coordinates are displayed in the order they were collected, then arranged by the priority order of the treasures: "gold" at the top, followed by "silver," then "emerald," and lastly "copper" at the bottom. In the second field, the coordinates the character traveled from the beginning to the end of the game are shown step by step. In the last field, the total number of steps taken by the character from the start to the end of the game, or the total distance traveled, is displayed.
![Ekran görüntüsü 2024-04-01 193138](https://github.com/MustafaEfeTamer/Pirates-of-the-Caribbean-Treasure-Hunt/assets/119308432/de96a18d-886d-4a22-95e4-cc62ea5b50d1)
