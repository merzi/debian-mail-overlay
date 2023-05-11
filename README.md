## hardware/debian-mail-overlay

This overlay base image contains Debian 11 "Bullseye" slim (remove some extra files that are normally not necessary within containers, such as man pages and documentation), compile skarnet.org's small & secure supervision software suite (skalibs, execline, s6) and build Rspamd, the fast, free and open-source spam filtering system.

Software built from source :

* Skalibs 2.13.1.1 : <https://skarnet.org/software/skalibs/>
* Execline 2.9.3.0 : <https://skarnet.org/software/execline/>
* s6 2.11.3.2 : <https://skarnet.org/software/s6/>
* Rspamd 3.5 : <https://rspamd.com/>
* Gucci 1.6.6 : <https://github.com/noqcks/gucci/>

Please see the [main repository](https://github.com/mailserver2/mailserver) for instructions.
