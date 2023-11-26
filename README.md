# talon-contractions

TalonScript file, *contractions.talon*, that contains the expansions of common contractions in English.
These are automatically expanded in the [Talon Voice](https://talonvoice.com/docs/index.html) when used in the dictation mode. 
Voice In is a open source project that is wrapped with Python and that is highly customizable via either TalonScript or Python scripts.

I grew tried of correcting contractions manually. 
This file saves a lot of time during the editing phase.

## Installation

Store *contractions.talon* inside `~/.talon/users/<whatever>/`.
The subfolder <whatever> can have any name and is optional.
Talon Voice will automatically detect this file and all others inside `~/.talon/users/` without restarting Talon Voice.

You can add more contractions by using a text editor.
The *contractions.talon* file is a plain text file written in TalonScript which is a subset of Python.
