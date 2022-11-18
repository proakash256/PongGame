# PongGame
This is a simple version of the Pong Game, which was one of the first computer game ever created.

Pong is a table tennis–themed twitch arcade sports video game, featuring simple two-dimensional graphics,
manufactured by Atari and originally released in 1972.
Turtle module of the Python Standard Library is mainly used to make this project and the concept of
Object Oriented Programming has been used extensively.
This project facilitates two players to play the game against each other.

The Steps involved in creating this project are :

1. Setting up the Screen :
   The Game Screen is of the size 800 x 600 px and its background colour is black.
   
2. Creating and Moving the Paddles :
   The paddles are fundamentally Turtle class instances. The paddles are coloured white. The dimensions of the paddles
   are 100 x 20 px. The Right paddle moves Up and Down using Upward and Downward Arrow keys and the Left paddle moves Up
   and Down using W And S keys.
   
3. Creating and Moving the Ball :
   The ball is also a Turtle class instance and is coloured white. The dimensions of the ball is 20 x 20 px.
   At one point, the ball move 10 px in both x and y coordinates.
   
4. Detecting the Collision with the Upper and Lower wall and bouncing back :
   When the y coordinates of the ball is greater than 280 or is less than -280, then the y coordinate of the ball movement
   is multiplied by -1, so that it turns negative and hence the ball bounces back.
   The coordinates can be changed according to the Screen Size.
   
5. Detecting the Collision with the Paddles and bouncing back :
   When the y coordinates of the ball is greater than 320 or is less than -320, and the distance between the ball
   turtle instance and the paddle turtle instance is less than 50 pxthen the y coordinate of the ball movement
   is multiplied by -1, so that it turns negative and hence the ball bounces back.
   The coordinates can be changed according to the Screen Size.
