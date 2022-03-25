# Maze_project
A simple Ray Casting 3D engine using SDL as the rendering back-end.

# <u>AUTHORS</u>
- Joseph Aboagye ... [Twitter](https://twitter.com/home?lang=en)
- Topister Onyango ... [LinkedIn](https://www.linkedin.com/in/topister-nandera-5930331a5/) 

## The goal of this project is to create a game in 3D using raycasting !
This was designed for kids so that it could improve their spatial recognition and analytical skills

## Keyboard Keys for Players
- `Arrow Keys` -- Player Directions 
- `R` -- Refresh 
- `M` -- Map 
- `C` -- Zoom Player view 
- `[` -- Zoom Out in Game 
- `]` -- Zoom In in Game 
- `F` -- Change Views (Normal view to Panoramic view and vice versa) 
- `T` -- Change Texture of walls and square columns 

### <u>Tools and Languages Used...</u>
- C language
- SDL2 (Simple Directmedia Layer)
- Ray-Casting
- Bash

## Compiling
Using a Windows Operating sysytem, Navigate to the `src` folder and Compile with 
`gcc -std=c17 *.c -I{Path to SDL2\include} -L{Path to SDL2\lib} -Wall -lmingw32 -lSDL2main -lSDL2 -o raycaster`
Check out [this link](https://www.matsson.com/prog/sdl2-mingw-w64-tutorial.php#:~:text=the%20gcc%20command.-,Step%202%3A%20Installing%20SDL2,library%20for%20Windows%20using%20MinGW.&text=After%20extracting%20the%20contents%20using,bit%20version%20of%20the%20library) for help.

Using Linux, Navigate to the `src` folder and Compile with
`gcc -o raycaster *.c 'sdl2-config --cflags --libs' -lm`
- Remove the line `#define SDL_MAIN_HANDLED` from the source codes in Linux

#### Most of the code inspiration were adopted from [DrDanick](https://github.com/drdanick)

### More modifications are underway. Explore and enjoy it!
