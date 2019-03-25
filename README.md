# heart.py

Draws a fancy heart in the terminal.  Made for the [Esoteric Python
Challenge 5](https://github.com/python-discord/esoteric-python-challenges/tree/master/challenges/05-text-hearts).

## What you need

- Python 3.6 (f-strings used in the code)
- PIL(low)
- `DejaVuSans.ttf` somewhere in the system
- a 256-colour terminal
- a decent unicode font with emoji and Japanese characters

## How to run

```
% ./heart.py [size] [preset]
```

The parameters can be omitted -- size defaults to 24 and preset is
chosen randomly from the available ones -- `matrix`, `shades`,
`ascii`, `pink`, `emoji`, `lipsum`, `japanese`.

## How does it work

The code uses PIL(low) to render a heart emoji (`"\u2665"`, ♥) on the
text terminal.  Seven fancy presets are predefined to make the output
visually appealing.
