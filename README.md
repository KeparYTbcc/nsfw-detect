# ✨ NSFW Classifier API ✨
Rest API Written In Python To Classify NSFW Images.

[![Python](http://forthebadge.com/images/badges/made-with-python.svg)](https://python.org)
[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/TheHamkerCat/)

# Fastest Solution

If you don't want to selfhost it, there's already an instance of this running [here](https://nsfw-detect.herokuapp.com?url=)

## Install Locally Or On A VPS

```sh
$ git clone https://github.com/KeparYTbcc/nsfw-detect

$ cd NSFW_Detection_API

$ pip3 install -U -r requirements.txt

$ python3 -m api
```

## Quick use:

```sh
$ curl http://127.0.0.1/?url=https://nsfwimage.com/image.png
```
## Classifies

* **Hentai** - Hentai and pornographic drawings
* **Porn** - Pornographic images, sexual acts
* **Drawings** - Safe for work drawings (including anime)
* **Neutral** - Safe for work neutral images
* **Sexy** - Sexually explicit images, not pornography

# Credits

Thanks to https://github.com/GantMan/nsfw_model/ for their model.
