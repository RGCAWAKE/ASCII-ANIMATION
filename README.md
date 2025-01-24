# ANIMATIONASCII

## Description
`ANIMATIONASCII` is a Python-based program that converts GIFs into ASCII animations and displays them dynamically in a user-friendly GUI. Users can load a GIF, process it into ASCII art, and play the resulting animation with adjustable playback speed. The program ensures an engaging and visually interesting way to experience GIFs in text-based art.

---

## Features
- Load and process any GIF into ASCII art.
- Play ASCII animations with smooth frame transitions.
- Adjust playback speed using a slider.
- Clear the display and reset the program easily.
- Responsive interface that dynamically resizes to fit ASCII art.
- User-friendly GUI with help and about sections.

---

## Requirements
To run the program, you'll need:
1. Python 3.8 or later ([Download Python](https://www.python.org/downloads/))
2. Required Python libraries:
   - `Pillow` for image processing

Install the required library by running:
```bash
pip install pillow
```

---

## How to Run
1. **Download the Script**:
   Ensure you have the `ANIMATIONASCII.py` file.

2. **Run the Program**:
   Open a terminal or command prompt, navigate to the folder containing the file, and run:
   ```bash
   python ANIMATIONASCII.py
   ```

3. **Using the Program**:
   - **Select File**: Click to choose a GIF from your computer.
   - **Process File**: Convert the selected GIF into ASCII art.
   - **Play Animation**: View the ASCII animation.
   - **Adjust Speed**: Use the slider to change animation playback speed.
   - **Stop Animation**: Halt the playback anytime.
   - **Clear**: Reset the program to start fresh.

---

## How to Share
### For Users With Python Installed
1. Share the `ANIMATIONASCII.py` file.
2. Provide the installation command for Pillow:
   ```bash
   pip install pillow
   ```
3. Share the instructions to run the program:
   ```bash
   python ANIMATIONASCII.py
   ```

### For Users Without Python
Use **PyInstaller** to create a standalone executable:
1. Install PyInstaller:
   ```bash
   pip install pyinstaller
   ```
2. Generate the executable:
   ```bash
   pyinstaller --onefile ANIMATIONASCII.py
   ```
3. Share the executable file from the `dist` folder.

---

## License
This project is open-source and available for non-commercial use. Feel free to modify and share it, but please give credit to the original creator.

---

## Support
If you encounter any issues or have questions, feel free to reach out for help or suggestions!

