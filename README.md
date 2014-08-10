lancache
========

Game Update Caching for LAN Parties

Initially pulled from http://blog.multiplay.co.uk/2014/04/lancache-dynamically-caching-game-installs-at-lans-using-nginx/

This repository will include my changes to adapt the configuration from FreeBSD to Linux and tweak the paths to fit my environment.

To utilize these config files, install nginx version 1.6.0 or greater and place these files in the configuration directory (usually /etc/nginx).  You will need the mime.types file from the distribution, otherwise everything else can be empty.

You will need to set up virtual IP addresses and DNS records as described in the original blog post.

**NOTICE: Debian versions before jessie and all versions of Ubuntu as of this writing do not have a recent enough version of nginx in their repositories.  You must install a newer version some other way.**

nginx offers official repositories for many popular distros, that would be my recommendation.
