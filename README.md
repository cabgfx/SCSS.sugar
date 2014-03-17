SCSS.sugar
=============

Make Espresso.app recognize .scss files as CSS

## Installation

Clone repo:
```bash
$ git clone git@github.com:cabgfx/SCSS.sugar.git
```

Symlink it into Espresso's `Sugars` directory:
```bash
$ cd ~/Library/Application\ Support/Espresso/
$ mkdir -p Sugars # Creates Sugars folder, if it doesn't already exist (eg. a fresh install of Espresso)
$ ln -s PATH/TO/YOUR/CHECKOUT Sugars/SCSS.sugar
```

That's it. Relaunch Espresso and hack away!

---

### Credit
Big thanks to Ian Beck ([@ianbeck](https://twitter.com/ianbeck)) for his writeup on [Custom file extensions and Espresso 2](http://beckism.com/2013/12/custom-extensions-and-espresso/). Installing a Sugar like this keeps your customizations safe from being overwritten with future updates to Espresso.

---

#### License
MIT. See [LICENSE](https://github.com/cabgfx/SCSS.sugar/blob/master/LICENSE)
