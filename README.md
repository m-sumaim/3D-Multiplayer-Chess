# 3D Chess Game

This project is about chess game in 3D mode. Chess is a two-player strategy board game on a checkered board with 8x8 grid dimension. There is two player on each game which the first player as *White* and the second player as *Black*. 

![](chess-game-demo.gif)

## Getting started
To use this repository, you will need:
- C++
- FreeGLUT

## Usage
- Clone this repository
```
git clone https://github.com/m-sumaim/3D-Multiplayer-Chess
```
- Compile C++ source code files
- Run the executable

### How to build and run on Linux

```bash
# build
mkdir -p bin && g++ main.cpp Model.cpp Chess/*.cpp `pkgconf --libs glut gl glu` -o bin/3d-chess-opengl

# run
bin/3d-chess-opengl
```


## Game Control
|Key|Action|
|:---:|:---:|
|`N`|Start new game|
|`W`|Move cursor forward 1 step|
|`A`|Move cursor left 1 step|
|`S`|Move cursor backward 1 step|
|`D`|Move cursor right 1 step|
|`Space`|Select piece<br>Move piece<br>Cancel move|
|`O`|Approve `start new game`|
|`X`|Close game after `checkmate`<br>Cancel `start new game`|
|`Q`|Promote to `Queen`|
|`R`|Promote to `Rook`|
|`B`|Promote to `Bishop`|
|`K`|Promote to `Knight`|

