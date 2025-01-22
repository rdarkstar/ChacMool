# ChacMool

ChacMool is a fork of emesene, an instant messenger capable of connecting to XMPP
that uses different graphical toolkits.
Currently XMPP (jabber) it's supported through papyon and Slixmpp,
which allows emesene to connect to various IM services such as
Windows Live Messenger, GTalk, Facebook Chat, etc.

## Useful links

* [Main repository](https://github.com/rdarkstar/ChacMool/)
* [Old Wiki](http://wiki.github.com/emesene/emesene)

## Upstream libraries repositories

emesene embeds in its codebase a number of python libraries for the different
service it supports. We embed them instead of using git submodules so we can
make packagers' life better and hotfix eventual bugs.

* [papyon] (https://github.com/emesene/papyon)
* [SleekXMPP] (https://github.com/fritzy/SleekXMPP) (OLD)
* [pyfb] (https://github.com/jmg/pyfb)
* [libwebqq](https://github.com/linuxqq/libwebqq)
