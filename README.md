# Nand2Tetris HDL Visualizer Image Saver

Hacked this together in a couple of hours. Basically just a puppeteer wrapper for [this amazing visualizer extension created by @jainpranav1](https://github.com/jainpranav1/Nand2Tetris-HDL-Visualizer). 

## Usage

Just clone the repo, install the necessary packages using `npm install` and run the script using `npm start`.

Pass the folder with the wanted HDL files as the only argument.

```bash
$ npm start ../Nand2Tetris/projects/01

Processing ../Nand2Tetris/projects/01/And.hdl
Saved And.png
...
```

The images will be saved to the same folder as the .hdl files.