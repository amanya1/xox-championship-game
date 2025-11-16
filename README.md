# xox-championship-game
XOX Line Champion: A Continuous-Score Tic-Tac-Toe Game

This project is a single-file HTML/CSS/JavaScript implementation of a modern, score-based Tic-Tac-Toe (XOX) game. Unlike traditional XOX, this game focuses on continuous scoring over a full board, featuring a challenging Tournament Mode and fun Dares for the loser.

The application was built entirely through collaborative prompting with the Gemini 2.5 Flash model, demonstrating the power of iterative development and sophisticated prompt engineering.

🚀 Game Features

The final application incorporated several complex feature changes requested during the development process:

Feature

Description

Continuous Line Scoring

The core logic was transformed from a first-to-win system to a system where players score points based on the total number of unbroken lines ($X-X-X$ or $O-O-O$) they create when the board is full.

Dynamic Grid Sizes

Players can choose to play on a standard 3x3 board or a more complex 4x4 board.

Tournament Mode

A "Best of 3" mode tracks round wins, determining the overall series champion.

Post-Game Dares

A fun social element where the loser of the round or tournament is presented with an entertaining, randomly selected dare.

Responsive UI

The game layout is fully responsive and uses Tailwind CSS for a modern, clean design.

🧠 The Power of Collaborative AI Development

This project serves as a practical example of how AI models like Gemini 2.5 Flash can function as a pair programmer and technical consultant, guiding a project through multiple feature pivots.

Utilizing Gemini 2.5 Flash

The game logic, structure, and user interface were generated and refined by the Gemini 2.5 Flash model. This powerful model was critical for:

Rapid Feature Pivots: Converting the initial concept from an "SOS" game to a continuous-scoring "XOX" game, which required a complete re-write of the core win/scoring logic (calculateTotalLines).

State Management: Implementing the complex state required for the Tournament Mode (tracking round scores vs. tournament scores, managing round advancement, and declaring a final champion).

Debugging & Refinement: Identifying and fixing multiple critical bugs (like the "white screen" error caused by invalid CSS) quickly through detailed analysis of the provided code.

This access to cutting-edge AI assistance was made possible through programs like Google Pro for Students, demonstrating the practical benefits of such educational resources beyond simple image generation.

The Role of Prompt Engineering

The success of this project hinged on the ability to provide clear, multi-layered instructions. The iterative, highly specific nature of the prompts—which detailed new features, corrected previous logic, and defined the required output structure (a single HTML file)—was directly influenced by prompt engineering principles.

Specifically, the learning from courses such as Xavier Amatriain's LinkedIn Learning course on Prompt Engineering proved essential for:

Clarity and Constraint: Defining hard boundaries for the output (e.g., "single file only," "no alert()").

Iterative Refinement: Building on previous code versions while describing the specific changes needed (e.g., "now make the game end only when the board is full, and score based on lines").

The final game is a testament to the fact that effective communication with AI is the new frontier in rapid software development.

🛠️ How to View and Play

Since this is a single, self-contained HTML file, setting it up is incredibly easy:

Clone this Repository or download the xox_game.html file.

Open the file directly in any modern web browser (Chrome, Firefox, Edge, etc.).

(For instructions on hosting this game live via GitHub Pages, see the section below.)
