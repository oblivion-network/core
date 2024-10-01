Oblivion Core
=============

Setup
---------------------
Oblivion Core is the original Oblivion client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Oblivion transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Oblivion Core, visit [oblivion.org](/).

Running
---------------------
The following are some helpful notes on how to run Oblivion Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/oblivion-qt` (GUI) or
- `bin/obliviond` (headless)

### Windows

Unpack the files into a directory, and then run oblivion-qt.exe.

### macOS

Drag Oblivion Core to your applications folder, and then run Oblivion Core.

### Need Help?

* See the documentation at the [Oblivion Wiki](https://oblivion.info/) for help and more information.
* Ask for help on [#oblivion](https://webchat.freenode.net/#oblivion) on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#oblivion).
* Ask for help on the [OblivionTalk](https://obliviontalk.io/) forums, in the [Technical Support board](https://obliviontalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build Oblivion Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The Oblivion repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://doxygen.bitcoincore.org/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [OblivionTalk](https://obliviontalk.io/) forums.
* Discuss general Oblivion development on #oblivion-dev on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#oblivion-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
