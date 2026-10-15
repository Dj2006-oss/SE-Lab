# Rock Paper Scissors Lab

This project is an interactive Rock Paper Scissors game built using **Python and Pygame**. The lab focuses on debugging, AI-assisted development, and implementing additional features to improve gameplay.

## Project Overview

The starter project contains a working Rock Paper Scissors game with a deliberate scoring bug and three additional features to implement. ChatGPT was used as a debugging and pair-programming assistant to analyze the code, correct the bug, and implement the required improvements.

## Tasks Completed

### Task 1: Fix the Inverted Outcome Evaluation Bug

Corrected the outcome evaluation logic so that the game follows standard Rock Paper Scissors rules:

- Rock beats Scissors.
- Scissors beats Paper.
- Paper beats Rock.
- Identical choices result in a draw.

The scoring logic was corrected so that points are awarded to the appropriate winner.

### Task 2: Implement First-to-5 Match Victory State

Implemented a first-to-5 match system. The game ends when either the player or the computer reaches five points. A match victory message is displayed, and the player can restart the game.

### Task 3: Implement Adaptive AI Pattern Tracking

Improved the computer opponent by tracking the player's recent moves and adapting its selections to counter frequently chosen options.

### Task 4: Implement Procedural Gesture Icons and Reveal Animations

Added visual gesture icons for Rock, Paper, and Scissors, along with a countdown and reveal sequence before displaying the selected moves.

## Technologies Used

- Python
- Pygame
- Git and GitHub
- ChatGPT for AI-assisted debugging and development

## Getting Started

### Prerequisites

- Python 3.10 or later
- Pygame

### Installation

1. Clone the game repository:

   ```bash
   git clone https://github.com/Dj2006-oss/59_rock_paper_scissor.git
   ```

2. Navigate to the project directory:

   ```bash
   cd 59_rock_paper_scissor
   ```

3. Install Pygame:

   ```bash
   pip install pygame
   ```

4. Run the game:

   ```bash
   python main.py
   ```

## Source Code

The complete game source code is available in the following GitHub repository:

**[Rock Paper Scissors – Game Repository](https://github.com/Dj2006-oss/59_rock_paper_scissor)**

## Project Structure

```text
59_rock_paper_scissor/
├── game/
│   ├── button.py
│   └── game_engine.py
├── main.py
└── README.md
```

## Submission Checklist

The assignment requires the following three items:

- [ ] **Before Gameplay Video:** A 10-second video showing the original bug or broken behavior before the changes.
- [ ] **After Gameplay Video:** A 10-second video demonstrating the corrected scoring and newly implemented features.
- [ ] **Complete Chat History:** A shareable link to the ChatGPT conversation containing the complete chat history used during the lab.

## Conclusion

This project demonstrates debugging an existing Python game, implementing a match victory condition, improving computer decision-making through adaptive AI, and enhancing gameplay with gesture icons and reveal animations.
