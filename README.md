# Project: Cheerup
#### Video Demo: https://youtu.be/L6bZ-A2hB9w
#### Description:

## Overview
**Cheerup!** is a small but cheerful interactive web application designed to celebrate user interaction with a simple, fun, and positive experience. This application ask to go out if user press yes, then excitment increases and after that when a user clicks the “Ask again?” button, the application redirects them to a first page that displays an animated baby GIF along with a Question.  

Although the project looks simple on the surface, it demonstrates how **HTML, CSS, and JavaScript** can work together to build interactive and engaging web applications. This project was created as part of my CS50x final project, aiming to practice the fundamentals of web development while also creating something delightful and user-friendly.

---

## Features
- **Two HTML Pages:**  
  - `index.html` is the entry page, where the user interacts with the question and the button.  
  - `yes.html` (the second page) displays the celebration message along with an animated GIF.  

- **Animated GIF:** A cute animated baby GIF is used to visually express excitement and joy, making the page feel lively.  

- **Celebratory Message:** The text “Hurrrrreyyyy!” reinforces the fun and celebratory tone of the project.  

- **Optional Sound Effect:** With the help of JavaScript, the project can be extended to play a short “pop” sound whenever the button is clicked. This adds an additional sensory layer to the interaction. but i didn't use it

- **Responsive and Clean Design:** The CSS styles ensure the application looks good on both desktops and mobile devices.  

---

## File Structure
- **`index.html`**  
  The main entry file. It contains the initial layout with a simple message and a button. Clicking this button takes the user to the celebratory page.  

- **`yes.html`**  
  The second HTML file. It displays the animated baby GIF and the celebratory message. This file is the “highlight” of the project.  

- **`style.css`**  
  The stylesheet used for both pages. It defines the layout, fonts, colors, backgrounds, and button designs. It also ensures the wrapper (the container for content) is centered and styled nicely.  

- **`2.gif`**  
  The animated baby GIF displayed on the celebration page. It is the key visual element of the app.  

- **`script.js` (optional)**  
  A simple JavaScript file that can be added to handle sound effects when the button is clicked. but i use internal js


---

## Design Choices
1. **Simplicity First:**  
   The design was kept intentionally simple so that the core learning objectives—HTML structure, CSS styling, and optional JavaScript—could be clearly demonstrated.  

2. **Animated GIF Instead of Static Image:**  
   A moving image adds more excitement and better conveys the celebratory mood than a still picture.  

3. **Cheerful Color Scheme:**  
   Bright and warm colors like yellow and light blue were chosen to match the theme of happiness and positivity.  

4. **Optional Sound Effects:**  
   To make the project flexible, sound effects are optional. Users who want additional interaction can add the JavaScript and audio file, while those who prefer silence can leave it out.  

5. **Mobile Compatibility:**  
   The CSS was kept lightweight and flexible, ensuring the project displays properly across different screen sizes.  

---

## Future Improvements
Although the project is complete in its current form, there are several directions in which it could be expanded:  
- Adding a set of **random GIFs** so each button click leads to a new celebratory animation.  
- Allowing users to **input custom messages** that would then be displayed on the celebration page.  
- Adding **background animations** such as balloons, fireworks, or falling confetti.  
- Creating a **music loop** in the background to further enhance the celebratory feel.  
- Expanding the project into a small game or quiz where correct answers trigger the celebration.  

---

## How to Run
1. Place all project files (`index.html`, `hurrrrreyyyy.html`, `style.css`, `2.gif`, and optional `script.js`/`pop.mp3`) in the same folder.  
2. Open `index.html` in any modern browser (such as Chrome, Firefox, or Edge).  
3. Click the button on the first page to load the celebration page.  
4. If JavaScript and audio are included, enjoy the sound effect when the button is pressed.  

---

## Skills Learned
This project helped strengthen my understanding of:  
- **HTML**: Structuring multiple pages and linking them together.  
- **CSS**: Styling elements for layout, responsiveness, and color themes.  
- **JavaScript**: (optional) Adding interactivity like sound effects through DOM manipulation.  
- **Project Organization**: Managing files, separating style from structure, and keeping the design clean.  

---

## Reflections
The biggest challenge was keeping the project both simple and engaging. I had to balance between not over-complicating the design while also ensuring that the project demonstrates creativity and technical skill. For example, deciding whether to include background music or just a sound effect required some thought. In the end, I kept sound optional to allow flexibility.  

This project may look small, but it reflects many real-world web development concepts: linking multiple pages, styling them consistently, adding visuals and interactivity, and ensuring they run across devices.  

---

## License
This project was created for educational purposes as part of the **CS50x Final Project** in 2025.  

