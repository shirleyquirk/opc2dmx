## opc2dmx
OPC to DMX server, forked and split off from fcserver

fcserver is unmaintained and uses ancient libusbx as its backend, which doesnt work on osX anymore.

we dont use fadecandies anymore, but we do need an OPC->DMX server.

so fork fcserver, delete everything we dont need. 
verify it still works on linux.
port the libusb calls to libusb-latest
verify it still works
verify it works on osX
