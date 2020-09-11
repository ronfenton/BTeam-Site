# B-Team GitHub Pages Site

## Requirements

HTML & CSS knowledge, NodeJS if you want a nicer DevOps experience.

## Quickstart

You can lint/prettify the files quickly by running:

`make happy` in a Bash/ZSH/\*nix environment, or:

`npx prettier --write --loglevel silent .` in your CLI of choice (eg. PowerShell).

You can also run a server that live-reloads changes as you go by running:

`make serve` in a Bash/ZSH/\*nix environment, or:

`npx live-server` in your CLI of choice (eg. PowerShell).

The hot loading config is located in `.live-server.json` on the project root. You can see the configuration options [here](https://www.npmjs.com/package/live-server#usage-from-node).

> Watch out for any browser plugins that inject stuff above the head of the document; it'll break hot reloading.

## Other

- `.nvmrc`, a configuration file for [Node Version Manager](https://github.com/nvm-sh/nvm) is located in the project root. This locks your version of NodeJS to the specified version. If you don't have NVM running locally, it won't do anything.
