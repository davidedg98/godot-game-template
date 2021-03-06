# Godot Game Template

WARNING: currently Work in Progress and not ready to be used. 

Opinionated game template for quick development.

## Features

- Mouse, keyboard and joypad support for the GUI elements
- Game pause / unpause handling
- Main menu
- `change_scene(scene, params)` function to handle transitions with fade-in/out and input prevention
- project structure: lowercase letters only for file system paths
  - `scenes/`, `entities`
- Continuos Integration:
  - Automatic desktop build (linux, windows, osx, HTML5) for each commit
  - Automatic HTML5 publish to Github pages for each commit
- `.gitignore`

## Lower case letters only

To avoid issues when multiple contributors are working on the same project across various
file systems and operating systems.


**Explanation**  
Usually on Windows `player.png` and `PLAYER.png` represents the same file.

This is not true for case-sensitive file systems like ext4.

- https://en.wikipedia.org/wiki/Filename#Letter_case_preservation
- https://en.wikipedia.org/wiki/Filename#Comparison_of_filename_limitations 
- https://docs.godotengine.org/en/stable/getting_started/step_by_step/filesystem.html#drawbacks

## Thanks

- https://github.com/aBARICHELLO/godot-ci
