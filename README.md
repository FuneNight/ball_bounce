# ball_bounce
This learning project defines a simple graphical animation called "BallBounce". It creates an animation of balls bouncing around a window, handling their movements and collisions.

Ball Class: Ball class defines the properties and behaviors of each ball, including its position, velocity, and how it should be drawn on the screen.

Ball Array: The program maintains an array of Ball objects (list), initializing four balls at different starting positions with random velocities.

Collision Detection: In the move method, the program checks for collisions between balls. When two balls collide, their paths or velocities are altered.

Movement and Painting: Each ball's position is updated in the move method, and they are redrawn in the overridden paint method.

Main Method: The main method sets up a JFrame window titled "Ball Collision" and adds an instance of BallBounce to it. The window's size is set, and it's made visible. The program enters a loop where it continually updates the ball positions (via move) and repaints the frame, creating the animation effect.

Animation Loop: The infinite loop in the main method with a Thread.sleep(10) call causes the animation to be updated every 10 milliseconds, giving the appearance of continuous movement.

Overall, this project helped me understand the basic principles of animation, collision detection, and object-oriented programming in Java. It's a good example of how to use the Java Swing framework for creating simple animated graphics.
