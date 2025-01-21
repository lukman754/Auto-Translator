# Automatic Translator

Auto Translator is a powerful desktop application that provides real-time text translation with automatic language detection. This allows users to quickly translate selected text in various applications using keyboard shortcuts.
![image](https://github.com/user-attachments/assets/ef0748cc-bb30-49c7-af08-e60c58ec3dcf)

## Demo
https://github.com/user-attachments/assets/215b9c0a-a45c-431d-968e-0853188d7e89




## Feature

- **Real Time Translation**: Translate text instantly from any app
- **Automatic Language Detection**: Automatically detects the source language of the selected text
- **Smart Language Switching**: Automatically switches languages ​​when necessary to ensure optimal translation
- **Keyboard Shortcuts**: Quick translation using convenient hotkeys
- **Interactive UI**: User friendly interface with:
  - Language selection dropdown with search capability
  - Real time translation preview
  - Activity log
  - Display of original and translated text

## Condition

-Python 3.x
- Required Python packages:
  - tkinter
  - keyboard
  - pipe clamp
  - Googletrans
  - input

## Use

1. Run the program:
2. Select your desired source and target languages ​​from the dropdown menu
3. Use the following keyboard shortcut:
   - `Ctrl + Space`: Translate selected text
   - `Ctrl + Shift + Space`: Switches source and target languages
   - `Ctrl + Shift + Q`: Exit the program

## How It Works

1. **Language Selection**:
   - Select source and target languages ​​from the drop-down menu
   - Search function available in dropdown
   - Automatic prevention of selecting the same language for source and target

2. **Translation Process**:
   - Select text in any app
   - Press the translation shortcut key
   - Program automatically:
     - Copy selected text
     - Detect source language
     - Translate text
     - Replaces selected text with its translation
     - Retains original text in clipboard

3. **Smart Features**:
   - Automatic language detection
   - Smart language switching when the detected language matches the target
   - Search language options as you type
   - Activity logging for tracking operations

## User Interface

The interface consists of:
1. **Language Settings**:
   - Source language dropdown
   - Target language dropdown
   - Language switch button

2. **Translation View**:
   - Original text panel
   - Translated text panel

3. **Activity Notes**:
   - Real-time recording of operations
   - Error reporting
   - Language detection information

4. **Usage Guide**:
   - Quick reference for keyboard shortcuts
   - Basic usage instructions

## Technical Notes

- Uses Google Translate API via `googletrans` library
- Implemented keyboard event handling using `pynput` and `keyboard` libraries
- Handle clipboard operations with `pyperclip`
- Built with `tkinter` for graphical interface
- Includes smart language detection and automatic switching logic

## Known Limitations

- Depends on Google Translate API availability
- May require administrator rights for global keyboard shortcuts
- Text formatting (bold, italic, etc.) is not preserved in translation
