# Ako Ang Bagyo Lyrics by ItsMeRiooooPH

A desktop lyric-animation experience built with Python. The app plays the
included audio track while lyric cards appear, type themselves out, alternate
between sides of the screen, rise upward, and flip colors.

## Features

- Animated lyric cards with a typewriter effect
- Smooth upward movement across the screen
- Alternating left and right card placement
- Automatic light/dark card color flips
- Synchronized background audio
- No external assets are required beyond the included MP3 file

## Requirements

- Python 3.10 or newer
- A desktop environment with Tkinter support
- The dependencies listed in [`requirements.txt`](./requirements.txt)

> **Windows note:** Standard Python installers usually include Tkinter. If
> Tkinter is unavailable, reinstall Python and enable the Tcl/Tk option.

## Installation

1. Clone the repository and open its folder:

   ```bash
   git clone https://github.com/ItsMeRioooo/SHEAN.git
   cd SHEAN
   ```

2. Create and activate a virtual environment (recommended):

   **Windows PowerShell**

   ```powershell
   py -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

   **macOS/Linux**

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Install the project dependency:

   ```bash
   python -m pip install -r requirements.txt
   ```

## Run

Run the application from the project directory so the bundled audio file can
be found:

```bash
python Ako_Ang_Bagyo.py
```

On Windows, `py Ako_Ang_Bagyo.py` can be used instead if `python` is not
available as a command.

The app minimizes its main window and displays the animated lyric cards over
the desktop. Close the lyric windows or stop the Python process to exit.

## Project structure

```text
.
├── Ako_Ang_Bagyo.py   # Application code
├── akoangbagyo.mp3    # Background audio
├── requirements.txt    # Python dependency list
└── README.md          # Project documentation
```

## Troubleshooting

### `ModuleNotFoundError: No module named 'pygame'`

Make sure the virtual environment is active, then reinstall the requirements:

```bash
python -m pip install -r requirements.txt
```

### The audio file cannot be found

Run the command from the repository directory and confirm that
`akoangbagyo.mp3` is beside `Ako_Ang_Bagyo.py`.

### No window or audio appears

Confirm that you are running the program in a desktop session with audio
enabled. This project is not intended for a headless server or terminal-only
environment.

## Contributing

Suggestions, improvements, and bug reports are welcome. Before opening a
change, please describe what was changed and how it was tested.

## Connect

- GitHub: [@ItsMeRioooo](https://github.com/ItsMeRioooo)
- TikTok: [@itsmeriooooph](https://www.tiktok.com/@itsmeriooooph)
- Support server: [Join the Discord server](https://discord.gg/ZDEXjYdSCd)

## License

This project is licensed under the [MIT License](./LICENSE).
