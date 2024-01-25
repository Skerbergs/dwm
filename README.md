# dwm
## About
dwm is a dynamic window manager for X. It manages windows in tiled, monocle and floating layouts. All of the layouts can be applied dynamically, optimising the environment for the application in use and the task performed.

This is the custom setup of dwm I use on my FreeBSD computer.
## Switching themes
At the start of config.def.h, include your desired theme from the themes folder. After that comment out the following lines:
```C
static const char col_gray1[]       = "#222222";
static const char col_gray2[]       = "#444444";
static const char col_gray3[]       = "#bbbbbb";
static const char col_gray4[]       = "#eeeeee";
static const char col_cyan[]        = "#005577";
```
