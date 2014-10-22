#threejs-nanopore

Nanopore device drawn with threejs


## Installing dependencies

[index.html](index.html) expects certain dependencies. 

1. `bower_components/threejs/build/threejs.min.js`
2. `bower_components/stats.js/build/stats.min.js`

You can install these dependencies a couple of ways:

1. Using [bower](bower.io) to install dependencies.

  ```bash
$ bower install
  ```

2. Download the dependencies and put them in the appropriate subdirectory yourself.

  ```bash
$ mkdir -p bower_components/threejs/build
$ cd bower_components/threejs/build
$ wget http://threejs.org/build/three.min.js   # for three.js
$ wget https://github.com/mrdoob/stats.js/raw/master/build/stats.min.js   # for stats.js
  ```

# Creating the JSONLoader-ready model

The blender file is located at [models/chip.blend](models/chip.blend).
You should install the [Three.js Blender Import/Export](https://github.com/mrdoob/three.js/tree/master/utils/exporters/blender) addon for [Blender](http://www.blender.org/) and export the Threejs model to [models/chip.js](models/chip.js).


## Viewing

Start a simple server any way you know how, for example

```bash
$ python -m SimpleHTTPServer
```

And point your browser to the appropriate address, in this case [http://localhost:8000](http://localhost:8000).
