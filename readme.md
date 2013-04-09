# minecraft-chunk

read voxel data from minecraft chunks

extracted from code originally written by @ithkuil for [mcchunkloader](https://github.com/ithkuil/mcchunkloader), turned into a module and now maintained by @maxogden

minecraft is property of Mojang AB

```javascript
var mcChunk = require('minecraft-chunk')

var options = {
  nbt: nbt, // from the minecraft-nbt module
  ymin: 0,
  showstuff: false,
  superflat: false,
  chunkX: 0,
  chunkZ: 0
}

mcChunk(options).extractChunk(function onVoxel(x, y, z, type) {
  
})
```

this module is used by [minecraft-mca](http://github.com/maxogden/minecraft-mca)

designed for use with [browserify](http://browserify.org)

# license

BSD