# 🏓 Hand-Tracking Pong Game

A fun and interactive **2-player Ping Pong game** powered by real-time **hand tracking** using your webcam! 🖐️

No controllers needed — just use your **hands as paddles** and battle it out with a friend.

![Demo](./Resorces/pingpong-ezgif.com-optimize.gif)
---

## 🎮 Features

- 🖐️ Real-time dual hand tracking (Left & Right players)
- 🏓 Smooth paddle control using hand movements
- 🎯 Ball collision detection and bounce mechanics
- 🧠 Score system and game over screen
- 🔁 Reset and restart functionality
- 🖼️ Mini camera preview during gameplay

---

## 🧰 Tech Stack

- **Python**
- **OpenCV** – Video capture and image processing
- **cvzone** – Hand tracking and image overlay
- **MediaPipe** – Real-time hand tracking
- **NumPy** – Numerical operations

---

## 📂 Folder Structure

📁 Resources/<br>
├── `Background.png` – Main game background <br>
├── `Ball.png` – Transparent ball image <br>
├── `bat1.png` – Player 1 (Left) paddle image <br>
├── `bat2.png` – Player 2 (Right) paddle image <br>
├── `gameOver.png` – Game over screen image <br>

📄 `pingpong.py` – Main game script

---

## 🚀 How to Run

1. **Clone this repo** or download the code.
2. Install required dependencies:

```bash
pip install opencv-python cvzone numpy
```

3. Make sure all images are placed inside a folder named Resources/.

4. Run the game:

```bash
python pingpong.py
```
---

## 🕹️ Controls
| Key   | Action           |
|-------|------------------|
| `r`   | Restart the game |
| `Esc` | Quit the game    |

---


## ✋ Hand Gestures
| Hand       | Action                    |
|------------|---------------------------|
| ✋ Left     | Controls Player 1 paddle  |
| ✋ Right    | Controls Player 2 paddle  |

Move your hand up and down to hit the ball. Keep it in bounds to score!

---

## 📸 Screenshots
<!-- Add gameplay screenshots here -->
<br>

---

## 🤝 Credits
- cvzone by Murtaza’s Workshop

- MediaPipe – Hand Tracking by Google

- Sound effects and assets – Free online resources
