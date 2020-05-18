# pihole5-list-tool
This tool allows quickly bulk adding __block lists__ to your [Pi-hole 5](https://pi-hole.net/) setup.


Currently there are three _sources_ available to use:
- [firebog.net](https://firebog.net/)
  - Non-crossed lists: For when someone is usually around to whitelist falsely blocked sites
  - Ticked lists: For when installing Pi-hole where no one will be whitelisting falsely blocked sites
  - All lists: For those who will always be around to whitelist falsely blocked sites
-  A file you have - one url per line
-  Pasting in a list - one url per line


The source of each list is visible in the web interface and an option to load the lists for immediate use is available after adding.

## requirements
[python 3.6+](https://python.org/) is required. That is available by default on Raspbian, so it should be available on your system.


## installation
If you don't **sudo pip3 install**, things won't work in a confusing way.
```bash
$ sudo pip3 install pihole5-list-tool
```

## running
Simply run:
```bash
$ sudo pihole5-list-tool
```

Here's what installing and running it will look like:

[![asciicast](https://asciinema.org/a/331296.svg)](https://asciinema.org/a/331296)