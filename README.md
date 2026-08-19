# TFRN
Code and data of paper: A texture feature removal network for sonar image classification and detection

## Image Assets

A high-quality SVG fighter jet image has been added to the repository:

| File | Description |
|------|-------------|
| [`assets/fighter-jet.svg`](assets/fighter-jet.svg) | Cinematic-style modern stealth fighter jet piercing clouds with golden sunlight, 1600×900 (写实电影风格战斗机) |
| [`assets/fighter-jet.html`](assets/fighter-jet.html) | Showcase / preview page for the SVG image |

![Fighter Jet Preview](assets/fighter-jet.svg)


because the upload files must <25M, so i upload the source code on Baidu Netdisk.

link（链接）：https://pan.baidu.com/s/13AVBrjYFFR4IGzryoN634g?pwd=w4mw 
extract code (提取码)：w4mw 

and a few note:
1, i'm so sorry that i have forgotten the detail of this code, but i make lots of #note

2、I remember the single_convert.py is used to debug the algorithm.

3, if the debug results seems fine, then i will use batch_convert.py to generate the whitened dataset, then train a NN under the whitened dataset, and at the same time, train a NN with original dataset, so that my algorithm could be compared.

4, finally, start with single_convert.py is recommended
