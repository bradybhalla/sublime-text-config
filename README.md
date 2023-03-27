# sublime-text-config

## Setup instructions
1) Move the contents of this repository to the `User` folder.  On macOS, this is probably located at `~/Library/Application\ Support/Sublime\ Text/Packages/User`.
2) Open the command palette (`Cmd + Shift + P`) and type `Install Package Control` if Package Control is not already installed.
3) Restart Sublime Text.

Note: This will overwrite the current preferences and packages.

## Configuration

### Packages
- 0x0
  -  Quickly share code
- AutoFoldCode
- Git
- LSP
- LSP-pylsp
- LSP-TexLab
- LSP-typescript
- Open Finder
- Package Control
- Python3
- Sass
- sublime-matrix-calculator
  - I made it!
- Terminus
  - Terminal in Sublime Text
  - Set up to use powerlevel10k and tmux
  - May need to put "Terminus Utilities: Generate User Theme" in Command Palette to fix formatting

### Keybinds
- Terminus
  - ``Option + ` ``: Open panel
  - ``Option + Shift + ` ``: Open view
  - `Option + Up` / `Option + Down`: Bring to view/panel
- LSP
  - `Option + F`: Format file
  - `Command + I`: Simulate hover
  - `Command + E`: Jump to next diagnostic
  - `Command + Shift + E`: Code action (quick fixes for diagnostic)

### Builds
- LaTeX
  - Using `pdflatex`
- Markdown
  - Using `pandoc` (which must be installed through Homebrew)

### Snippets
- Snippets for accelerating LaTeX writing

### Menu items
- Additional layouts
  - View -> Layout -> Rotated Face `Command + Option + 5`