# sublime-text-config

## Setup instructions
1) Move the contents of this repository to the `User` folder.  On macOS, this is probably located at `~/Library/Application\ Support/Sublime\ Text/Packages/User`.
2) Open the command palette (`Cmd + Shift + P`) and type `Install Package Control` if Package Control is not already installed.
3) Restart Sublime Text.

Note: This will overwrite the current preferences and packages.

## Configuration

### Packages
- 0x0
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
- sublime-matrix-calculator (I made it!)
- Terminal

### Additional Keybinds
- `Cmd + I`: Hover for LSP information
- `Cmd + E`: Jump to next LSP diagnostic
- `Cmd + Shift + E`: Code action (quick fixes for diagnostic)
- `Option + F`: Format file (using LSP)

### Additional Builds
- Compile LaTeX
- npm run dev

### Additional Snippets
- Snippets for accelerating my LaTeX writing