Build-Bonita-BPM
================

The script to build Bonita BPM Engine, Portal and Studio from official sources
------------------------------------------------------------------------------

This script has been tested on Debian GNU/Linux Jessie, with Oracle JDK 8u152, Maven 3.5.2 (latest stable as at 9th Dec 2017).

Around 4 GB of dependencies will be downloaded (sources, Maven dependencies, ...). A fast internet connection is recommended.
Place this script in an empty folder on a disk partition with more than 15 GB free space.

Then, run 'bash build-script-7.6.0.sh' in a terminal.

Once finished, you will find a working build of Bonita BPM in: `bonita-studio/all-in-one/target`.


Requirements
------------

This script is designed for Linux Operating System. You are of course free to fork it for Windows or Mac.
