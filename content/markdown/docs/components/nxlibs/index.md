.. pub: 1
.. description: Compressed and cached X11 for Remote Desktop/Application Computing
.. title: NXv3 (aka nx-libs)


# nx-libs (nxagent, nxproxy)

NXv3 is a software suite which implements very efficient
compression of the X11 protocol. This increases performance when
using X applications over a network, especially a slow one.

## NXv3 Agent ##

nxagent is an agent providing NX transport of X sessions. The application
is based on the well known Xnest "nested" server. nxagent, like Xnest,
is an X server for its own clients, and at the same time, an X client
for a system's local X server.

The main scope of nxagent is to eliminate X round-trips or transform
them into asynchronous replies. nxagent works together with nxproxy.
nxproxy itself does not make any effort to minimize round-trips
by itself, this is demanded of nxagent.

Being an X server, nxagent is able to resolve all the property/atoms related
requests locally, ensuring that the most common source of round-trips are
nearly reduced to zero.

## NXv3 Proxy

nxproxy provides NXv3 support for X11 connections with or without an NXv3
agent on the server side. You can either connect two NXv3 proxy instances
with each other (one in -S and one in -C mode), or you can connect NXv3
proxy (-S mode) with an instance of NXv3 agent.
