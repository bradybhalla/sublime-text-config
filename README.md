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
- Terminal
  - Open iTerm
- Terminus
  - Terminal in Sublime Text
  - Set up to use powerlevel10k and tmux
  - May need to put "Terminus Utilities: Generate User Theme" in Command Palette to fix formatting

### Additional Keybinds
- ``Option + ` ``: Open Terminus panel
- ``Option + Shift + ` ``: Open Terminus view
- `Option + F`: Format file (using LSP)
- `Option + I`: Hover for LSP information
- `Option + E`: Jump to next LSP diagnostic
- `Option + Shift + E`: Code action (quick fixes for diagnostic)

### Additional Builds
- LaTeX
  - Using `pdflatex`
- Markdown
  - Using `pandoc` (which must be installed through Homebrew for this build)

### Additional Snippets
- Snippets for accelerating LaTeX writing