# 8-Puzzle Search Lab

A single-file, browser-based 8-puzzle used as a class exercise in problem
formulation (AIMA §3.2): every move updates the state tuple, the applicable
actions, RESULT(s,a), the goal test and the path cost. A built-in search lab
runs breadth-first, greedy best-first and A* (with the misplaced-tile and
Manhattan heuristics) on the current state and reports measured node counts.

No build step and no dependencies to install — `index.html` is the whole app.

## Publishing with GitHub Pages

1. Push this folder to a public repository.
2. Settings → Pages → Build and deployment → Source: *Deploy from a branch*,
   branch `main`, folder `/ (root)`.
3. Wait a minute, then open `https://<user>.github.io/<repo>/`.

The "Project QR code" button then encodes that address, so students can scan it
from the projector and play on their phones.
