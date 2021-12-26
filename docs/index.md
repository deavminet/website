# Welcome to DNET!

Welcome to the DNET homepage where you can find information on everything related to the DNET protocol. This
includes documentation on the protocol, server implementations, API and library documentation and client
softwares.

## News

DNET is currently going through a complete re-write which includes the following:

1. Re-speccing the client/server protocol
    * This includes switching to a ProtocolBuffer-encoded message format
    * Adding task IDs to the messages for a task/event-based protocol
2. Client rewrites
    * Re-writing the GTK client - Gustav
    * Re-writing the terminal client, skippy
    * Integrating [tasky]() to provide task/event-based protocol handling on the client side

## Contents

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Getting started

If you want to get connected to a DNET-based network then there are a few things you should take a look
at. You first will need to [find a server]() of which you can connect to using a client. Thye next thing
you may want then take a look at is _which_ client you will be using to do so, whether or not you want a
graphical/GUI-based client or a text-based client that can run in your terminal, all of this can be found
on the [choosing a client]() page.

