# Dotfiles PI4 Dasung

<img src="dasung-paperlike-3-pi-4-close-up.jpg" width="200"/><img src="dasung-paperlike-3-pi-4.jpg" width="200" />

This repo is here to help you use your Dasung e-Ink monitor with your Raspberry PI.

## Steps

1. Copy the parts of the [`config.txt`](config.txt) you need to the `config.txt` file on your boot SD card.

2. When you start up your Raspberry PI, you should now see the login screen on your Dasung monitor.

    > Note: I am using this on [Raspberry PI4](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/), with [Dasung Paperlike 3 HD-FT](https://www.amazon.com/Dasung-Paperlike-Front-Light-Touch-Monitor/dp/B07SKS6CS7). You may need to adjust the resolution if your monitor is not capable of the Paperlike 3 resolution.

3. Copy the [`bin`](bin/)  files from this repo to your home/bin folder `~/bin`.

    > The bin files contain a few functions to make life easier. More below in the Usage section.

4. Run the `bin/startup` command. This should adjust your color pallette to give you a white-on-black screen with a virtual resolution of 512 x 384.

---

[Blog](https://f1lt3r.io) | [Instagram](https://www.instagram.com/f1lt3r/)