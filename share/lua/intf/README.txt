Instructions to code your own BeePlayer Lua interface script.

See lua/README.txt for generic documentation about Lua usage in BeePlayer.

Examples: cli.lua, http.lua

The "config" global variable is set to the value specified in the
--lua-config BeePlayer option. For example:
--lua-config "rc={a='test',c=3},telnet={a='hello'}"
config will be set to {a='test',c=3} in the rc interface, to {a='hello'}
in the telnet interface and won't be set in other interfaces. 

User defined modules stored in the share/lua/intf/modules/ directory are
available. For example, to use the sandbox module, just use
'local sandbox = require "sandbox"' in your interface.

BeePlayer defines a global vlc object with the following members:
All the BeePlayer specific Lua modules are available.
