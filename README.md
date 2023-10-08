# tygoee/code

Just some small coding projects

These are some files that I made earlier on, or they were too small to make a repository. You are free to copy any of these contents without any mention, unless stated otherwise.

Some of these files moved to their own repository, and here you can see their early progress. Most old projects were uploaded with some differences in like formatting and type checking.

## Current projects

- bash/monitors.sh - Used to setup my monitors with Xorg
- bash/local_install.sh - Install apt packages locally, moved to [tygoee/papt](https://github.com/tygoee/papt)
- brainfck/helloworld.bf - Just hello world in brainfck, because I was curious
- cpp/tutorials/ - Tutorials I followed when starting with C++
- cpp/game/ - I was trying trying to make a game with some friends, later deleted it ([tygoee/ww3game](#))
- python/getimages/ - My first 'big' project: getting images from a online book viewer and constructing a pdf
- python/wrds/ - A pretty little terminal project for practicing words, inspired by [https://wrts.nl](https://studygo.com/nl/)

## Running code

Most projects are run pretty intuitively, but here are some instructions:

First, of course, clone the git repo:

    git clone https://github.com/tygoee/code

### Bash

If you have linux (or macos?) installed, cd into the directory, give the file execute permissions and run the file:

    cd bash/(directory)
    chmod +x file.sh
    ./file.sh

If you have windows, install WSL and do the same.

### Brainfck

Install a [Brainfck interpreter](https://github.com/pocmo/Python-Brainfuck) and run the file:

    git clone https://github.com/pocmo/Python-Brainfuck
    cd Python-Brainfuck
    mkdir -p ~/.local/bin/
    cp -t ~/.local/bin/ brainfuck.py getch.py

    cd brainfck/(directory)
    brainfuck file.bf

### C++

Install [gcc/g++](https://gcc.gnu.org/) and run the file with `g++ file.cpp`. Files here don't contain any imports or libraries, so you don't need any flags to include libraries or other files. Note that some files I made are Windows-only, because they use standard headers like `conio.h`.

### Python

Assuming you have [Python](https://www.python.org/) installed, cd into the folder, make a virtual environment and install `requirements.txt`:

    cd python/(directory)
    python3 -m venv .venv
    source .venv/bin/activate
    pip3 install -r requirements.txt

Then, just run the main python file with `python3 file.py`

---

(c) Tygo Everts <br>
This code is licensed under the Unlicense, <br>
you can do anything you want with it.
