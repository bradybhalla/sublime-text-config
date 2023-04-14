# sublime-text-config

## Setup Instructions
1) Move the contents of this repository to the `User` folder.  On macOS, this is probably located at `~/Library/Application\ Support/Sublime\ Text/Packages/User`.
2) Open the command palette (`Cmd + Shift + P`) and type `Install Package Control` if Package Control is not already installed.
3) Restart Sublime Text.

Note: This will overwrite the current preferences and packages.

## Configuration

### Syntax specific configs
#### LaTeX
- "LaTeX" build system to compile and view pdf
  - Uses `pdflatex`
- Keybinds to make writing more natural ([LaTeX/Default.sublime-keymap](LaTeX/Default.sublime-keymap))
- Additional snippets ([LaTeX/Snippets](LaTeX/Snippets))

#### Markdown
- "Markdown" build system to compile and view HTML
  - Uses `pandoc` (installed with Homebrew)
  - Nicely styled page
  - Code can be copied by clicking
  - Deletes HTML after build
- Color scheme to make headers more visible

### Packages
- LSP (with various languages)
- Terminus
  - Terminal in Sublime Text
  - Set up to use powerlevel10k and tmux
  - May need to run "Terminus Utilities: Generate User Theme" in Command Palette to fix formatting
- sublime-matrix-calculator
  - I made it!
- Color Highlight
- AutoFoldCode
  - Store folded code and selections
- *see all packages in* [Package Control.sublime-settings](Package%20Control.sublime-settings)

### Keybinds
- Terminus, LSP, and more
- *see all keybinds in* [Default (OSX).sublime-keymap](Default%20(OSX).sublime-keymap)

### Other notes
- Additional layouts
  - View $\to$ Layout $\to$ Rotated Face
- Various syntax specific modifications
- Tab for autocomplete
- Made for macOS
