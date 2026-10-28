🚩 Hack Club Polyglot - Code Playground & Quiz Game
A web app where developers and club members guess programming languages from short, tricky, or esoteric code snippets and execute live code directly in the browser across dozens of languages.
✨ Features
🎮 Interactive Quiz Game:
Three Difficulty Tiers: Mainstream (Easy), Tricky Syntax & Quirks (Medium), and Esoteric/Low-level (Hard: Brainfuck, Assembly, COBOL, APL).
Multiple Input Modes: Choice between 4-option Multiple Choice or Hardcore Typed Inputs.
Game Modifiers: Speed Run (8s timer per question) and Sudden Death mode.
Synthesizer SFX: Retro arcade sound effects generated dynamically using the Web Audio API.
Certificates: Canvas-generated downloadable Hack Club Certificate of Mastery upon completing a round.
⚡ Live Polyglot Playground:
Execute live code in 8+ languages using the free, open-source Piston Execution Engine.
Pass custom STDIN input parameters and inspect execution time, exit status, STDOUT, and STDERR.
🎨 Snippet Studio:
Create custom quiz questions for your local club or hackathon.
Export and import quiz packs in .json format.
🏆 Stats & Achievements:
Unlocks collectible badges ("Brainfuck Whisperer", "Polyglot Grandmaster", etc.) and persists statistics via localStorage.
🚀 Tech Stack
Frontend Framework: HTML5, Vanilla JavaScript (ES6+)
Styling: Tailwind CSS
Syntax Highlighting: Prism.js
Code Execution API: Piston Engine API
Sound Effects: Web Audio API Synthesizer
Icons & Fonts: Font Awesome 6, JetBrains Mono & Space Grotesk
🛠️ Local Setup & Deployment
Because this project is built as a self-contained single-file application, running it locally or deploying it is seamless and free:
Running Locally
Clone the repository:
git clone https://github.com/your-username/polyglot-playground.git

Open index.html directly in any browser (no build steps or node_modules required!).
Deploying for Free
GitHub Pages: Upload index.html to a repository and enable GitHub Pages in repository settings.
Vercel: Import your repository into Vercel and set the root directory to deploy instantly.
