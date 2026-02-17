# Soyfetch

neofetch with soyjaks GEEEEEEEEEEEEEEG

fork of hyfetch, made to make a lot of the brimmy things there into gems

## Installation

compile from source, i VVILL update the python version to be feature compliant to the rust version so you dont have to use rust geg.
i might port the rust shit to c/c++ since c/c++ are both aryan and no rust being used anymore geg

## Usage

When you run `hyfetch` for the first time, it will prompt you to choose a color system and a preset. Just follow the prompt, and everything should work (hopefully). If something doesn't work, feel free to submit an issue!

no LGBT flags geeeeeg, just american flag and indian flag for right now geg
arch's distro logo is replaced with a troonjak as of right now, will likely add more 'jaks for logos.

## Questions and answers

#### Q: How do I change my config?

A: Use `hyfetch -c`

#### Q: What do I do if the color is too dark/light for my theme?

A: You can try setting the colors' "lightness" in the configuration menu. The value should be between 0 and 1. For example, if you are using dark theme and the rainbow flag is too dark to display, you can set lightness to 0.7.

Feel free to experiment with it!

![image](https://user-images.githubusercontent.com/22280294/162614553-eb758e4e-1936-472c-8ca7-b601c696c6eb.png)

#### Q: Why do you use pride flag's coloring? I don't think it looks nice at all.

A: blah blah we dont have that anymore at soyfetch geg

#### Q: When I use `hyfetch` or `neowofetch` in my MotD, no art displays. How do I get the art back?

A: Most likely, the `stdout` detection is set to auto and is removing the ascii art and colors. To change this, you can: set `args` in your hyfetch.json to `"--stdout=off"`, add `--stdout=off` to the `neowofetch` command in your motd script, or set the option in $HOME/.config/(neofetch|neowofetch)/config.conf to off.

#### Q: How can I run Soyfetch on Windows?

A: compile it as a wheel for the python version geg, you need every dependency


## Contributing

To make changes to our codebase, you first need to create a fork by clicking the "Fork" button on the top right. Then, you can clone your fork of the source code using `git clone https://github.com/{your username}/hyfetch.git`.

After making changes to the source code, you can run `python -m hyfetch` in the root directory of your repo to test out your changes.

If they work correctly, you can commit and push these changes using git command or Github Desktop. Then, you can create a pull request on Github so that it can go into our next release!

You can also install your version locally by running `pip install .` in the repo root.
