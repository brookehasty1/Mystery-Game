PROJECT OVERVIEW


Pyramid Escape in an interactive, Egyption-themed escape room website created for CSC WP 4370 by Hamza Yassin and Brooke Hasty


The story follows a missing royal scarab, and the users goal is to find out who stole the scarab and escape the pyramid to freedom.


This website is designed for people who like puzzle games and mysteries. Its goal is to create an engaging experience using only HTML and CSS.


HOW TO RUN THE PROJECT


1. Download the protected files.
2. Keep the HTML files, style.css, and the images folder together in the project directory.
3. Open indes.html in the web browser
4. Use the navigation and instructions to explore through the puzzle to the final puzzle.


PROJECT STRUCTURE


- index.html: The home page introducing the story, explaining the goals and details of the room, and linking to the first puzzle chamber.
- subterranean.html: The first puzzle, featuring single-select and pattern-recognition puzzles.
- kings.html: The second puzzle, featuring tablet, balancing-scale, and pattern-recognition puzzles.
- queens.html: The third puzzle, featuring drawer, timeline, and pattern-recognition puzzles.
- clue_borad.html: An evidence board where players can inspect six clue cards.
- unlock.html: The final stage where players identify the suspect and attempt the escape code
- /images: Holds the images used on the website


DESIGN AND IMPLEMENTATION DECISIONS


HTML and CSS: The project calls for using only HTML and CSS, meaning in order to recognize user input, we need to use CSS selectors such as :checked in order to reveal content, select answers, flip cards, and control puzzle progression.


Visual Design: The website uses an Egyption-inspired theme with dark backgrounds, parchment-colored elements, and Georgia serif typography. Shared CSS variables and reusable classes allow for consistent styling.


Navigation and User Experience: A shared navigation menu allows for the user to access and move between each page. Instructions and hints help the users understand the puzzles and feedback messages communicate their progress. Organized around the goals: Explore the pyramid, collect clues, and escape


Accessibility and Responsive Design: The project includes HTML elements, descriptive alternative text, labeled form controls, visible keyboard-focus indicators, and skip-to-main content link on the puzzle chamber pages. The CSS allows for the screen to be adjusted based on the size of the screen with media tags.


TECHNICAL LIMITATIONS


Due to the project relying on only HTML and CSS, we could not provide user accounts, server-side game logic, or persistent saved progress.


TESTING


The website can be tested by:
   - Opening each page and checking that navigation links work.
   - Trying correct and incorrect puzzle inputs and observing how the page behaves.
   - Testing interactive elements with tab, arrow keys, and space.
   - Checking that focus indicators remain visible.
   - Resizing the browser to check layouts, text, images, and navigation on different screen sizes.
   - Revisiting pages after HTML and CSS changes to ensure that existing features still work.


TEAM


Brooke Hasty and Hamza Yassin


Course: CSC WP 4370
Project: Project 1 - Pyramid Escape
