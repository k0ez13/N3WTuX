<p align="center">
  <a href="/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="MIT License"></a>
  <a><img src="https://img.shields.io/badge/OS-Linux-green.svg" alt="Linux"></a>
  <a><img src="https://img.shields.io/badge/Cheat-CS:GO-green.svg" alt="CS:GO cheat"></a>
  <a><img src="https://img.shields.io/badge/State-Maintained-green.svg" alt="Maintained"></a>
  <a><img src="https://img.shields.io/badge/Detection-Undetected-green.svg" alt="Detection: Undetected"></a>
  <a href="https://discord.gg/SCHsWHFJMb"><img src="https://img.shields.io/badge/Chat-Discord-blue.svg" alt="Discord"></a>
</p>

An open source training utility for Counter-Strike: Global Offensive on Linux.



## Current Features

### Features

 - Basic GDB injector
 - ImGui menu
 - ESP
 - Weapon ESP
 - Chicken/Fish ESP
 - Force square radar
 - Recoil crosshair
 - Rank revealer
 - Backtracking
 - Backtrack Chams
 - Flappy Bird clone
 - Legitbot
 - Hitmarkers
 - Nightmode
 - JumpBug
 - EdgeBug
 - Edge Jump


## How to use

### Debian / Ubuntu / Pop OS / Linux Mint required packages:

```sudo apt install -y libsdl2-dev cmake git gcc-10 g++-10 gdb clang```

### Arch / Manjaro required packages:

```sudo pacman -S --needed base-devel git cmake gdb sdl2 clang```

### Fedora required packages:

```sudo dnf install gcc-g++ gdb SDL2-devel cmake git clang```

### OpenSUSE required packages:

```sudo zypper install gcc gdb SDL2-devel cmake git llvm-clang llvm-gold```

```sh
git clone https://github.com/k0ez13/N3WTuX
cd N3WTuX
chmod +x toolbox.sh
./toolbox.sh -p -u -b -l # pull; unload cheat if currently injected, build and then load, use -h for help
```


## Basic toolbox.sh usage

| Argument           | Description                             |
| ------------------ | --------------------------------------- |
| -u (--unload)      | Unload the cheat from CS:GO if loaded   |
| -l (--load)        | Load/inject the cheat via gdb           |
| -ld (--load_debug) | Load/inject the cheat and debug via gdb |
| -b (--build)       | Build to the build/ dir                 |
| -bd (--build_debug)| Build to the build/ dir as debug        |
| -p (--pull)        | Update the cheat                        |
| -h (--help)        | Show help                               |

All args are executed in the order they are written in, for example, "-u -b -l" would unload the cheat, build it, and then load it back into csgo.

