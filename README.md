systools
========

fork of neko-systools ( https://code.google.com/p/neko-systools ) for Haxe 3/Neko 2


### Status ###
The files are updated and are _mostly working_ for all platforms - which means that it should be working as well as the old systools; For my own project goals, its current status is enough. I will, however, try to maintain it the best I can, if any issues are reported.

You are welcome to ask for new features; A broader version of systools is planned to be made from scratch, and with a more permissive license.

### Neko usage with OpenFL ###
OpenFL will not include **systools.ndll** by default when building for the Neko platform. To solve this you must include an additional line in your `project.xml` file, just after the `<haxelib name="systools" />` tag:
```xml
<ndll name="systools" haxelib="systools" />
```
