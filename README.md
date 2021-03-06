---
layout: default.html
---

## Sicilia Style Guide [![Build Status](https://travis-ci.org/sicilia-io/style-guide.svg?branch=master)](https://travis-ci.org/sicilia-io/style-guide)

Lista di risorse utili per l'impaginamento.
Punto di riferimento per Articolisti e Designers Siciliani.


## Installation
```
git clone git@github.com:Ideabile/monera.git && cd monera
```

## Usage
```
make build
```

## Contributing
This isn't the main project and since this is a Kingdom.
And the only purpose of this repository is documenting how to develop with our resources.

However you're contributions are also welcome here.

We suggest to take a look to the Organism list bellow that monera is officially compose by.
Or you can suggest/submit new Organism.

You can still apply your contributions to this repo by:

  1. Fork it!
  2. Create your feature branch: `git checkout -b my-new-feature`
  3. Commit your changes: `git commit -am 'Add some feature'`
  4. Push to the branch: `git push origin my-new-feature`
  5. Submit a pull request :D

## Development
We require you to have `npm` and `node` installed to make able to install [`browser-sync`](http://www.browsersync.io/),
additionally we download and compile [`fsWatch`](http://github.com/emcrisostomo/fswatch) to run `make build` every-time that a file change.
```
make install-dev && make dev-start
```
Now you can do your changes in the content, and when you save them they would be compile, and your browser refresh automatically.

*Note: We also use ngnix machine to start the server, and our ip address is set to 192.168.99.100 for our local development, you maybe want to change it, if for your case is different in the Makefile, but please don't commit them.*

## Create your first website with Travis and Github Pages
This documentation is a live example in how you could change your

  1. Fork it!
  2. Create a [GitHub Authentication token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/)
  3. Add your repository to travis.
  4. Add your `GH_TOKEN` to travis `travis encrypt GH_TOKEN=secretvalue`
  5. Commit and push.
  6. Enjoy your website at `http://<username>.github.io/<repo-name>/`

Every change on master would recreate your gh-pages branch. Enjoy :-)

## Other organisms

  - [monera-transformer](https://github.com/Ideabile/monera-static-transformer) - The first organism, a static trasformer for your ui's.

## Credits

  - [Mauro Mandracchia ~ Author](http://www.ideabile.com)
