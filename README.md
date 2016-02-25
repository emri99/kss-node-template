kss-node-template
=================

This is a **template** for [kss-node](https://github.com/kss-node/kss-node) styleguide.
"kss-node" is a NodeJS implementation of [Knyle Style Sheets](https://github.com/kneath/kss) (KSS).
kss-node enables us to generate a beautiful styleguide for CSS, of course that suports LESS, SASS and Stylus.

You can see the example styleguide from the left navi.


Demo
----
**[Example Styleguide](http://emri99.github.io/kss-node-template/)**

### Features
* For keeping compatible with your any CSS, optimize the document's style code.
* Make the side navi interactive. That also shows the child sections in the showing page.
* Improve the style of markdown content for readability.


Download
--------
**[kss-node-template](https://github.com/emri99/kss-node-template/archive/master.zip)** [zip] or

```
git clone git://github.com/emri99/kss-node-template.git
```

**Note:** This package contains only template files.
You have to install kss-node at first.


How to apply this template
--------------------------
1. Install kss-node. Type `npm install kss` or `npm install -g kss` for global CLI.
2. Install kss-node-template. Type `npm install emri99/kss-node-template --save-dev`
3. Run `kss-node` command with `--template` option, like below.

```
kss-node <sourcedir> --template node_modules/kss-node-template/template
```


License
-------
Copyright (c) 2013-2015 Hiroyuki Tanjo. Licensed under the [MIT License](LICENSE).
