Ref-uis
=======


Presentation
------------

*ref-uis* is the mini-server package for enabling the local installation of the web-ui.

Usually, this mini-server package ref-uis is part of a mono-repo containing an other package for the web-ui and potentially an *universal* library backing the web-ui.


Requirements
------------

- [node](https://nodejs.org) > 22.0.0
- [npm](https://docs.npmjs.com/cli) > 11.0.0


Installation
------------

```bash
npm i -D ref-uis
```


Usage
-----

```bash
npx ref-uis
npx ref-uis --help
```


Usage without installation
--------------------------

```bash
npx ref-uis
npx --package=ref-uis ref-uis
npx --package=ref-uis ref-uis --help
```

