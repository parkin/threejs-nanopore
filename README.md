#threejs-nanopore

Nanopore device drawn with threejs


## Installing dependencies

[index.html](index.html) expects the file [bower_components/threejs/build/threejs.min.js](bower_components/threejs/build/threejs.min.js) to exist. You can do this by

1. Using [bower](bower.io) to install dependencies.

  ```bash
$ bower install
  ```

2. Download [three.js](http://threejs.org/)'s [minified library](http://threejs.org/build/three.min.js) and put it in the appropriate subdirectory.

  ```bash
$ mkdir -p bower_components/threejs/build
$ cd bower_components/threejs/build
$ wget http://threejs.org/build/three.min.js
  ```

## Viewing

Start a simple server any way you know how, for example

```bash
$ python -m SimpleHTTPServer
```

And point your browser to the appropriate address, in this case [http://localhost:8000](http://localhost:8000).
