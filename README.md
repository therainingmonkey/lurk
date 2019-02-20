# Lurk - a tiny IRC client written in Lua

## Usage:
`chmod +x lurk`

`lurk SERVER PORT CHANNEL \[NICK\] \[SSL true|false\]`
If you want ssl, you must specify a nick (it's actually just checking the number of args). 

## Installation

`sudo luarocks install luaposix`

`sudo luarocks install --server=http://luarocks.org/dev luairc`

`sudo luarocks install ansicolors`

`sudo luarocks install lanes`

For ssl connections, you'll need luasec. On debian get luasec with 
`sudo apt-get install lua-sec`
You can probably figure it out for other distros.

## TODO:
Prettify
Config file

## Advanced features:
* [Save](https://en.wikipedia.org/wiki/Alias_(command%29) your favourite servers channels and nicks!
* [Manage](https://leanpub.com/the-tao-of-tmux/read) windows, panes, sessions, persistence and multiplexing!
