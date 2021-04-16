# prickly

Cross-platform TUI application for editing prc files.

## Installation:

- With cargo: `cargo install --git https://github.com/BenHall-7/prickly.git`

## Startup:

Possible options:

- Drag and drop a param file onto the prickly executable
- Set prickly to be the default program for .prc files
- Specify the file to open from the terminal in the app arguments
- Open the application and load the file manually with the file explorer

## Command shortcuts:

- `Ctrl + O`: open the file explorer for opening files
- `Ctrl + S`: open the file explorer for saving files
- `Enter`: Enter or edit a param node, or open a folder/file in the file explorer
- `Backspace`: Go to the parent param, or to the parent folder in the file explorer
- `Esc`: Exit the given prompt (param viewer, file explorer, inputs, etc)
- `/`: Begin typing a filter for params, or search for a file in the file explorer
  - NOTE: If the file explorer is in saving mode, pressing `Enter` will attempt to save with the given name
