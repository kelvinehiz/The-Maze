# The Maze

This project is an ALX portfolio project in partial fulfilment for specialization.

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D world!

The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

### About SDL2 

Simple DirectMedia Layer 2 (SDL2) is a cross-platform software development library used for multimedia applications, including games, emulators, and media players. It supports 2D graphics rendering with hardware acceleration, audio playback and recording, and input handling from various devices. SDL2 also offers multi-threading and window management. It is widely used for its performance, portability, and ease of use. SDL2 is open-source, licensed under the zlib license, allowing free use in both open-source and proprietary projects. This versatility makes it a popular choice for creating cross-platform multimedia applications.

## Instalation 
```sh
 git clone https://github.com/kelvinehiz/The-Maze.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart
![The Maze Flow Chart](https://i.imgur.com/t0MxNni.png)

## Demo
[![The Maze Demo](https://i.imgur.com/5Ss7s1S.png)](https://www.youtube.com/embed/6T2N8gNUTQ8)
