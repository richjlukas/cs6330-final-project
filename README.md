# CS 6230 Final Project

This repository contains data and notebooks for gait analysis.

## Authors

- Robert Burkhardt
- Rich Lukas
- Dan Olson

## Requirements

* Python 3
* Git
* Git LFS

## Getting Started

```sh
# Reqs
brew update
brew upgrade
brew install python3 git-lfs graphviz
git lfs install

# Get repo
git clone git@github.com:rgeorgebu/cs6330-final-project.git
cd cs6330-final-project

# Setup env
python3 -m venv .
source bin/activate
pip install -r requirements.txt

# Start
jupyter notebook
```

### Tracking New Dependencies
```sh
pip freeze --all > requirements.txt
git add requirements.txt
git commit -m "Updating dependencies"
git push
```

### Tracking Resource Files

```sh
git lfs track "*.csv"
git lfs track "*.pdf"
git lfs track "*.tsv"
git lfs track "*.html"
```
