![Version](https://img.shields.io/static/v1?label=talon-contractions=0.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# talon-contractions: Automatically expand English contractions

## Purpose
TalonScript file, *contractions.talon*, contains the expansions of common contractions in English.
These contractions are automatically expanded in the [Talon Voice](https://talonvoice.com/docs/index.html) when used in the dictation mode. 
Voice In is an open-source project wrapped in Python that is highly customizable via TalonScript or Python scripts.

I do not use contractions in my writing, although I do use them frequently in my speech.
I grew tired of correcting contractions manually. 
This file eliminates that task.

## Disclaimer
This is a programming tool, not an educational tool.
It provides no explanations and no context.


## Installation
Store *contractions.talon* inside `~/.talon/users/<whatever>/`.
The subfolder <whatever> can have any name and is optional.
Talon Voice will automatically detect this file and all others inside `~/.talon/users/` without restarting Talon Voice.

You can add more contractions by using a text editor.
The *contractions.talon* file is a plain text file written in TalonScript, a Python subset.

## Contributing new contractions

If you find a contraction(s) that should be added to this file, please open an issue above.
