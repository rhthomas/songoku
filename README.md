# songoku

### [v 0.1](https://www.youtube.com/watch?v=H4L9yENEQbI)
Working release

## Installation

(Optional) Setup a virtual environment to install the necessary packages.

```bash
virtualenv venv
source venv/bin/activate
```

Install the packages listed in the requirements file.

```bash
pip install -r requirements.txt
```

Run the application.

```bash
python camera.py
```

## TODO

- [x] Guess numbers every 10 frames (it still grabs every frame of video).
- [ ] Complete README.md.
- [ ] Create `main.py` file, rather than having to run `camera.py` (unclear that this is main until reading the source).
- [ ] Make numbers less shaky (better contour grabbing?).
- [ ] Make it so it only guesses the numbers every ~20 frames? Maybe guesses them really fast at the beginning and once it has it figured out it slows down.
