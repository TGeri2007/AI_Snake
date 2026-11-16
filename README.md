# AI_Snake

A classic Snake game for the web. Pure HTML, CSS and JavaScript, no build step.

## Run

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Controls

- Move: arrow keys or W / A / S / D (swipe or on-screen arrows on touch devices)
- Pause / resume: Space or P
- Restart: R
- Eat food to grow and earn 10 points; the snake speeds up as it grows.
- Every 15 seconds a spiky ball arrives at least 5 cells away from you. A red warning marker appears 1.5 seconds before it lands. Touching the ball kills you. Each ball stays for one minute, so several can be on the board at once.
- The best score is saved in your browser's local storage.
