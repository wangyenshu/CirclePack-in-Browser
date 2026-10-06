Built using the openjdk21 emscripten port https://github.com/emscripten-forge/recipes/pull/6206.

The cpcore.jar is built using apache ant from a patched source: https://github.com/wangyenshu/CirclePack/tree/patch. The only modification is https://github.com/wangyenshu/CirclePack/blob/06a962355c505b48c994d3a98e1c714145936b37/src/cpTalk/sockets/CPMultiServer.java.

Drag and drop is fixed. packings and scripts are in `/app/cpcore/packings` and `/app/cpcore/scripts` respectively.

The app built using the closed source cheerpj is moved to https://github.com/wangyenshu/CirclePack-cheerpj.

Credit:

circlepack: http://www.circlepack.com/software.html
