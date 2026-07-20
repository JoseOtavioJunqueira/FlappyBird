# Flappy Bird (Python)

A recreation of the classic Flappy Bird, built with Pygame to practice Object-Oriented Programming: encapsulated game entities, animation state, and simple physics (gravity, rotation, pixel-perfect collision via masks).

## Classes

- **Passaro** (Bird): the player-controlled character — handles jump physics, rotation, and wing animation.
- **Cano** (Pipe): the obstacles — spawns at a random height and detects collision with the bird via mask overlap.
- **Chao** (Ground): a looping scrolling ground.

## Tech Stack

- **Python** with **Pygame**

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/JoseOtavioJunqueira/flappy-bird-python.git
   cd flappy-bird-python
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the game:
   ```bash
   python main.py
   ```
   Press **Space** to flap.

## Project Structure

```
main.py       # Game entities (Passaro, Cano, Chao) and main loop
imagens/       # Sprites and backgrounds
```

## License

MIT — see [LICENSE](LICENSE).

## Contact

José Otávio — joseotavio.jr1104@gmail.com
