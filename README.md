#Tic-Tac-Toe Game
Overview
This Tic-Tac-Toe game is an interactive web-based version of the classic two-player game. It leverages HTML for structure, CSS for styling, and JavaScript for functionality, creating an engaging and user-friendly experience. The game includes drag-and-drop mechanics, score tracking, and persistent game state across sessions.

HTML Structure
The HTML provides the foundational structure of the game. It includes elements for the game board, draggable markers ('X' and 'O'), score display, and control buttons for resetting the game and scores.

Key Elements:
Game Board: A 3x3 grid where players drop their markers.
Draggable Markers: 'X' and 'O' markers that players drag to the board.
Score Display: Sections to show the current scores of 'X' and 'O'.
Control Buttons: Buttons for resetting the game and scores.
CSS Styling
The CSS styles the game, ensuring it is visually appealing and user-friendly. It includes styles for the game board, markers, and various UI elements.

Key Styles:
Game Board: Styled to look like a classic Tic-Tac-Toe grid with borders.
Markers: Distinct styles for 'X' and 'O' to make them easily identifiable.
UI Elements: Styles for buttons, score display, and overall layout.
JavaScript Functionality
JavaScript handles the interactive aspects of the game, including drag-and-drop mechanics, turn management, win/draw detection, score tracking, and game state persistence.

Key Functions:
Drag-and-Drop: Allows players to drag 'X' and 'O' markers and drop them onto the game board. Once placed, markers become non-draggable to ensure fair play.
Turn Management: Keeps track of whose turn it is and switches turns after each move. The game starts with the previous winner, adding a competitive edge.
Win/Draw Detection: Checks for winning patterns after each move and declares the winner or a draw appropriately.
Score Tracking: Uses localStorage to persist player scores across sessions, updating the display dynamically.
Game Reset: Clears the game board while retaining scores, allowing for a quick restart. The reset button also resets the draggable markers to their original positions.
