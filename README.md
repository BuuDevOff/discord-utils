# 🤖 Discord Utils 🤖

This code is for educational purposes only!

## Features

- [ ] Token checker
- [ ] Token joiner
- [ ] Token verifier
- [ ] Token humanizer
- [ ] DM bomber
- [ ] Friends bomber
- [ ] Guild message bomber
- [ ] Guild data scraper
- [ ] Guild explore data scraper
- [ ] Recursive guild data scraper

## How it works?

This tool was made using Node.js and [discord.js-selfbot-v13](https://github.com/aiko-chan-ai/discord.js-selfbot-v13) library by [aiko-chan-ai](https://github.com/aiko-chan-ai).

This tool is a single-threaded project written in JavaScript using Node.js.

#### Supported Captcha Solving Services
- [ ] **fCaptcha** (Currently works with hCaptcha Enterprise)
- [ ] **hCaptcha** (Currently works with hCaptcha Enterprise)
- [x] **CapMonster** ("Doesn't support hCaptcha Enterprise" PATCHED)
- [x] **2Captcha** ("Doesn't support hCaptcha Enterprise" PATCHED)

## Installation

Run this command inside the root of the project:

> npm install

Then configure `config.json` or directly run this command inside the project for CLI-assisted configuration:

> node index.js --config

To start the script, run:

> node index.js

## Arguments

To use arguments, prefix them with `--` after `node index.js`:

> node index.js `...args`

- `no-logs` or `nl`: Removes all additional output.
- `debug` or `dbg`: Enables all debug output.
- `config` or `cfg`: Starts assisted configuration mode.

## License

This code is under the MIT License. See the LICENSE file for more details.
