JokeCoin Core
==========

This is the official reference wallet for Jokecoin digital currency and comprises the backbone of the Jokecoin peer-to-peer network. You can [download JokeCoin Core](https://www.jokecoin.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run Jokecoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/jokecoin-qt` (GUI) or
- `bin/jokecoind` (headless)

### Windows

Unpack the files into a directory, and then run jokecoin-qt.exe.

### OS X

Drag Jokecoin-Qt to your applications folder, and then run Jokecoin-Qt.

### Need Help?

* See the [Jokecoin documentation](https://docs.jokecoin.org)
for help and more information.
* See the [Jokecoin Developer Documentation](https://jokecoin-docs.github.io/) 
for technical specifications and implementation details.
* Ask for help on [Jokecoin Nation Discord](http://jokecoinchat.org)
* Ask for help on the [Jokecoin Forum](https://jokecoin.org/forum)

Building
---------------------
The following are developer notes on how to build JokeCoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The JokeCoin Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [Jokecoin Forum](https://jokecoin.org/forum), in the Development & Technical Discussion board.
* Discuss on [Jokecoin Nation Discord](http://jokecoinchat.org)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
JokeCoin Logo contains "Jester Hat" image (c) by Madeleine Bennett (CCBY).