# King of Tokyo

**King of Tokyo** is a multiplayer web game where you play as a giant monster fighting for dominance over the city. Roll dice, buy ability cards, and battle other players to claim victory! 

This project is an implementation of the **King of Tokyo** board game (Richard Garfield, [IELLO](https://iellogames.com/games/king-of-tokyo/)), built in Python with the **Django** framework.


<img width="1917" height="866" alt="start" src="https://github.com/user-attachments/assets/c4351879-d98f-42a3-bafe-6e36f03024aa" />


<img width="1897" height="855" alt="gamestart" src="https://github.com/user-attachments/assets/7c33dea2-2f8a-4f44-b76a-40b89702fbbb" />


<img width="1890" height="857" alt="game" src="https://github.com/user-attachments/assets/6056ba8e-b5bb-412a-b78d-f61226b5ab1c" />



## Tech Stack

- Python
- Django
- SQLite
- HTML/CSS

## Game Rules (Summary)

**Note:** Detailed game rules and a complete manual are available directly on the website once you launch the game.

King of Tokyo is a game for 2–6 players.

### How to Win
 
There are two ways to win the game:
 
1. **Domination:** Be the first monster to reach **20 Victory Points**.
2. **Annihilation:** Reduce all other players' Health Points to **0** and be the last monster standing.
### Quick Rules & Mechanics
 
- **Roll the Dice:** On your turn, roll the dice up to 3 times. Keep the symbols you need and reroll the rest to plan your strategy.
- **Dice Actions:** Your final dice results allow you to score Victory Points (by rolling 1s, 2s, or 3s), **Attack** opponents, **Heal** your wounds, or collect **Energy** to purchase special ability cards.
- **The Rule of Tokyo:** The core of the game revolves around controlling Tokyo:
  - **Inside Tokyo:** You deal damage to *everyone* outside the city and earn bonus Victory Points just for being there. However, you **cannot heal**, and every monster outside is attacking *you*.
  - **Outside Tokyo:** You can safely heal your wounds, but your attacks only target the monster currently holding Tokyo. If you attack them, they might flee, forcing you to take their place!


## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/hylaj/King-Of-Tokyo.git
   cd King-Of-Tokyo
   ```

2. (Recommended) create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the development server:
   ```bash
   python manage.py runserver
   ```

5. Open in your browser:
   ```
   http://127.0.0.1:8000/
   ```
   
## Inspiration

https://iellogames.com/games/king-of-tokyo/
