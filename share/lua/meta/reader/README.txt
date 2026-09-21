Instructions to code your own BeePlayer Lua meta script.

See lua/README.txt for generic documentation about Lua usage in BeePlayer.

Examples: See filename.lua .

BeePlayer Lua "meta reader" modules should define one of the following functions:
 * read_meta(): returns a path to an artwork for the given item

Available BeePlayer specific Lua modules: msg, stream, strings, variables, item,
objects and xml. See lua/README.txt

Note, those scripts are supposed to be fast. Read non blocking, no IO.
