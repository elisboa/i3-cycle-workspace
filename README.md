# i3-cycle-workspace


## Description

A simple tool that cycles a workspace between monitors

This tool is used to switch a i3 workspace between monitors when called.

Original code from: https://gitlab.inria.fr/snippets/32 from [Daan Wynen](https://gitlab.inria.fr/dwynen)

## Prerequisites

You must install i3 lib on pip:
```
pip install i3-py
```

## How to use

On your `$HOME/.i3/config`, you should add these lines, so you can call it with a keyboard shortcut:

```
# Cycle workspace
bindsym $mod+c exec --no-startup-id /home/elisboa/.py/i3-cycle-workspace.py
```

After saving this file, you should restart your i3 session ($mod + shift + r) for the changes to take effect


## Ideas for future releases

- suppot arguments from command line when called
- have a config file
- automatically switch workspaces based on number or name when attaching or detaching a second monitor

