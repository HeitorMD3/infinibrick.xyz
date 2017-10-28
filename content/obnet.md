---
title: "OBNet"
---
OBNet is the network of servers that support the infrastructure used for the development of OpenBlox and other software hosted by the OpenBlox project.

## Servers

OBNet comprises the servers described in this section. These servers are listed in order of addition.

### Stargazer

Stargazer runs Debian Jessie and hosts MediaWiki (wiki.openblox.org), cgit (git.openblox.org), GNU Mailman (lists.openblox.org), ownCloud (cloud.openblox.org), Bugzilla (bugs.openblox.org), and Jenkins (ci.openblox.org).

### Daedalus

Daedalus is the mail gateway and the entry point for SSH access. It also hosts the Internet Relay Chat hub and the Shalture services for the IRC network, as well as [Bloxbot](https://git.openblox.org/openblox/bloxbot). Daedalus runs Debian Jessie.

### Mars

Mars is a droplet hosted on DigitalOcean which hosts the news server (news.openblox.org) and a ZNC bouncer for contributors. Both mars.openblox.org and developer.openblox.org resolve to Mars. Mars runs Fedora 25.
