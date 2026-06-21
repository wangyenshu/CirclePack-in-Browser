The cpcore.jar is built using apache ant from a patched source: https://github.com/wangyenshu/CirclePack/tree/patch. The only modification is https://github.com/wangyenshu/CirclePack/blob/06a962355c505b48c994d3a98e1c714145936b37/src/cpTalk/sockets/CPMultiServer.java.

If you want to host it on root directory, change all `/app/CirclePack-in-Browser` to `/app`. If you want to host it on another directory, say `xyz`, then change all `/app/CirclePack-in-Browser` to `/app/xyz`.

Credit:

circlepack: http://www.circlepack.com/software.html

cheerpj: https://cheerpj.com/
