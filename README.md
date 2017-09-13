# A-Guide-to-DeepMind-s-StarCraft-AI-Environment-
This is the code for "A Guide to DeepMind's StarCraft AI Environment" by Siraj Raval on Youtube

## Overview

This is the code for [this](https://youtu.be/URWXG5jRB-A) video on on Youtube by Siraj Raval. This code will help you train or run a pretrained AI model in the DeepMind Starcraft II environment. 

## Dependencies 

- pysc2 (Deepmind) [https://github.com/deepmind/pysc2]
- baselines (OpenAI) [https://github.com/openai/baselines]
- s2client-proto (Blizzard) [https://github.com/Blizzard/s2client-proto]
- Tensorflow 1.3 (Google) [https://github.com/tensorflow/tensorflow]

## Usage


## 1. Get PySC2

### PyPI

The easiest way to get PySC2 is to use pip:

```shell
$ pip install pysc2
```

Also, you have to install `baselines` library.

```shell
$ pip install baselines
```

## 2. Install StarCraft II

### Mac / Win

You have to purchase StarCraft II and install it. Or even the Starter Edition will work.

http://us.battle.net/sc2/en/legacy-of-the-void/

### Linux Packages

Follow Blizzard's [documentation](https://github.com/Blizzard/s2client-proto#downloads) to
get the linux version. By default, PySC2 expects the game to live in
`~/StarCraftII/`.

* [3.16.1](http://blzdistsc2-a.akamaihd.net/Linux/SC2.3.16.1.zip)

## 3. Download Maps

Download the [ladder maps](https://github.com/Blizzard/s2client-proto#downloads)
and the [mini games](https://github.com/deepmind/pysc2/releases/download/v1.0/mini_games.zip)
and extract them to your `StarcraftII/Maps/` directory.

## 4. Train it!

```shell
$ python train_mineral_shards.py
```

## 5. Enjoy it!

```shell
$ python enjoy_mineral_shards.py
```

## Credits

The credits for this code go to [chris-chris](https://github.com/chris-chris/pysc2-examples). I've merely created a wrapper to get people started. 
