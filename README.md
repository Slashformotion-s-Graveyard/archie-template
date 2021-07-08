# Archie template

## How to use it 

1. Fork me
2. Change the values in the `_config.yml` file
3. You can customize the `about.md` page

## Setup for CI

This theme uses `jekyll-archives` gem which is not supported by GitHub Pages. If you want to use full features like categories and tags, I recommend you to use the github action workflow action included in this repo. If you don't want it delete the `.github` folder. 


After this, we should provide permissions for this action to push to the gh-pages branch:

- Create a Personal Token with repos permissions and copy the value (check your settings on github).
- Go to your ***repository’s*** Settings and then switch to the Secrets tab.
Create a token named `GH_TOKEN` (important) using the value copied.