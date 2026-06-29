# ReModel Documentation

[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)

A website to host documentation relating to the ReModel: Read, Run, Reuse Open Simulation Models project.

## How to contribute

1. Ensure that you have [Quarto](https://quarto.org/docs/get-started/) installed on your machine
1. [Clone this repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) to your local machine
1. Checkout the main branch and ensure it is up to date with `git checkout main && git pull` in the terminal
1. Checkout a new branch `git checkout -b your-branch-name`
1. Make your edits in your branch and save your file. For the sessions, you will need to create new folders for each session, with an index.qmd within it. It's probably easiest to copy and paste from a previous session.
1. Preview your changes with `quarto preview .` in the terminal - your browser should open showing you what your changes will look like
1. When you're happy, add and commit your changes with `git add files/to/add` and `git commit -m "message about your commit"`
1. Push your changes to your branch on GitHub with `git push origin your-branch-name`
1. Make a pull request and wait for your changes to be approved. 
1. When your pull request is approved, merge it into the `main` branch.

## Publishing

The website will automatically be updated via GitHub actions whenever changes are merged into the `main` branch.

