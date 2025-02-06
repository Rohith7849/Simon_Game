# **Simon Game**

## **Project Overview**

The Simon Game is a classic memory-based game where players must repeat a randomly generated sequence of colors. The game gets progressively more challenging as the sequence length increases with each correct round.

---

## **1. How to Play?**

- Press any key to start the game.
- Observe the sequence of colors that light up.
- Click the buttons in the same order as shown.
- If the sequence is entered correctly, the game continues with an additional color added to the sequence.
- If the sequence is incorrect, the game ends, and players can restart.

---

## **2. Technologies Used**

- **HTML**: Structure of the webpage.
- **CSS**: Styling and layout.
- **JavaScript (jQuery)**: Game logic and interactivity.

---

## **3. File Structure**

### **3.1. HTML (index.html)**

- Defines the basic structure of the game.
- Includes a title, buttons for the four colors, and links to CSS and JavaScript files.

### **3.2. CSS (styles.css)**

- Styles the game elements.
- Adds color effects, button styles, and game-over animation.

### **3.3. JavaScript (game.js)**

- Handles game logic.
- Generates random sequences.
- Captures user input and checks for correctness.
- Plays sound effects and animations.

---

## **4. Game Logic**

### **4.1. Starting the Game**

- The game begins when a key is pressed.
- The level counter starts at zero and increments with each successful round.

### **4.2. Generating Sequences**

- The game randomly selects one of four colors.
- The selected button blinks, and a sound is played.
- The sequence is stored in an array.

### **4.3. User Interaction**

- Players click the colored buttons.
- Each click is stored and compared with the generated sequence.
- If the sequence is correct, a new color is added.
- If incorrect, the game ends, and a "Game Over" message is displayed.

### **4.4. Restarting the Game**

- After a wrong input, the game resets.
- Players can restart by pressing a key.

---

## **5. How to Run the Project?**

1. Clone the repository or download the files.
2. Open `index.html` in a web browser.
3. Press any key to start the game.
4. Follow the sequence and try to beat your high score!

---

## **6. Future Enhancements**

- Adding difficulty levels.
- Implementing a high-score tracking system.
- Adding sound customization options.

---

### **Enjoy playing the Simon Game!**

