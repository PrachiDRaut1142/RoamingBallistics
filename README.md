# RoamingBallistics
"Roaming Ballistics" is a JavaScript and HTML project featuring balls of random sizes and colors that move dynamically across the screen. They bounce off walls and collide with each other, creating an engaging visual experience. This project showcases principles of motion and collision detection, providing users with an interactive demonstration in their web browser.

### Getting Started

**Way 1: Using Visual Studio Code with Live Server**

1. Clone the project repository `https://github.com/PrachiDRaut1142/RoamingBallistics.git`.
2. Install the `Live Server` extension in Visual Studio Code.
3. Open the `index.html` file.
4. Right-click and select `Open With Live Server`.


**Way 2: Using a Web Browser**

1. Navigate to the `project directory` in your `file explorer`.
2. Right-click on `index.html`.
3. Choose your `web browser` from the `Open with options`.


### Concepts Demonstrated: This project includes demonstrations of the following concepts:

**HTML5 Canvas:**
The project utilizes the HTML5 <canvas> element to draw the balls on the screen. The canvas provides a space where you can use JavaScript to create and manipulate graphics, offering a powerful tool for dynamic and interactive visual content.

**JavaScript Classes:**
The code employs JavaScript classes to define and manage ball objects. Each ball is an instance of the Ball class, which encapsulates properties like position, velocity, size, and color, as well as methods for drawing and updating the ball.

**Animation:**
Animation is achieved using the requestAnimationFrame method, which allows for smooth and efficient updates to the canvas. This method calls a specified function to update the animation before the next repaint, ensuring that the animation runs at the optimal frame rate.

**Collision Detection:**
Collision detection is a key aspect of the project. The balls are programmed to detect collisions with the walls of the canvas and with each other. When a ball collides with a wall, its velocity is reversed, creating a bouncing effect.

**Event Handling:**
The project includes event handling to make the animation interactive. A mouse move event listener is added to the canvas, allowing users to interact with the balls. When a user hovers over a ball, its color changes, adding an interactive element to the visual experience.

**Randomization:**
Randomization is used extensively to create a diverse and visually interesting animation. The balls are initialized with random sizes, colors, positions, and velocities. This randomness ensures that each execution of the project presents a unique and engaging visual display.

These concepts come together to create a dynamic, interactive animation that demonstrates fundamental principles of computer graphics and interactive programming.