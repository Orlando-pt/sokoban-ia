# iia-ia-sokoban
Sokoban clone for AI teaching

https://user-images.githubusercontent.com/60890452/161307167-5d4c3e15-c329-4e6c-a486-3c44d474e4fb.mp4

## How to install

Make sure you are running Python 3.5 or higher

1. Create a virtual environment (venv)
```bash
python3 -m venv venv
```

2. Activate the virtual environment (you need to repeat this step, and this step only, every time you start a new terminal/session):
```bash
source venv/bin/activate
```

3. Install the game requirements:
```bash
pip install -r requirements.txt
```

## How to run

open 3 terminals:

`$ python3 server.py`

`$ python3 viewer.py`

`$ python3 client.py`

to play using the sample client make sure the client pygame hidden window has focus

## Debug Installation

Make sure pygame is properly installed:

python -m pygame.examples.aliens

# Tested on:
- OSX 10.15.6
- Ubuntu 20.04

# Credits

Thank you [Kenney](https://www.kenney.nl/assets/sokoban) for the sprites.

Also, a huge thanks to [Diogo Gomes](https://github.com/dgomes) for the amazing IA lessons.

