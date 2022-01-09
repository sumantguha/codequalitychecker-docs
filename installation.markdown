---
layout: page
title: Installation
permalink: /install/
---

Installation
============

It's recommended to use the latest version of Python. `CodeQualityChecker` supports **Python 3.5** and newer. Install [python3](https://www.python.org/downloads/) and ``pip`` (can use ``brew install python`` on unix systems if 
homebrew is installed)

### Installing the checker
Clone the repo: `git@github.com:sumantguha/CodeQualityChecker.git`

### Dependecies
Run `python3 -m pip install -r requirements.txt` to install all the required dependencies.

### Running the checker
Run `python3 main.py config_path debug=False post_to_ed=True`