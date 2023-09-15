# Chandrayaan
Assessment
**Spacecraft.js (Spacecraft Class Implementation):**
This code defines a Spacecraft class, which represents a lunar spacecraft.
The class has properties position and direction to track the spacecraft's location and orientation.
It provides methods like getPosition and getDirection to retrieve the spacecraft's position and direction.
The executeCommand method interprets commands (e.g., 'f' for forward, 'l' for left) and invokes corresponding methods to perform actions.
The moveForward and moveBackward methods update the spacecraft's position based on its current direction.
The turnLeft, turnRight, turnUp, and turnDown methods change the spacecraft's direction as needed.
The class follows a modular structure, making it easy to extend and maintain.

**Spacecraft.test.js (Jest Test Cases for Spacecraft Class):**
This code defines a test suite for the Spacecraft class using the Jest testing framework.
It imports the Spacecraft class from the spacecraft.js file.
Inside the test suite, there are individual test cases for various spacecraft actions, such as initialization, moving forward/backward, turning left/right, and turning up/down.
The beforeEach function ensures that a new Spacecraft instance is created before each test case, ensuring a clean state.
In each test case, specific actions are performed using the Spacecraft instance, and then assertions are made to check if the spacecraft behaves as expected.
