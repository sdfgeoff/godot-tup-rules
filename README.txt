Tup ( http://gittup.org/tup/ ) is a build system that is much more reliable
than traditional systems like Make. It keeps track of both input and output
files, and as a result it's builds are very stable (eg: it auto-discovers
dependencies that you don't explicitly list - such as linked blend files).
This repo contains a tupfile and a set of tools for working with Godot
projects. It automates:

1. Any blend file matching `*.escn.blend` will be exported to an escn file (ie a model or scene)
2. Any blend file matching `*.png.blend` will be rendered to PNG
3. Any gimp xcf files will be exported to PNG

Future additions:

1. POssibly add GLTF support as a model/scene pipeline
