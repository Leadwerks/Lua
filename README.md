# Lua for Visual Studio

Just add these files into your Lua file and everything will work. This is using Lua 5.1.5 and VS 2019 but it should be easy to reconfigure for other versions.

lusconf.h is included with LUA_IDSIZE changed from 60 to 2048. This eliminates the problem of file paths being truncated in error messages.
