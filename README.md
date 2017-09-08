# The snake game

I was watching a C++ tutorial about **ncurses** and decided to publish
the tutorial code on github. You can follow the same tutorial on Youtube,
https://www.youtube.com/watch?v=4HgyStstIhw.


## Getting ncurses

```sh
sudo pacman -S ncurses
```


## Getting snake-ncurses source

```sh
git clone git@github.com:fabiomontefuscolo/snake-ncurse.git
```


## Compiling snake-ncurse

```sh
cd snake-ncurse
g++ snake.cpp main.cpp -o snake -lncurses
```


## Running it

```sh
./snake
```

