# three_dart

Dart 3D library. an easy to use, lightweight, cross-platform, general purpose 3D library. 

three.js rewrite by Dart. 3D for Flutter. Base on [flutter_gl](https://github.com/wasabia/flutter_gl)


support Web, iOS, Android, macOS, Windows, Linux

three.js r138


Example Demo on flutter web [https://wasabia.github.io/three_dart_example/#/](https://wasabia.github.io/three_dart_example/#/)


## Getting Started

First at all. Follow flutter_gl Usage [flutter_gl](https://github.com/nyaneet/flutter_gl)


TODO


## Usage

check example project

```
camera = new three.PerspectiveCamera( 40, 1, 0.1, 10 );
camera.position.z = 3;

scene = new three.Scene();
camera.lookAt(scene.position);

scene.background = three.Color(1.0, 1.0, 1.0);
scene.add( new three.AmbientLight( 0x222244, null ) );

var geometryCylinder = new three.CylinderGeometry( 0.5, 0.5, 1, 32 );
var materialCylinder = new three.MeshPhongMaterial( { "color": 0xff0000 } );

mesh = new three.Mesh( geometryCylinder, materialCylinder );
scene.add( mesh );
```


## Example

```
cd example && flutter run
```


![3](https://user-images.githubusercontent.com/1768228/141482294-b78446b3-d9ab-4cc0-83fc-dbabaab459e2.png)


## TODO
- unit test
- more example
- README && Document
- and so on...

## Issues
File any issues, bugs, or feature requests.

## Contributing
Pull request please!

## Libraries and Plugins

[https://github.com/nyaneet/three_dart_jsm](https://github.com/wasabia/three_dart_jsm)

[https://github.com/wasabia/opentype](https://github.com/wasabia/opentype)

[https://github.com/wasabia/typr_dart](https://github.com/wasabia/typr_dart)

