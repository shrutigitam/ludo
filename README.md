# 🎲 Python Ludo Game (Tkinter)
A full-featured, multiplayer board game inspired by classic Ludo, created with Python’s Tkinter library. Play locally with 2–4 players—each with unique colored tokens, realistic dice rolling, animated movement, and all the home/kill/double-play logic you’d expect! Perfect for casual fun or as a Python GUI/OOP showcase.

## 🚩 Features
- **Vibrant Graphical Board:** Custom image assets for board and pieces—distinct styles for red, blue, green, and yellow players.
- **Faithful Ludo Gameplay:** Tokens start from “home” (you need a six!), move around the colored path, and race to the center to win.
- **Full Game Logic:** Handles all Ludo rules—bringing pieces out after a six, turn-based dice rolls (with up to three rolls for consecutive sixes), “killing” an opponent’s piece (sending it home), and doubles (your own two tokens safe together).
- **Complete Mouse Support:** Click to roll, move, and play—no console or terminal required.
- **Standalone:** No internet needed; just install Python, add your assets, and go!

## 🗂 Project Structure
├── main.py                
├──           
├── README.md

> **You must include all referenced `.gif` image files in your game folder:**
> - `whitebox.gif`, `red side.gif`, `blue side.gif`, `green side.gif`, `yellow side.gif`, `center.gif`
> - `greenbox.gif`, `greenstop.gif`, `yellowbox.gif`, `yellowstop.gif`, `bluebox.gif`, `bluestop.gif`, `redbox.gif`, `redstop.gif`, `head.gif`, `tail.gif`  
> - *(and others as referenced in the source code)*

## 🚀 Getting Started
1. **Clone or Download this Repository**
    ```bash
    git clone https://github.com/yourusername/python-ludo-tkinter.git
    cd python-ludo-tkinter
    ```
2. **Install Python (if not installed)**
    - Requires Python 3.x (comes with Tkinter on most systems).
      
3. **Make Sure All Image Assets Are Present**  
    - Place every required `.gif` file in the same directory as `main.py`.

4. **Run the Game!**
    ```bash
    python main.py
    ```

## 🎮 How to Play
- Press **ROLL** to roll the dice at your turn.
- Click your tokens to move them, following the game rules.
- **If you roll a 6**, you can bring a token from home or roll again (up to 3 times in a row).
- Land on another color’s piece to send it “home” (unless they have a double!).
- First player to bring all their tokens to the center wins.

## 🖼 Screenshots

> *(Add screenshots of the active board and gameplay here for extra polish!)*

## 🛠️ Technologies Used
- Python 3
- Tkinter (standard GUI library)
- Custom GIF images for UI

**Enjoy classic Ludo—now built by you, for your friends—right on your desktop!**
