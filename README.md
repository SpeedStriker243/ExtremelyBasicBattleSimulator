# Extremely Basic Battle Simulator
An extremely basic battle simulator I did for college. It's pretty terrible.

## What the hell is this?
I had to make a game for college. In C++. I was originally gonna reuse my [`playerobject` project](https://github.com/SpeedStriker243/playerobject), but that was done in Python, and the requirements asked for C++ in particular, so I had to come up with something on my own.
Based off of my aforementioned project, but fundamentally different, this project was intended to be an RPG game. Since I **really** suck at C++, and considering the deadline, it's now *Extremely Basic Battle Simulator*, obviously ~~ripping off~~ inspired by the title of Landfall Games' *Totally Accurate Battle Simulator*.

## Extremely basic?
Yeah, you heard me. This consists of **one C++ program** that works via command-line. It also uses cross-platform stuff, so you can compile and run it with basically anything that supports C++11.

## How do I play this?
Compiling is super easy. 

### For the experienced programmer
On Linux and macOS, you should be able to run `g++` from the command line.
On Windows, you should probably install [MinGW](http://www.mingw.org/). See [here](https://courses.cs.washington.edu/courses/cse373/99au/unix/g++.html) for a tutorial on using `g++`.

### For the less experienced
If you just wanna run the code without the hassle of using the command line, you can use a website like [cpp.sh](http://www.cpp.sh/) and paste the [source code](https://github.com/SpeedStriker243/ExtremelyBasicBattleSimulator/blob/master/main.cpp) in there. 

### For people who are completely clueless
If you can't even do *that*, you can run the code at [repl.it](https://repl.it/@SpeedStriker243/ExtremelyBasicBattleSimulator).

### Bruh
Seriously? Too lazy to click a link? Alright, fine, I'll show you some output...
```
SpeedX243 challenges Enemy to a fight!

SpeedX243 attacks! Dealt 50 points of damage!
Enemy received 50 points of damage! Enemy now has 100 points of health!

Enemy attacks! Dealt 20 points of damage!
SpeedX243 received 20 points of damage! SpeedX243 now has 100 points of health!

SpeedX243 attacks! Dealt 50 points of damage!
Enemy received 50 points of damage! Enemy now has 50 points of health!

Enemy attacks! Dealt 20 points of damage!
SpeedX243 received 20 points of damage! SpeedX243 now has 80 points of health!

Enemy has been defeated! Victory!
```
