# Jetbrains Themofia Theme
JetBrains Themofia Theme: A serene color scheme &amp; keymap for JetBrains IDEs. Elevate your coding with stylish visuals &amp; efficient keybindings.

# Themofia Keymap Documentation

The Themofia keymap is a color scheme configuration used to define the visual appearance of code and console output in an integrated development environment (IDE). This documentation provides an overview of the keymap's structure and its associated color attributes.

## Scheme Information

- **Scheme Name:** Themofia
- **Version:** 142
- **Parent Scheme:** Darcula

### Meta Information

- **Created:** 2022-07-27
- **IDE:** WebStorm
- **IDE Version:** 2022.1.3.0.0
- **Modified:** 2022-08-29
- **Original Scheme:** Themofia

## Global Options

The Themofia keymap includes various global options that affect the overall appearance of the IDE.

- **FONT_SCALE:** 1.0
- **LINE_SPACING:** 1.2
- **EDITOR_FONT_SIZE:** 18
- **EDITOR_FONT_NAME:** Operator Mono
- **EDITOR_LIGATURES:** true
- **CONSOLE_FONT_NAME:** Operator Mono
- **CONSOLE_FONT_SIZE:** 16

## Console Colors

The console colors define the background and foreground colors for different types of console output.

- **CONSOLE_BACKGROUND_KEY:** 1d2021
- **CONSOLE_FOREGROUND_KEY:** a89984

## Console Attributes

The console attributes section defines the background colors for various types of console outputs.

- **CONSOLE_BLACK_OUTPUT:**
  - **BACKGROUND:** 1d2021

- **CONSOLE_BLUE_BRIGHT_OUTPUT:**
  - **BACKGROUND:** d6678

- **CONSOLE_BLUE_OUTPUT:**
  - **BACKGROUND:** d6678

- **CONSOLE_CYAN_BRIGHT_OUTPUT:**
  - **BACKGROUND:** 8ba59b

- **CONSOLE_CYAN_OUTPUT:**
  - **BACKGROUND:** 8ba59b

- **CONSOLE_DARKGRAY_OUTPUT:**
  - **BACKGROUND:** 665c54

- **CONSOLE_GRAY_OUTPUT:**
  - **BACKGROUND:** a89984

- **CONSOLE_GREEN_BRIGHT_OUTPUT:**
  - **BACKGROUND:** 95c085

- **CONSOLE_GREEN_OUTPUT:**
  - **BACKGROUND:** 95c085

- **CONSOLE_MAGENTA_BRIGHT_OUTPUT:**
  - **BACKGROUND:** 8f4673

- **CONSOLE_MAGENTA_OUTPUT:**
  - **BACKGROUND:** 8f4673

- **CONSOLE_RED_BRIGHT_OUTPUT:**
  - **BACKGROUND:** fb543f

- **CONSOLE_RED_OUTPUT:**
  - **BACKGROUND:** fb543f

- **CONSOLE_WHITE_OUTPUT:**
  - **BACKGROUND:** fdf4c1

- **CONSOLE_YELLOW_BRIGHT_OUTPUT:**
  - **BACKGROUND:** fac03b

- **CONSOLE_YELLOW_OUTPUT:**
  - **BACKGROUND:** fac03b

## Terminal Command Colors

The colors for terminal commands that are run using the IDE are defined in this section.

- **TERMINAL_COMMAND_TO_RUN_USING_IDE:**
  - **FOREGROUND:** a89984
  - **BACKGROUND:** 1d2021

## Text Colors

The text colors section defines the appearance of text within the IDE.

- **TEXT:**
  - **FOREGROUND:** a9b7c6
  - **BACKGROUND:** 2b2b2b
  - **FONT_TYPE:** 2
  - **EFFECT_TYPE:** 5

## Conclusion

The Themofia keymap is a color scheme configuration that offers a distinctive visual style for code and console output in the WebStorm IDE. By customizing the various color attributes, developers can create a personalized coding environment that aligns with their preferences and enhances their coding experience.

# Themofia Keymap Keybindings Documentation

The Themofia keymap provides a set of keybindings for various actions within the integrated development environment (IDE). These keybindings enhance productivity by allowing developers to quickly perform common tasks. Below is a list of keybindings and their associated actions in the Themofia keymap.

## Basic Editing

- **Undo:** `Ctrl + Z`
- **Move to Next Change in Changes View:** `Not specified`
- **Close Active Content (Tab/Editor):** `Ctrl + F4`, `Ctrl + W`

## Code Navigation and Manipulation

- **Show Code Inspections on Editor:** `Not specified`
- **Backspace (Delete Previous Character):** `Backspace`
- **Delete (Delete Next Character):** `Delete`, `Shift + Backspace`
- **Delete Line:** `Ctrl + Y`, `Alt + Backspace`
- **Move Cursor Down:** `Down Arrow`, `Alt + Comma`
- **Move Cursor Down with Selection:** `Shift + Down Arrow`, `Shift + Alt + Comma`
- **Join Lines:** `Not specified`
- **Move Cursor Left:** `Left Arrow`, `Alt + J`
- **Move Cursor Left with Selection:** `Shift + Left Arrow`, `Shift + Alt + J`
- **Move Cursor to Line End:** `End`, `Alt + Quote`
- **Move Cursor to Line End with Selection:** `Shift + End`, `Shift + Alt + Quote`
- **Move Cursor to Line Start:** `Home`, `Alt + H`
- **Move Cursor to Line Start with Selection:** `Shift + Home`, `Shift + Alt + H`
- **Match Brace:** `Ctrl + H`, `Alt + M`
- **Move to Next Word:** `Ctrl + Right Arrow`, `Ctrl + L`
- **Move to Next Word with Selection:** `Shift + Ctrl + Right Arrow`, `Shift + Ctrl + L`
- **Move to Previous Word:** `Ctrl + Left Arrow`, `Ctrl + J`
- **Move to Previous Word with Selection:** `Shift + Ctrl + Left Arrow`, `Shift + Ctrl + J`
- **Move Cursor Right:** `Right Arrow`, `Alt + L`
- **Move Cursor Right with Selection:** `Shift + Right Arrow`, `Shift + Alt + L`
- **Scroll Down:** `Ctrl + Down Arrow`, `Ctrl + Comma`
- **Scroll Up:** `Ctrl + Up Arrow`, `Ctrl + I`
- **Select Word at Cursor:** `Ctrl + O`
- **Move Cursor Up:** `Up Arrow`, `Alt + I`
- **Move Cursor Up with Selection:** `Shift + Up Arrow`, `Shift + Alt + I`

## File and Project Navigation

- **Toggle Path Display in File Chooser:** `Not specified`

## Search and Find

- **Find Next:** `F3`
- **Find Previous:** `Shift + F3`

## Code Generation

- **Generate Missing Members (ES6 Syntax):** `Not specified`
- **Generate Missing Members (TypeScript Syntax):** `Not specified`
- **Implement Methods:** `Not specified`
- **Insert Live Template:** `Not specified`
- **Move Statement Down:** `Shift + Ctrl + Down Arrow`, `Shift + Ctrl + M`, `Shift + Ctrl + Comma`
- **Move Statement Up:** `Shift + Ctrl + Up Arrow`, `Shift + Ctrl + I`
- **Override Methods:** `Not specified`

## Code Analysis and Tools

- **Show Parameter Info (Tooltip):** `Not specified`
- **Show Popup Menu (Select Next Item):** `Down Arrow`, `Alt + Comma`
- **Quick Implementations:** `Not specified`
- **Select Next Occurrence:** `Ctrl + P`
- **Clear Terminal Buffer:** `Not specified`
- **Navigate to Type Hierarchy:** `Not specified`
- **Navigate to Base Type in Type Hierarchy:** `Not specified`
- **Unselect Previous Occurrence:** `Not specified`
- **Filter Usages by Imports:** `Not specified`
- **Filter Usages by Write Access:** `Not specified`
- **Focus Text Filter in Version Control Log:** `Not specified`
- **Move Changed Lines to Changelist in VCS:** `Not specified`
- **Toggle Amend Commit Mode in VCS:** `Not specified`
- **Load Context:** `Not specified`
- **Toggle Italic Styling in Markdown:** `Not specified`

Please note that some actions might not have default keybindings assigned in the Themofia keymap. You can customize and assign keybindings according to your preference using your IDE's settings.